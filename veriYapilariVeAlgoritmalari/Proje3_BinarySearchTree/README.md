Proje 3

[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.

1. adım

Kök 7'dir.

     7

2. adım

5; 7'den küçüktür. Yani kökün sol tarafındadır.

     7
    /   
   5     

3. adım

1, 7 ve 5'ten küçüktür.

       7
      /   
     5     
    /      
   1        

4. adım

8; 7'den büyüktür. Yani kökün sağ tarafındadır.

        7
      /   \
     5     8
    /      
   1    

5. adım

3; 7 ve 5'ten küçük ama 1'den büyük.

        7
      /   \
     5     8
    /      
   1  
    \
     3

6. adım

6; 7'den küçük ama 5'ten büyüktür.

         7
       /   \
      5     8
     /  \    
    1    6
      \
       3

7. adım

0; 7, 5 ve 1'den küçüktür.

           7
         /   \
        5     8
       / \     
      1   6       
     /  \ 
    0    3

8. adım

9; 7 ve 8'den büyüktür.

           7
         /   \
        5     8
       / \     \
      1   6     9  
     /  \
    0    3

9. adım

4; 7 ve 5'ten küçük ama 3'ten büyüktür.

           7
         /   \
        5     8
       / \     \
      1   6     9  
     /  \
    0    3
          \
           4

10. Son adım

Ve son olarak 2; 7 ve 5'ten küçük ama 1'den büyük. Ayrıca 3'ten küçüktür.

           7
         /   \
        5     8
       / \     \
      1   6     9  
     /  \
    0    3
        /  \
       2   4
