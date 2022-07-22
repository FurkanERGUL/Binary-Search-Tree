# Binary-Search-Tree
Binary search tree projesinin çözümü.

[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.

1-Öncellikle diziyi sıralı bir hale getiriyoruz çünkü binary search tree de veri bu şekildeymiş gibi davranıyor.

2-Seriyi doğru bir şekilde ortalayıp dağıtarak (kökün sağında büyük solunda küçük olan olacak şekilde) diziyoruz.

# 1-)Sıralama:

[0,1,2,3,4,5,6,7,8,9]

# 2-) Ortalama:

           3
        /     \
       1       5
      / \     / \
     0   2   4   6
                  \
                   8
                  /  \
                 7    9
