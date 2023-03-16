## Proje 1
#### [22,27,16,2,18,6] -> Insertion Sort

> Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

* Step 1 = [22,27,16,2,18,6]
* Step 2 = [2,22,27,16,18,6]
* Step 3 = [2,6,22,27,16,18]
* Step 4 = [2,6,16,22,27,18]
* Step 5 = [2,6,16,18,22,27]
 
> Big-O gösterimini yazınız.

Insertion Sort’un time complexity’si :

- Best Case : O(n)
- Worst Case : O(n²)
- Average Case : O(n²)

>  Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız  1. Average case: Aradığımız sayının ortada olması 2. Worst case: Aradığımız sayının sonda olması 3. Best case: Aradığımız sayının dizinin en başında olması. 
 
Average Case kapsamına girer.

> [7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.  

* Step 1 = [7,3,5,8,2,9,4,15,6]
* Step 2 = [2,3,5,8,7,9,4,15,6]
* Step 3 = [2,3,4,8,7,9,5,15,6]
* Step 4 = [2,3,4,5,7,9,8,15,6]
 
* Step 5 = [2,3,4,5,6,9,8,15,7]
* Step 6 = [2,3,4,5,6,7,8,15,9]
* Step 7 = [2,3,4,5,6,7,8,9,15]

---

## Proje 2
#### [16,21,11,8,12,22] -> Merge Sort

> Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.

* Step 1 = [16,21,11,8,12,22]
* Step 2 = [16,11,21,8,12,22]
* Step 2 = [11,16,21,8,12,22]
* Step 2 = [8,11,12,16,21,22]


>Big-O gösterimini yazınız.

O(nlogn)

---

### Proje 3

> [7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız. Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.

* Step 1 = ----------------7
* 
* Step 2 = ----------------7
* ----------------------5
* 
* Step 3 = ----------------7
* ----------------------5
* ------------------1
* 
* Step 4 = ----------------7
* ----------------------5-------8
* ------------------1
* 
* Step 5 = ----------------7
* ----------------------5-------8
* ------------------1
* --------------3
* 
* Step 6 = ----------------7
* ----------------------5-------8
* -------------------1----6
* ---------------------3
* 
* Step 7 = ----------------7
* ----------------------5-------8
* -------------------1----6
* -----------------0---3
* 
* Step 8 = ----------------7
* ----------------------5-------8
* -------------------1----6--------9
* -----------------0---3
* 
* Step 9 = ----------------7
* ----------------------5-------8
* -------------------1----6--------9
* -----------------0---3
* ------------------------4
* 
* Step 10 = ----------------7
* ----------------------5-------8
* -------------------1----6--------9
* -----------------0---3
* -------------------2---4


