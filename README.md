# Algorithm
# Proje 1

[22,27,16,2,18,6] -> Insertion Sort
Yukarı verilen dizinin sort türüne göre aşamalarını yazınız. Big-O gösterimini yazınız.

1. adım: [22,27,16,2,18,6]
2. adım: [22,27,16,2,18,6]
3. adım: [22,16,27,2,18,6] -> [16,22,27,2,18,6]
4. adım: [16,22,2,27,18,6] -> [16,2,22,27,18,6] -> [2,16,22,27,18,6]
5. adım: [2,16,22,18,27,6] -> [2,16,18,22,27,6]
6. adım: [2,16,18,22,6,27] -> [2,16,18,6,22,27] -> [2,16,6,18,22,27] -> [2,6,16,18,22,27]

Time Complexity: 
Insertion Sort'un Big-O gösterimi: O(n^2) (Quadratic time complexity)

Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız.
Average case: Aradığımız sayının ortada olması.
Worst case: Aradığımız sayının sonda olması.
Best case: Aradığımız sayının dizinin en başında olması.
Cevap: Average case kapsamına giriyor.

[7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.
1. adım: [2,3,5,8,7,9,4,15,6]
2. adım: [2,3,4,8,7,9,5,15,6]
3. adım: [2,3,4,5,7,9,8,15,6]
4. adım: [2,3,4,5,6,9,8,15,7]
5. adım: [2,3,4,5,6,7,8,15,9]
6. adım: [2,3,4,5,6,7,8,9,15]

# Proje 2
[16,21,11,8,12,22] -> Merge Sort

Yukarıdaki dizinin sort türüne göre aşamalarını yazınız. Big-O gösterimini yazınız. 
Big-O: O(nlogn)

1.               [16,21,11]                             [8,12,22]
                /           \                         /           \
2.          [16,21]          [11]                  [8,12]          [22]
           /        \             \               /      \            \
3.      [16]         [21]          [11]        [8]        [12]         [22]   
            \       /              /             \         /            /
4.           [16,21]           [11]                 [8,12]           [22]
                 \            /                        \           /
5.                 [11,16,21]                            [8,12,22]
                                  
6.                                [8,11,12,16,21,22]





# Proje 3
[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.


                             7
                           /   \ 
                          5      8
                        /  \       \
                       1    6       9
                     /   \           
                    0     3          
                        /   \      
                       2     4    

1. Root 7. Root'un solunda 5, sağında 8
2. Sol tarafa geçtik. 1<5 sola, 6>5 sağa
3. 0<1 sola, 3>1 sağa
4. 2<3 sola, 4>3 sağa
5. 9>8 olduğu için sağ tarafa eklenir.


