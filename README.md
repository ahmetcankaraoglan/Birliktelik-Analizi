# Birliktelik Analizi

![Test Image 1](https://zeynepozturkk.files.wordpress.com/2019/03/market-basket-analysis.jpeg)

**Birliktelik Kuralları Nedir?**

Veri içerisindeki pattern'leri (ilişkileri, yapıları) bulmak için kullanılan kural tabanlı bir makine öğrenmesi tekniğidir. Birliktelik analizi uygulamaları veri biliminde en çok karşımıza çıkan uygulamalardandır. Tavsiye sistemleri olarak da denk gelmiş olacaktır. Bu uygulamalar karşınıza şu şekillerde gelmiş olabilir "o ürünü alan bu ürünü de aldı" ya da "o ilana bakanlar bu ilanlara da baktı" ya da "senin için çalma listesi oluşturduk" ya da "sıradaki video için önerilen video" gibi. Bu senaryolar e-ticaret veri bilimi veri madenciliği çalışmaları kapsamında en sık karşımıza çıkacak olan senaryolar. Türkiye'deki ve dünyadaki büyük e-ticaret şirketleri, spotify, amazon, netflix gibi biraz daha yakından bilebileceğimiz birçok platform tavsiye sistemlerini kullanmaktadır.

**Peki özetle ne yapmaktadır bu birliktelik analizleri?**

Apriori Algoritması bu alanda en çok kullanılan yöntemdir. Birliktelik kuralı analizi bazı metrikler incelenerek gerçekleştirilir:

* **Destek (Support)**
  * Support(X, Y) = Freq(X,Y)/N
    X: ürün Y: ürün N: toplam alışveriş
* **Güven (Confidence)**
  * Confidence(X, Y) = Freq(X,Y) / Freq(X)
* **Lift**
  * Lift = Support (X, Y) / ( Support(X) * Support(Y) )
  
bu metriklere bakılarak yorumlar ve aksiyon kararları alınmaktadır. 

**Support:** Örneğin X ve Y ürünleri olsun. Bu ikisinin birlikte görülme olasılığını ifade etmektedir.
**Confidence:** Örneğin X ve Y ürünleri olsun. X'i alanların % şu kadarı Y'yide alacaklar. Bu bize confidence değerini verecektir.
**Lift:** Bir ürünün alınması diğer ürünün alınmasını % kaç arttırmaktadır. Bizlere bu bilgiyi vermektedir. 






