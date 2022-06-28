# datastructures-insertionsort
[22,27,16,2,18,6] -> Insertion Sort

1.)Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

2.)Big-O gösterimini yazınız.

3.)Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.

4.)Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.



[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.


1.) Baslangic-> [22,27,16,2,18,6] 
    1.aşama->   [2,27,16,22,18,6]
    2.aşama->   [2,6,16,22,18,27]
    3.aşama->   [2,6,16,22,18,27]
    4.aşama->   [2,6,16,18,22,27]

2.) Big O n(n+1)/2 ->Big O(n^2)

3.)Time Complexity: Average case: Aradığımız sayının ortada olması, Sıralama yapılacak dizinin orta karışıklıkta olması. Big O(n^2)
Worst case: Aradığımız sayının sonda olması, Sıralama yapılacak dizinin karışık olması. Big O(n^2)
Best case: Aradığımız sayının dizinin en başında olması. Ya da elimize sıralı liste verilmesi. Big O(n)

4.)18 sayısı 4. aşamada düzenlendi. n-> n-1-> n-2-> n-3 . n-3 duruma bakıldı.


1.) Baslangic -> [7,3,5,8,2,9,4,15,6]
    1. aşama  -> [2,3,5,8,7,9,4,15,6]
    2. aşama  -> [2,3,5,8,7,9,4,15,6]
    3. aşama  -> [2,3,4,8,7,9,5,15,6]
    4. aşama  -> [2,3,4,5,7,9,8,15,6]
    5. aşama  -> [2,3,4,5,6,9,8,15,7]
    6. aşama  -> [2,3,4,5,6,7,8,15,9]
    7. aşama  -> [2,3,4,5,6,7,8,15,9]
    8. aşama  -> [2,3,4,5,6,7,8,9,15]

2.) Big O n(n+1)/2 -> Big O(n^2)

3.)Time Complexity: Average case: Aradığımız sayının ortada olması, Sıralama yapılacak dizinin orta karışıklıkta olması. Big O(n^2)
Worst case: Aradığımız sayının sonda olması, Sıralama yapılacak dizinin karışık olması. Big O(n^2)
Best case: Aradığımız sayının dizinin en başında olması. Ya da elimize sıralı liste verilmesi. Big O(n)

4.)18 sayısı bu dizide yok.
