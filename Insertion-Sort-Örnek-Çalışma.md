# Insertion Sort Proje

### Dizi [ 22, 27, 16, 2, 18, 6 ]

## *Yukarıda verilen dizinin insertion sort'a göre aşamalarını yazınız.*

* [ **22**, 27, 16, **2**, 18, 6 ] 
* [ <span style="color:red">2</span>, **27**, 16, 22, 18, **6** ]
* [ <span style="color:red">2</span>, <span style="color:red">6</span>, **16**, 22, 18, 27 ]
* [ <span style="color:red">2</span>, <span style="color:red">6</span>, <span style="color:red">16</span>, **22**, **18**, 27 ]
* [ <span style="color:red">2</span>, <span style="color:red">6</span>, <span style="color:red">16</span>, <span style="color:red">18</span>, 22, 27 ]


## *Yukarıda verilen diziye ait Big-O gösterimini yazınız.*

Diziyi **n** elemanlı olarak ele alalım. Bu durumda en kötü durumda en küçük elemanı saptaya bilmek için ilk aşamada **n** tane arama yapmam gerekir. Her bir adımda bu 1 azalarak 1'e ulaşana kadar devam edecektir.Yani n, (n-1), (n-2), ... , 1  bu durumda 1'den n'e kadar olan sayıların toplamında kullandığımız formül n(n+1)/2 den faydalana biliriz. Bu durumda n^2+n/2 ye ulaşırız. Burada bizim artış hızımızı n^2 belirler bu yüzden O(n^2) olarak hesaplanır.

## *Yukarıda verilen dizinin Time Complexity: Average Case, Worst Case ve Best Case seneryolarını inceleyiniz.*

* Average Case: Bu tabloda Worst Case ve Average Case eşittir.

* Worst Case: n(n+1)/2 = n^2+n/2'den O(n^2) olarak bulunur açıklaması bir üstteki soruda zaten yapıldı.
O(6^2)=36

* Best Case: En iyi durumda bu dizi zaten sıralı olarak verilmiş olabilir yani her eleman yerli yerindedir bu durumda O(n)'dir.
O(6)=6

## *Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer yazınız.*

Sıralı dizide 18, 4. elemandır dizide 6 eleman bulunduğu için 18 Average Case kapsamına girmektedir.

### Dizi [ 7, 3, 5, 8, 2, 9, 4, 15, 6 ]

### *Yukarıdaki dizinin insertion sort algoritmasına göre ilk 4 adımını yazınız.*

* [ **7**, 3, 5, 8, **2**, 9, 4, 15, 6 ]
* [ <span style="color:red">2</span>, **3**, 5, 8, 7, 9, 4, 15, 6 ]
* [ <span style="color:red">2</span>, <span style="color:red">3</span>, **5**, 8, 7, 9, **4**, 15, 6 ]
* [ <span style="color:red">2</span>, <span style="color:red">3</span>, <span style="color:red">4</span>, **8**, 7, 9, **5**, 15, 6 ]
* [ <span style="color:red">2</span>, <span style="color:red">3</span>, <span style="color:red">4</span>, <span style="color:red">5</span>, 7, 9, 8, 15, 6 ]

### Patika dev'de bana ulaşmak için
[Buraya tıklayın](https://app.patika.dev/nes)


