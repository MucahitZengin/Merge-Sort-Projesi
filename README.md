Merge-Sort-Projesi
====================
[16,21,11,8,12,22] -> Merge Sort

## Aşamalar
1. [16, 21, 11]&emsp;&emsp;&emsp;[8, 12, 22]
2. [16, 21]&emsp;[11]&emsp;&emsp;[8, 12]&emsp;[22]
3. [16][21]&emsp;[11]&emsp;&emsp;[8][12]&emsp;[22] 

4. [16] [21]
5. **[16, 21]**
6. [16] [11]
7. **[11, 16, 21]**

8. [8] [12]
9. **[8, 12]**
10. [8, 22]
11. **[8]**
12. [12, 22]
13. **[8, 12, 22]**

14. **[11, 16, 21]** **[8, 12, 22]**

16. [11] [8]
17. **[8]**
18. [11, 12]
19. **[8,11]**
20. [16, 12]
21. **[8, 11, 12]**
22. [16, 22]
23. **[8, 11, 12, 16]**
24. [21, 22]
25. **[8, 11, 12, 16, 21]**
26. **[8, 11, 12, 16, 21, 22]**

## Big-O
Her basamakta n-1 karşılaştırma yapılır. O(n)

Dizi her seferinde ikiye bölündüğünden x'inci seviyede 2<sup>x</sup>=n eleman olur. Burdan x=log(n) bulunur. O(logn)
> Time complexity: O(nlogn)
