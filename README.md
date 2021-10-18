# insertionsortprojeodevi
Soru 1
--------------------
[22,27,16,2,18,6] -> Insertion Sort

Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
Big-O gösterimini yazınız.
Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.
Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.

Cevap:
Aşamaları
1) [22,27,16,2,18,6]
2) [2,27,16,22,18,6]
3) [2,6,16,22,18,27]
4) [2,6,16,18,22,27]


Big-O gösterimi ilk aşamada n değer için n defa 2.aşamada n-1 defa 3.aşamada n-3 defa kontrol sağlanmış
(n.(n+1))/2 =(n^2+n)/2 den   O(n^2) dir(n kare)

Time Complexity : (n^2)

Dizi sıralandıktan sonra 18 sayısı  Avarage case kapsamına girer

Soru 2
-------------
[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.
Cevap:
ilk dört aşaması
1) [7,3,5,8,2,9,4,15,6]
2) [2,3,5,8,7,9,4,15,6]
3) [2,3,4,8,7,9,5,15,6]
4) [2,3,4,5,7,9,8,15,6]
