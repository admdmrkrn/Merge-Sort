#Proje 2
* [16,21,11,8,12,22] -> Merge Sort

* Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
* Big-O gösterimini yazınız.
-------------------------------------------------------------------------------------------------------------
* [16,21,11,8,12,22] -> Merge Sort
* [16,21,11] -- [8,12,22]
* [16,21]--[11]-- [8,12]--[22]
* [16]  -   [21]  -  [11]   -    [8]   -  [12]  -   [22]  

* [16,21] [8,11]  [12,22] // Birleştirirken sıralama işlemi yapılır.
* [8,11,16,21]   [12,22]  // Artık diziler sıralı olduğu için daha az sayıda kıyaslama işlemi yapılacaktır. Dizinin en solundaki sayı ile yapılması yeterli olacaktır.
* [8,11,16,12,21,22]

----------------------------------------------------------------------------------------------------------------------
### Big-O Gösterimi
#### O(nlog(n))

#Proje 3
- [7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

- Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.

* Binary-Search-Tree aşamaları
* Root=5
* o(logN)
   
                       5
                1             7
           0       3       6       8
               2      4             9
