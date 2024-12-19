<!--
Proje 2
[16,21,11,8,12,22] -> Merge Sort

1.Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.

2.Big-O gösterimini yazınız.
-->

1.
[16,21,11,8,12,22]
[16,21,11] & [8,12,22]
[16,21] & [11] & [8,12] & [22]
[16] & [21] & [11] & [8] & [12] & [22]

[16,21] & [8,11] & [12,22]
[8,11,16,21] & [12,22]
[8,11,12,16,21,22]

2.
Sıralama yaparken her satırda n-1 işlem yaptığımızdan O(n)
İşlem her seferinde yarıya indiği için 2^x=n -> x=log2n -> O(logn)
Big-O = O(nlogn)
