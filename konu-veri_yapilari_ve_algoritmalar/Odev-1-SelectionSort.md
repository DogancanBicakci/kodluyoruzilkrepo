<!-- 
Proje 1
[22,27,16,2,18,6] -> Insertion Sort

1.Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

2.Big-O gösterimini yazınız.

3.Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız

Average case: Aradığımız sayının ortada olması
Worst case: Aradığımız sayının sonda olması
Best case: Aradığımız sayının dizinin en başında olması.

4.[7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız. 
-->

1.
[22,27,16,2,18,6]
[16,22,27,2,18,6]
[2,16,22,27,18,6]
[2,16,18,22,27,6]
[2,6,16,18,22,27]

2.
n+(n-1)+(n-2)+...+1 = (n*(n-1))/2 --> 1'den n'e kadar olan sayıların toplamından. Big-O = O(n^2)

3.
18 sayısı için ortada diyebiliriz diye düşünüyorum ve average case olur.

4.
[7,3,5,8,2,9,4,15,6]
[2,3,5,8,7,9,4,15,6] (2<=>7)
[2,3,4,8,7,9,5,15,6] (4<=>5)
[2,3,4,5,7,9,8,15,6] (8<=>5)
[2,3,4,5,6,9,8,15,7] (7<=>6)


