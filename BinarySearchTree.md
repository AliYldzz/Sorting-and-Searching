# Proje 3
[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

---
Root 7 dir. Sağında 8, solunda 5 bulunur. 8 in solunda 8 den büyük olduğu için 9 bulunur. 5 in solunda ise 1, sağında ise 6 bulunur. 1 in sağıda 3, solunda ise 0 bulunur. 3 ün sağında ise 4, solunda ise 2 bulunur.

             [7,5,1,8,3,6,0,9,4,2]
                
                     [7]
                    /   \
                   /     \
                  /       \
                [5]       [8]
              /     \        \
             /       \        \
            /         \        \
            [1]       [6]      [9]
           /   \
          /     \
         /       \ 
        [0]     [3]
               /   \
              /     \
             /       \
            [2]       [4]