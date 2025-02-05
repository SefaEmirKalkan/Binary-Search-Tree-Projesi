# Binary-Search-Tree-Projesi
**[7, 5, 1, 8, 3, 6, 0, 9, 4, 2]** dizisinin Binary-Search-Tree aşamalarını yazınız.

Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.
**1.Adım**
root 7'dir  en üste yazılır.
**2.Adım**
5 - **7** den küçüktür -> sola yazılır.
**3.Adım**
1 - **7,5**'den küçüktür 5'in sol altına yazılır.
**4.Adım**
8 - **7**'den büyüktür 7'nin sağına yazılır.
**5.Adım**
3 - **7,5**'den küçük **1**'den büyük olduğu için 1'in sağına yazılır.
**6.Adım**
6 - **7**'den küçük **5**'den büyük olduğu için 5'in sağına yazılır.
**7.Adım**
0 - **7,5,1**'den  küçük olduğu için 1'in sol altına yazılır.
**8.Adım**
9 - **7,8**'den büyük olduğu için 8'in sağ altına yazılır.
**9.Adım**
4 - **7,5**'den küçük **1**'den büyük olduğu için 1'in alt sağına yazılır.
**10.Adım**
2 - **7,5**'den küçük **1**'den büyük olduğu için 1'in sağ altına orda da **3**'den küçük olduğu için sol altına yazılır.
