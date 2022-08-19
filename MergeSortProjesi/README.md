Patika.dev platformunda verilen eğitmlerden "Veri Yapıları ve Algoritmalar" adlı ders bitiminde talep edilen soruların cevapları aşağıdadır.

Kaynak: https://app.patika.dev/courses/veri-yapilari-ve-algoritmalar

Sayfam: https://app.patika.dev/osmanesad


Sorular:

[16,21,11,8,12,22] -> Merge Sort

1- Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.

2- Big-O gösterimini yazınız.

Cevaplar:

1- [16,21,11] - [8,12,22]<br>
   [16] - [21,11] -- [8] - [12,22]<br>
   [16] - [21] - [11] --- [8] - [12] - [22]
   [11,16,21] ---- [8,12,22]<br>
   [8,11,12,16,21,22]

2- O(nlogn)