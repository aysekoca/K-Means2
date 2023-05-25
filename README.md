# K-Means2
# K-MEANS ALGORİTMASI
# PROJENİN AMACI VE KULLANIMI
 K-means kümeleme algoritmasının bir örneğini içerir. 
 
 Amacı: Veri setindeki nesneleri belirli kümelere gruplamaktır. Örneğin, Türkiye'deki 10 ilin göç verilerini kullanarak kümeleme yapabiliriz.
 
K-means algoritması veri noktalarını belirli sayıda küme (K) içerisine gruplandıran bir makine öğrenimi ve veri madenciliği yöntemidir. Algoritma, her bir veri noktasını en yakın olan merkeze atanarak kümeleme işlemini gerçekleştirir. Ardından, küme merkezleri yeniden hesaplanır ve bu adımlar iteratif olarak tekrarlanır. Sonuç olarak, her veri noktası bir kümeye atanır ve küme merkezleri, kümelerin temsilcisi olarak kullanılır.

Bu kod örneğinde, Adana, Ankara, İstanbul, Bursa, Kocaeli, Sakarya, Mersin, İzmir, Antalya ve Van illerinin göç verilerini kullanarak bu illeri 3 küme içerisinde gruplandırıyoruz. Her bir ilin göç verisi, ilgili küme merkezi ile olan uzaklık ölçüsüne dayanarak bir kümeye atanır. Ardından, küme merkezleri güncellenir ve konverjans kontrolü yapılır. İterasyonlar devam ettikçe, kümeleme işlemi iyileşir ve sonuçları elde ederiz.

