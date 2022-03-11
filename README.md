# Kodluyoruz Insertion Sort Projesi

## 1.Örnek
[22,27,16,2,18,6] -> Insertion Sort

1.Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
```
1- [22,27|16,2,18,6]  
2- [16,22,27|2,18,6]  
3- [2,16,22,27|18,6]  
4- [2,16,18,22,27|6]  
5- [2,6,16,18,22,27]
```

2.Big-O gösterimini yazınız.
```
O(n^2)
```

3.Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.
```
Average case: O(n^2)  
Worst case: O(n^2)  
Best case: O(n)
```

4.Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.
```
4.adımda gireceği için Average case kapsamına girer. 
```

## 2.Örnek
[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.
```
1- [3,7|5,8,2,9,4,15,6]  
2- [3,5,7|8,2,9,4,15,6]  
3- [3,5,7,8|2,9,4,15,6]  
4- [2,3,5,7,8|9,4,15,6]
```