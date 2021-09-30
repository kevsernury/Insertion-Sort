# Insertion sort projesi

### [22, 27, 16, 2, 18, 6]
1. Yukarıda verilen dizinin Insertion sort türüne göre aşamalarını yazınız.
2. Big-O gösterimini yazınız.
3. Time Complexity: 
   - Average case: Aradığımız sayının ortada olması,
   - Worst case: Aradığımız sayın sonda olması,
   - Best case: Aradığımız sayıın en başta olması.
4. Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? 

### [7, 3, 5, 8, 2, 9, 4, 15, 6] dizisinin Insertion sort'a göre ilk 4 adımını yazınız.

1. - [22, 27, 16, 2, 18, 6]
   - [(22, 27), 16, 2, 18, 6]
   - [(16, 22, 27), 2, 18, 6]
   - [(2, 16, 22, 27), 18, 6]
   - [(2, 16, 18, 22, 27), 6]
   - [(2, 6, 16, 18, 22, 27)]
   
2. O(n^2)

3. Time Complexity: 
   - Average case: n/2 
   - Worst case:   n
   - Best case:    1

4. Average case


### [7, 3, 5, 8, 2, 9, 4, 15, 6]
- [7, 3, 5, 8, 2, 9, 4, 15, 6]
- [(7), 3, 5, 8, 2, 9, 4, 15, 6]
- [(3, 7), 5, 8, 2, 9, 4, 15, 6]
- [(3, 5, 7), 8, 2, 9, 4, 15, 6]
- [(3, 5, 7, 8), 2, 9, 4, 15, 6]
