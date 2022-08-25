# merge-sort

## PROJE 2
[16,21,11,8,12,22] -> Merge Sort<br>

Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.<br>
Big-O gösterimini yazınız.<br>

## ÇÖZÜM
[16,21,11,8,12,22] > [16,21,11] ve [8,12,22] olarak bölünür.<br>
[16,21,11] ise [16,21] ve [11] olarak bölünür. [8,12,22] ise [8,12] ve [22] olarak bölünür.<br>
[16,21] > [16] ve [21]. [11]<br>
[8,12] > [8] ve [12]. [22]<br>
ikiye bölerek yaptığımız bu bölümlerden sonra bu sayıları büyüklük küçüklük olma durumlarına göre birleştireceğiz.<br>
[16,21] ve [11]. Bir diğeri [8,12] ve [22]. <br>
Şimdi ise bu iki verileri büyüklük durumuna göre birleştireceğiz. [11,16,21] ve [8,12,22] olarak birleştirdim.<br>
ilk sayılara bakıyorum. 8 11den daha küçük olduğu için ondan başlıyorum. Ve devamında diğer verilerin de büyüklük küçüğüne göre birleştirme işlemini tamamlıyorum.<br>
Sonuç : [8,11,12,16,21,22]<br>
<br>
big o gösterimi: O[nlogn] dir.

                   
