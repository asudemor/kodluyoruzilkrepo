# kodluyoruzInsertionSortProject

[22,27,16,2,18,6] -> Insertion Sort

- Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
- Big-O gösterimini yazınız.
- Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.
- Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.


[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

[22,27,16,2,18,6] -> n
1-> [16,22,27,2,18,6] -> n-1
2-> [2,16,22,27,18,6] -> n-2
3-> [2,16,18,22,27,6] -> n-3
4-> [2,6,16,18,22,27] -> n-4

o(n^2)

Best Case = o(n)
Average Case = o(n^2)
Worst Case = o(n^2)

18 sayısı average case e girer.

-------------------------------------------------------------
[7,3,5,8,2,9,4,15,6]
1-> [3,7,5,8,2,9,4,15,6]
2-> [3,5,7,8,2,9,4,15,6]
3-> [2,3,5,7,8,9,4,15,6]
4-> [2,3,4,5,7,8,9,15,6]
