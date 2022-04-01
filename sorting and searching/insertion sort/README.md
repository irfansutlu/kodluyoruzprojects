## [22,27,16,2,18,6] -> Insertion Sort

- Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.


    1. ***2*** 27 16 ***22*** 18 6
    2. 2 ***6*** 16 22 18 ***27***
    3. 2 6 16 ***18*** ***22*** 27
    4. **2 6 16 18 22 27**

----------
- Big-O gösterimini yazınız.

    n + n-1 +n-2 + ....+1 = n*(n-1)/2

    O(n) = n^2

------------
- Time Complexity: 

    Average case: Worst case ile best casein ortalamasının alınmasıdır. **O(n^2)**

    Worst case: Tam tersi verilmiş dizi, bu durumda dizinin her bir elemanı bir sonrakinden büyük olacaktır. **O(n^2)**

    Best case: Tam sıralı dizi, bu durum dizinin her bir elemanının küçükten büyüğe doğru sıralanmış halidir. **O(n)**

---------
- Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer?

    **Average Case**    
----------
## [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

1.  ***2*** 3 5 8 ***7*** 9 4 15 6
2.  2 3 ***4*** 8 7 9 ***5*** 15 6
3.  2 3 4 ***5*** 7 9 ***8*** 15 6
4.  2 3 4 5 ***6*** 9 8 15 ***7***  