# selectionsortproje
## Soru 1: [22,27,16,2,18,6] -> Insertion Sort
### Aşama 1: Sayı öbeğinin en küçüğü bulunur ve en başa yazılır. Bu dizede bu sayı 2 dir.
[2,22,27,16,18,6]
### Aşama 2: 2. en küçün eleman bulunana kadar 2. eleman tüm sayılar ile kıyaslanır ve 2 nin sağına yazılır. Bu dizede bu sayı 6 dır.
[2,6,22,27,16,18]
### Aşama 3: 3. en küçün eleman bulunana kadar 3. eleman tüm sayılar ile kıyaslanır ve 6 nin sağına yazılır. Bu dizede bu sayı 16 dır.
[2,6,16,22,27,18]
### Aşama 4: 4. en küçün eleman bulunana kadar 4. eleman tüm sayılar ile kıyaslanır ve 16 nin sağına yazılır. Bu dizede bu sayı 18 dir. Kalan 2 eleman aralarında kıyaslanır ve işem biter.
[2,6,16,18,22,27]

## Big-O gösterimini yazınız.
Insortion Sort Big-O gösterimi: O(n²) dir.

##Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız
###Average case: Aradığımız sayının ortada olması.
###Worst case: Aradığımız sayının sonda olması.
###Best case: Aradığımız sayının dizinin en başında olması.

Doğru seçenek avarage casedir. Çünkü 18 ortada bulunmaktadır.

##Soru 2: [7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.

1. Adım: [3,7,5,8,2,9,4,15,6] 
2. Adım: [3,5,7,8,2,9,4,15,6]
3. Adım: [2,3,5,7,8,9,4,15,6]
4. Adım: [2,3,5,6,7,8,9,4,15]

