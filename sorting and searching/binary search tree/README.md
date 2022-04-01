## [7,5,1,8,3,6,0,9,4,2] dizisinin Binary-Search-Tree aşamalarını yazınız.

```
                            5
                          /   \
                         3      7
                        / \    / \
                       1   4  6   8
                      / \          \
                     0   2          9
```
1.  5 kök (root) olarak atadık

2.  Sıradaki sayımız 3. Eklemek için 5'e sorduk (büyük mü küçük mü diye?) Küçük olduğu için sol tarafa ekledik

3.  Sıradaki sayılarımız 1 ve 4. Eklemek için 5'e aynı şekilde soruyoruz. Sayılar küçük olduğu için sola gideriz ve önümüze 3 çıkar. 3'e aynı soru sorulur. 1 sayısı 3'ten küçük olduğu için sol tarafa eklenir. 4 sayısı 3'ten büyük olduğu için sağ tarafa eklenir.

4.  Sıradaki sayılarımız 0 ve 2. Eklemek için 5'e aynı şekilde soruyoruz. Sayılar küçük olduğu için sola gideriz ve önümüze 3 çıkar. 3'e aynı soru sorulur. Sayılar küçük olduğu için sola gideriz ve önümüze 1 çıkar. 0 sayısı 1'den küçük olduğu için sol tarafa eklenir. 2 sayısı 1'den büyük olduğu için sağ tarafa eklenir.

5. Sıradaki sayımız 7. Eklemek için 5'e sorduk (büyük mü küçük mü diye?) Büyük olduğu için sağ tarafa ekledik.

6. Sıradaki sayılarımız 6 ve 8. Eklemek için 5'e aynı şekilde soruyoruz. Sayılar büyük olduğu için sağa gideriz ve önümüze 7 çıkar. 7'ye aynı soru sorulur. 6 sayısı 7'den küçük olduğu için sol tarafa eklenir. 8 sayısı 7'den büyük olduğu için sağ tarafa eklenir.

7. Sıradaki sayımız 9. Eklemek için 5'e aynı şekilde soruyoruz. Sayı büyük olduğu için sağa gideriz ve önümüze 7 çıkar. 7'ye aynı soru sorulur. Sayı büyük olduğu için sağa gideriz ve önümüze 8 çıkar. 9 sayısı 8'den büyük olduğu için sağ tarafa eklenir.