# Binary Search Tree Projesi (Mehmet EC)

# Soru 
[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.

# Sorunun Cevabı -- )

# 1. Root 6'dır o yüzden ağacın başına yazılır.
                 6

# 2. 7, 6'dan büyük olduğu için sağ tarafa yazılır.
                 6
                     7

# 3. 5, 6'dan küçük olduğu için sol tarafa yazılır.
                 6
            5         7

# 4. 1, 5'den küçük olduğu için sol tarafa yazılır.
                6
            5         7
          1

# 5. 8, 7'den büyük olduğu için sağ tarafa yazılır.
                6
            5         7
          1              8

# 6. 3, 1'den büyük olduğu için sağ tarafa yazılır.
                6
            5         7
          1              8
             3

# 7. 0, 3'den küçük olduğu için sol tarafa yazılır.
                6
             5       7
          1             8

            3          
          0   

# 8. 9, 8'den büyük olduğu için sağ tarafa yazılır.
                6
             5       7
          1             8
            3              9
          0   

# 9. 4, 0'dan büyük olduğu için sağ tarafa yazılır.
                6
             5       7
          1             8
            3              9
          0   
             4

# 10. 2, 4'den küçük olduğu için sol tarafa yazılır.
                6
             5        7
           1             8
             3              9
           0   
              4
            2


https://app.patika.dev/courses/veri-yapilari-ve-algoritmalar/binary-search-tree-proje