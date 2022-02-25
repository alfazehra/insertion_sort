# insertion_sort
Veri Yapıları ve Algoritmaları Insertion Sort projesi
[22,27,16,2,18,6]--> Insertion Sort
Yukarıda verilen dizinin sort türüne göre aşamalarını yazmak için;

[22,27,16,2,18,6]
Verilenler içinde en küçük değer en başa gelir ve sıralama küçükten büyüğe geçene kadar yer değişikliği olur.
verilen içinde en küçük '2' bu en başta olan değer '22' ile yer değiştirir.
[2,27,16,22,18,6] düzenini alır.
Birinci kısımda en küçük değer yer alır ve bunda sonraki ikinci kısımda olması gereken en küçük değer kontrol edilir.
[2,27,16,22,18,6] '2' değerinden sonraki sayı sıralamada ki ikinci en küçük değer mi kontrolü yapılır ve değilse en küçük değer ile yer değiştirir bu şekilde sıralama yapılır.
'2' den sonra en küçük değer '6' bu değer ile '27' yer değiştirir.
[2,6,16,22,18,27] '2 ve 6' dan sonraki en küçük değer sıralaması yapılır.
'22' sayısı ile '18' yer değiştirmesi gerekiyor.Son olarak:
[2,6,16,18,22,27] şeklinde küçükten büyüğe göre sıralama gerçekleşir.


Big-O gösterimini yazınız.
**O(n^2)

*Time Complexity: Average Case: Aradığımız sayını ortada olması, WortCase Aradığımız sayının sonda olması, Best Case: Aradığımız sayının 18 sayısı hangi Case kapsamına girer?
** Aradığımız sayı ortada olmasından ötürü: Average Case

[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

Başlangıç [7,3,5,8,2,9,4,15,6]
1.Adım: '2 ve 7' yer değiştirir. [2,3,5,8,7,4,15,6]
2.Adım: '4 ve 5' yer değiştirir. [2,3,4,8,7,5,15,6]
3.Adım: '8 ve 5' yer değiştirir. [2,3,4,5,7,8,15,6]
4.Adım: '6 ve 7' yer değiştirir. [2,3,4,5,6,8,15,7]
********** İstenilen İlk 4 adım sonrası **********
5.Adım: '8 ve 7' yer değiştirir. [2,3,4,5,6,7,15,8]
6.Adım: '15 ve 8' yer değişitirir. [2,3,4,5,6,7,8,15]

Insertion Sort'a göre 6 adım da biter.
