[22,27,16,2,18,6] -> Insertion Sort

1) Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
2) Big-O gösterimini yazınız.
3) Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.
4) Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.
Answers;

1
[22,27,16,2,18,6] - (n)

[2|,27,16,22,18,6] - (n-1)

[2,6|,16,22,18,27] - (n-2)

[2,6,16|,18,22,27] - (n-3)

2
Worst Case: O(n²) = n+(n-1)+(n-2)....+1

Average Case: O(n²)

Best Case: O(n)

3
Worst Case: [27,22,18,16,6,2]

Best Case: [2,6,16,18,22,27]

4
Dizimiz küçükten büyüğe sıralandıktan sonra [2,6,16,18,22,27] şeklini alır ve 18 sayısı ortanca değeridir.