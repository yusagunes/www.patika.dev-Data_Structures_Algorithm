# Selection Sort Projesi  
[22,27,16,2,18,6] -> Insertion Sort

Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

Big-O gösterimini yazınız.

Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız

Average case: Aradığımız sayının ortada olması
Worst case: Aradığımız sayının sonda olması
Best case: Aradığımız sayının dizinin en başında olması.
.



[7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.

## 1 İnserion sort türüne göre aşamaları yazınız. 
### 1. Aşama
- Dizinin ilk elemanı sağındaki ikinci elemanla kıyaslanır. 22<27 olduğu için sıralama aynı kalır.
1. [22,27,16,2,18,6]
### 2. Aşama 
- İkinci eleman ve üçüncü eleman kıyaslanır. 27<16 olduğu için 16 ile 27 yer değiştirir.
  [22,16,27,2,18,6]
- Daha sonrasında 16 ile ilk eleman kıyaslanır, 16<22 olduğu için bu iki eleman da yer değiştirir ve sıralama şu şekilde olur:
   [16,22,27,2,18,6]
### 3. Aşama
-Üçüncü eleman ile dördüncü eleman kıyaslanır. 27>2 olduğu için elemanlar yer değiştirir.
   [16,22,2,27,18,6]
- ikinci eleman olan 22 ile kıyaslanır. 2<22 olduğu için yer değiştirirler.
   [16,2,22,27,18,6]
- 2, ilk eleman olan 16 ile kıyaslanır. 2<16 olduğu için sıralama şu şekilde olur:
    [2,16,22,27,18,6]
### 4. Aşama 
- Üçüncü eleman ile dördüncü eleman kıyaslanır. 27>2 olduğu için elemanlar yer değiştirir.
   [16,22,2,27,18,6]
- 18, üçüncü eleman ile kıyaslanır. 18<22 olduğu için elemanlar yer değiştirir.
   [2,16,18,22,27,6]
- 18, ikinci eleman ile kıyaslanır. Halihazırda 16<18 olduğu için yer değiştirmezler ve sıralama şu şekilde olur:
   [2,16,18,22,27,6]
 ### 5. Aşama
 - Beşinci eleman ile altıncı eleman kıyaslanır. 27>6 olduğu için elemanlar yer değiştirir.
   [2,16,18,22,6,27]
 - 6, dördüncü eleman ile kıyaslanır. 6<22 olduğu için elemanlar yer değiştirir.
   [2,16,18,6,22,27]
 - 6, üçüncü eleman ile kıyaslanır. 6<18 olduğu için elemanlar yer değiştirir .
    [2,16,6,18,22,27]
 - 6, ikinci eleman ile kıyaslanır. 6<16 olduğu için elemanlar yer değiştirir.
    [2,6,16,18,22,27]
 - 6, birinci eleman ile kıyaslanır. 6>2 olduğu için elemanlar yer değiştirmez. 6 dizideki son eleman olduğu için sıralama tamamlanmıştır:
    [2,6,16,18,22,27]
 ##  Big-O Gösterimi

Worst Case: O(n^2)

Average Case: O(n^2)

Best Case: O(n)

## Time Complexity
- Average case: Aradığımız sayının ortada olması

- Worst case: Aradığımız sayının sonda olması

- Best case: Aradığımız sayının dizinin en başında olması.

'[2,6,16,18,22,27] dizi sıralandığında 18 sayısı ortada kaldığı için Avarage Case olur.'


## [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.
1. [3,7,5,8,2,9,4,15,6]
2. [3,5,7,8,2,9,4,15,6]
3. [3,5,7,8,2,9,4,15,6]
4. [2,3,5,7,8,9,4,15,6]

-----------------------------------------------------------------------
# [www.patika.dev ] ekibine teşekkürler.
