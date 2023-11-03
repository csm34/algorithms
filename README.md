# Algorithm
# Proje 1
[22,27,16,2,18,6] -> Insertion Sort

Yukarı verilen dizinin sort türüne göre aşamalarını yazınız. Big-O gösterimini yazınız.

1. [22,27,16,2,18,6]
2. [22,27,16,2,18,6]
3. [22,16,27,2,18,6] -> [16,22,27,2,18,6]
4. [16,22,2,27,18,6] -> [16,2,22,27,18,6] -> [2,16,22,27,18,6]
5. [2,16,22,18,27,6] -> [2,16,18,22,27,6]
6. [2,16,18,22,6,27] -> [2,16,18,6,22,27] -> [2,16,6,18,22,27] -> [2,6,16,18,22,27]

  Time Complexity: 
Insertion Sort'un Big-O gösterimi: O(n^2) (Quadratic time complexity)

  Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız.
Average case: Aradığımız sayının ortada olması.
Worst case: Aradığımız sayının sonda olması.
Best case: Aradığımız sayının dizinin en başında olması.
Bizim durumumuzda Average case kapsamına giriyor.

  [7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.
1. [2,3,5,8,7,9,4,15,6]
2. [2,3,4,8,7,9,5,15,6]
3. [2,3,4,5,7,9,8,15,6]
4. [2,3,4,5,6,9,8,15,7]
5. [2,3,4,5,6,7,8,15,9]
6. [2,3,4,5,6,7,8,9,15]
