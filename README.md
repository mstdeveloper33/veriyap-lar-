# veriyap-lar-

proje 1


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



proje 2



Merge Sort, diziyi sürekli olarak ikiye bölüp daha sonra bu bölünen parçaları sıralı bir şekilde birleştirerek çalışır. İşlemleri adım adım inceleyelim:

Dizi: [16, 21, 11, 8, 12, 22]

Bölme (Divide) Aşaması:
İlk bölme: [16, 21, 11] ve [8, 12, 22]
İkinci bölme: [16] [21, 11] ve [8] [12, 22]
Üçüncü bölme: [16] [21] [11] ve [8] [12] [22]
Birleştirme (Conquer) ve Sıralama (Sort) Aşaması:
İlk birleştirme: [21] ve [11] birleştirilir ve [11, 21] olur.
[16] ve [11, 21] birleştirilir ve [11, 16, 21] olur.
İkinci birleştirme: [12] ve [22] birleştirilir ve [12, 22] olur.
[8] ve [12, 22] birleştirilir ve [8, 12, 22] olur.
Son birleştirme: [11, 16, 21] ve [8, 12, 22] birleştirilir ve sıralı dizi elde edilir.
Sonuç:

[11, 16, 21] ve [8, 12, 22] birleştirilir:
İlk olarak, 8 ve 11 karşılaştırılır. 8 daha küçük olduğu için sonuç dizisine eklenir: [8]
Sonra, 12 ve 11 karşılaştırılır. 11 daha küçük olduğu için eklenir: [8, 11]
Daha sonra, 12 ve 16 karşılaştırılır. 12 daha küçük olduğu için eklenir: [8, 11, 12]
16 ve 21 karşılaştırılır. 16 eklenir: [8, 11, 12, 16]
21 ve 22 karşılaştırılır. 21 eklenir: [8, 11, 12, 16, 21]
Son olarak, 22 eklenir: [8, 11, 12, 16, 21, 22]
Aşamaların tamamlanmış haliyle sıralı dizi:

[8, 11, 12, 16, 21, 22]
Big-O Gösterimi
Merge Sort'un zaman karmaşıklığı, her zaman 
𝑂
(
𝑛
log
⁡
𝑛
)
O(nlogn) olarak bilinir. Çünkü her bölme işleminde dizi ikiye ayrılır ve her birleştirme işleminde dizinin tamamı birleştirilir.

Özetle:

Merge Sort aşamaları, diziyi bölerek ve daha sonra birleştirerek nasıl sıraladığını gösterir.
Merge Sort'un Big-O zaman karmaşıklığı 
𝑂
(
𝑛
log
⁡
𝑛
)
O(nlogn) olarak ifade edilir.
