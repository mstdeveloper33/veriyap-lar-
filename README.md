# veriyap-lar-
Insertion Sort Aşamaları
Dizi: [22, 27, 16, 2, 18, 6]

Insertion Sort'un çalışma mantığı, diziyi sıralamak için her bir elemanı birer birer yerleştirmektir. İşlemleri adım adım takip edelim:

İlk Eleman (22): Dizi zaten tek elemanlı olduğu için sıralıdır.

[22]
İkinci Eleman (27): 27, 22'den büyük olduğu için yerini korur.

[22, 27]
Üçüncü Eleman (16): 16, 27'den küçük olduğu için 27'nin önüne geçer ve 22'den de küçük olduğu için en başa geçer.

[16, 22, 27]
Dördüncü Eleman (2): 2, 16'dan küçük olduğu için en başa geçer.

[2, 16, 22, 27]
Beşinci Eleman (18): 18, 27'den küçük ve 22'den büyük olduğu için 22 ve 27 arasına yerleşir.

[2, 16, 18, 22, 27]
Altıncı Eleman (6): 6, 16'dan küçük olduğu için 16'nın önüne geçer.

[2, 6, 16, 18, 22, 27]
Big-O Gösterimi
Insertion Sort'un en kötü durum (worst case) zaman karmaşıklığı 
𝑂
(
𝑛
2
)
O(n 
2
 ) olarak bilinir. Çünkü her eleman için, öncesindeki tüm elemanları karşılaştırmak gerekebilir.

Time Complexity: 18 Sayısı İçin Durum Analizi
Dizi sıralandıktan sonra [2, 6, 16, 18, 22, 27] şeklinde olur. 18 sayısı üçüncü sırada (ortada) yer aldığı için:

Average case: Aradığımız sayının ortada olmasıdır.
Selection Sort Adımları
Dizi: [7, 3, 5, 8, 2, 9, 4, 15, 6]

Selection Sort, her adımda en küçük elemanı seçip başa getirerek çalışır. İlk dört adımı takip edelim:

İlk Adım: En küçük eleman 2, 7 ile yer değiştirir.

[2, 3, 5, 8, 7, 9, 4, 15, 6]
İkinci Adım: Kalan dizideki en küçük eleman 3, yerinde kalır.

[2, 3, 5, 8, 7, 9, 4, 15, 6]
Üçüncü Adım: Kalan dizideki en küçük eleman 4, 5 ile yer değiştirir.

[2, 3, 4, 8, 7, 9, 5, 15, 6]
Dördüncü Adım: Kalan dizideki en küçük eleman 5, 8 ile yer değiştirir.

[2, 3, 4, 5, 7, 9, 8, 15, 6]
Bu şekilde Selection Sort diziyi adım adım sıralar.
