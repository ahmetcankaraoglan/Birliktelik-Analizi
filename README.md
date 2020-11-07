# Birliktelik Analizi

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




