# Marge Sort Projesi Emir Kalkan

### [16,21,11,8,12,22] -> Merge Sort
### 1. Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
### 2. Big-O gösterimini yazınız.

---

## Cevaplar

1. Marge sort türüne göre aşamaları

                                    16,21,11 - 8,12,22
                                16 - 21,11          8-12,22
                            16-21-11                     8-12-22
                            11,16,21                     8,12,22
                            

                                [ 8 , 11 , 12 , 16 , 21 , 22 ]

2. Big-O Gösterimi
        
        16 - 21,11
        11 , 16 , 21 

        2^x = n
        logn
        = O(nlogn)


