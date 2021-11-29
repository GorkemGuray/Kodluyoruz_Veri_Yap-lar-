# Proje - 1

**Veri:**  [22,27,16,2,18,6]
**Yöntem:** Insertion Sort

1.  Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
2.  Big-O gösterimini yazınız.
3. Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.
4. Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.

[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

## Cevaplar
### 1. Cevap
Adım-1 ---> [16,22,27,2,18,6]
Adım-2 ---> [2,16,22,27,18,6]
Adım-3 ---> [2,16,18,22,27,6]
Adım-4 ---> [2,6,16,18,22,27]

### 2. Cevap
Insertion Sort olduğu için O(n^2)'dir.

### 3.Cevap
> Soru burada net değil arama algoritması mı soruyor? Arama algoritması soruyorsa hangisi? O yüzden bu soruyu Insertion Sort algoritmasının Time Complexity'si olarak cevaplayacağım.

*Average Case* : Dizinin yarısının sıralı olduğu durum. Bu durumda O(n) * O(n-n/2) olduğundan **O(n^2)**'dir.
*Worst Case* : Dizinin hiç sıralı olmadığı durum. O(n) * O(n-1) * .... * 1 bu durumda 1'den n'e kadar olan sayıların toplamı formülü devreye girer *(aslında average case'de aynı durum var)* O(n) * O(n+1/2) olduğundan **O(n^2)**'dir.
*Best Case* : Dizinin sıralı olduğu durum. Bu durumda bile diznin sıralı olduğunu anlayabilmek için diziyi 1 kez dolaşmak gerekir. Bu yüzden **O(n^2)'dir.

### 4. Cevap
Dizi sıralandıktan sonra 18 sayısı, dizinin ortalarına denk gelmektedir bu sebeple Average Case'e denk gelmektedir.

### Bonus
Adım-1 ---> [3,7,5,8,2,9,4,15,6]
Adım-2 ---> [3,5,7,8,2,9,4,15,6]
Adım-3 ---> [2,3,5,7,8,9,4,15,6]
Adım-4 ---> [2,3,4,5,7,8,9,15,6]
 