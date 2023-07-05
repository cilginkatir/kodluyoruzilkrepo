# kodluyoruzilkrepo
Kodluyoruz Eğitimi kapsamında açtığım ilk repo

1: [22,27,16,2,18,6] -> Insertion Sort

Yukarı verilen dizinin sort türüne göre aşamalarını yazınız. Çözüm: Big-O gösterimini yazınız. [22,27,16,2,18,6] == n [2,22,27,16,18,6]== n-1 [2,6,22,27,16,18] == n-2 [2,6,16,22,27,18] == n-3 [2,6,16,18,22,27] == 1

Big O Notation = n*(n+1)/2 =(n^2+n) / 2 = n^2 Big O Notation = n^2

2: Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız

Average case: Aradığımız sayının ortada olması Worst case: Aradığımız sayının sonda olması Best case: Aradığımız sayının dizinin en başında olması.

Çözüm:

Sıralı dizi: [2,6,16,18,22,27] Aradığımız sayı olan 18 sayısı dizinin ortasında bulunduğundan; uygun kapsam "Average Case"dir

3: [7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız. [7,3,5,8,2,9,4,15,6] n [2,7,3,5,8,9,4,15,6] n-1 [2,3,7,5,8,9,4,15,6] n-2 [2,3,4,7,5,8,9,15,6] n-3 [2,3,4,5,7,8,9,15,6] n-4

ÖDEV 2

Proje 2 [16,21,11,8,12,22] -> Merge Sort

Yukarıdaki dizinin sort türüne göre aşamalarını yazınız. Big-O gösterimini yazınız.

[16,21,11,8,12,22] [16,21,11] , [8,12,22] [16], [21,11], [8,12], [22] [16], [21], [11], [8], [12], [22] [11,16,21] , [8, 12, 22] [8,11,12,16,21,22] 2^x=n, logn=x O(n), Big-O gösterimi: O(nlogn)

Ödev 3: Binary Search Tree

Verilen dizi: [7, 5, 1, 8, 3, 6, 0, 9, 4, 2]

Binary Search Tree aşamaları:

Adım: 7 (root) Adım: 7 (root) Sağ: 8 Sol: 5 Adım: 7 (root) Sağ: 8 Sağ: 9 Sol: 5 Sağ: 6 Sol: 4 Sağ: 5 Sol: 2 Sol: 0 Adım: 7 (root) Sağ: 8 Sağ: 9 Sol: 5 Sağ: 6 Sol: 4 Sağ: 5 Sol: 2 Sol: 0 Sağ: 1
