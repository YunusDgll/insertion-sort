# insertion-sort
[22,27,16,2,18,6] -> Insertion Sort

Yukarı verilen dizinin sort türüne göre aşamalarını yazınız. Big-O gösterimini yazınız. Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması. Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.

Çözüm:1

Adım Key= dizi [1] = [16,22,27,2,18,6] ✓
*27 sağa kaydı.
*22 sağa kaydı.

Adım Key= dizi [2] = [2,16,22,27,18,6] ✓
*27 sağa kaydı.
*22 sağa kaydı.
*16 sağa kaydı.

Adım Key= dizi [3] = [2,16,18,22,27,6] ✓
*27 sağa kaydı.
*22 sağa kaydı.

Adım Key= dizi [4] = [2,6,16,18,22,27] ✓
*27 sağa kaydı.
*22 sağa kaydı.
*18 sağa kaydı.
*16 sağa kaydı.

Çözüm:2
O(n^2)

Çözüm:3
Best case:2 
Worst case:27 
Average case:18

Çözüm:4
Ortaya yakın bir yerde olduğu için (18)Average Case'dir.

Çözüm:5 [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

1.Adım key dizi[1]= [3,7,5,8,2,9,4,15,6]
*7 sağa kaydı.

2.Adım key dizi[2]: [3,5,7,8,2,9,4,15,6]
*7 sağa kaydı.

3.Adım key dizi[3]: [2,3,5,7,8,9,4,15,6]
*8 sağa kaydı.
*7 sağa kaydı.
*5*sağa kaydı.
*3sağa  kaydı.

4.Adım key dizi[4]: [2,3,4,5,7,8,9,15,6]
*9 sağa kaydı.
*8 sağa kaydı.
*7 sağa kaydı.
*5 sağa kaydı.

