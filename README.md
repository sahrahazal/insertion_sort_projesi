# Insertion Sort Projesi
### **Proje 1**
**[22,27,16,2,18,6]** => Insertion Sort
1. Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
2. Big-O gösterimini yazınız.
3. Time Complexity: 
    **Avarage case:** Aradığımız sayının ortada olması, 
    **Worst case:** Aradığımız sayının sonda olması, 
    **Best case:** Aradığımız sayının dizinin en başında olması.
4. Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.

### **Proje 1 Çözümü**

**1.** 
```
[22,27,16,2,18,6]
[2,27,16,22,18,6]
[2,6,16,22,18,27]
[2,6,16,18,22,27]
```
**2.**
```
O(n^2) => Insertin Sort algoritmasının Big-O Notation'ıdır.
```
**3.** & **4.**
```
[2,6,16,**18**,22,27] => 18 sayısı dizinin ortasında olduğu için Avarage Case'dir.
```

***

**[7,3,5,8,2,9,4,15,6]** dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.
```
[2,3,5,8,7,9,4,15,6]
[2,3,4,8,7,9,5,15,6]
[2,3,4,5,7,9,8,15,6]
[2,3,4,5,6,9,8,15,7]
```


https://www.patika.dev
