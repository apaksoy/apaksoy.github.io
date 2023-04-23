---
layout: post
title: "Bankaların gerçek özkaynak getirileri ve F/K çarpanları"
related_image: /assets/banka-ozkaynak-getiri/getiri-ilk.png
categories: hisse
---
Özkaynak getirisi şirketlerin, özellikle de bankaların, kaynaklarını ne kadar iyi kullandıklarını gösteren belki de en önemli ölçü. Bu ölçü "[Bankaların 2022 ve 2021 mali tablolarına enflasyon muhasebesi uygulanması](/hisse/2023/04/14/bankalar-enflasyon-muhasebesi.html)" başlıklı yazımda yer alan TÜFE bazlı enflasyon muhasebesi rakamlarını da kullanarak 2010 yılından bu yana yıllık olarak hesaplandığında[^1] çıkan rakamlara dayanan aşağıdaki çizgeye göre bankalar son iki yılı epey kötü geçirmiş.

<br/>
[![Borsa İstanbul’da işlem gören bankaların tarihi ve enflasyona muhasebesi uygulanmış 2022 net karları.](/assets/banka-ozkaynak-getiri/getiri-ilk.png){:width=800px"}](/assets/banka-ozkaynak-getiri/getiri-ilk.png)
<br/>

Yukarıdaki çizgeye göre hisseleri Borsa İstanbul'da işlem gören 12 bankanın ortanca yıllık özkaynak getirileri 2010-2020 yıllarında ortalama %14,6 olarak gerçekleşirken, son iki yılda ortalama eksi %1,7 olarak gerçekleşmiş. 

Ama yukarıdaki çizgedeki verilerde şöyle bir sorun var: bankaların 2021 ve 2022 özkaynak getirileri reelken, yani enflasyon muhasebesinin uygulanmasıyla enflasyondan arındırılmışken, 2020 ve öncesi özkaynak getirileri nominal.

Bu sorunu gidermek için akla gelen ilk yol yukarıda bahsettiğim yazımdaki modeli kullanarak bankaların 2010-2020 yılları mali tablolarına da enflasyon muhasebesi uygulamak ama bu fikri uygulamak müthiş zor olmasa da bu çalışma için planladığımdan epey daha fazla emek ve zaman gerektirir. Neyse ki kestirme bir yöntem var:

Bankaların mali tablolarına enflasyon muhasebesi uygulandığında asıl fark yaratan kalem net parasal pozisyon karları (zararları). Bunun kaynağı da enflasyon ve bankaların net parasal pozisyonları. Bu çalışmaya konu bankaların varlıklarının genellikle ancak %1-%2'lik kısmı parasal olmayan duran varlıklarda olduğu için bankaların net parasal pozisyonları kabaca özkaynaklarına eşit. 

Dolayısıyla bankaların 2020 öncesi yıllık net karlarından ilgili yıl özkaynakları üzerinden hesaplanmış net parasal zararları düşülerek reel net karları ve böylece reel özkaynak getirilerini gerçeğe oldukça yakın bir şekilde hesaplamak mümkün. 

Bu hesapları yapıp bir çizgeye döktüğüm zaman karşımıza çıkan durum şu:

Yukarıdaki çizgeye göre bu çalışmaya konu bankaların 2010-2020 dönemi ortanca yıllık karlarının ortalaması %3,7. Aynı bankaların önceden hesapladığımız 

### Dipnotlar

[^1]: Özkaynak getirisi için en sık kullanılan formüle göre bir şirketin belli bir yıldaki özkaynak getirisi o yılın net karının ortalama özkaynağına bölünmesiyle bulunuyor. Bunu matematiksel olarak şöyle göstermek mümkün: <br/><br/>$${G}_T = \frac{K_T}{Z_T + Z_{T-1}} \times 2 \tag 1$$ <br/>ki bu formülde &nbsp;$${G}_T$$, $$K_T$$ ve $$Z_T$$, $$T$$ senesindeki, sırasıyla, özkaynak getirisi, net kar ve özkaynağı gösteriyor. Enflasyon muhasebesi doğrudan uygulanmış seneler için şu halini kullanıyorum:<br/><br/>$${G}_T = \frac{K_T}{Z_T + Z_{T-1}(1+E_{T})} \times 2 \tag 2$$<br/>ki bu formülde $$E_{T}$$, $$T$$ senesinde gerçekleşen enflasyonu gösteriyor.