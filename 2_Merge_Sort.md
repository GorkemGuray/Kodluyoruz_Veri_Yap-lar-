# Proje - 2

**Veri:**  [16,21,11,8,12,22]    
**Yöntem:** Merge Sort

1.  Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
2.  Big-O gösterimini yazınız.



## Cevaplar
### 1. Cevap
Adım-1 ---> [16,21,11] - [8,12,22]   
Adım-2 ---> [16,21] , [11] - [8,12] , [22]  
Adım-3 ---> [16] , [21] , [11] - [8] , [12] , [22]   
Adım-4 ---> [16,21] , [11] - [8,12] , [22]
Adım-5 ---> [11,16,21]  - [8,12,22]
Adım-6 ---> [8,11,12,16,21,22]

### 2. Cevap
Her defasında taradığım veri sayısı yarıya düştüğünden 2^x = n'dir bu durumda O(logN)'dir. Fakat bu işşlemi genelde düşünürsek O(n) kez de bu işlem yapılmalıdır. Bu durumda **O(n*log*N)**'dir.


 