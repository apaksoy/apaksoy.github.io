---
layout: post
title: "Bankaların gerçek özkaynak getirileri ve F/K çarpanları"
related_image: /assets/banka-ozkaynak-getiri/getiri-ilk.png
categories: hisse
---
Özkaynak getirisi[^1] şirketlerin, özellikle de bankaların, kaynaklarını ne kadar iyi kullandıklarını gösteren en önemli ölçülerden birisi. Türkiye'de enflasyonun hızla yükseldiği son iki yıl için kendi hesapladığım [enflasyon muhasebesi uygulanmış finansalları]((/hisse/2023/04/14/bankalar-enflasyon-muhasebesi.html)) kullandığım aşağıdaki çizgeye göre bankalar son iki yılı epey kötü geçirmiş.

<br/>
[![Borsa İstanbul’da işlem gören bankaların tarihi ve enflasyona muhasebesi uygulanmış 2022 net karları.](/assets/banka-ozkaynak-getiri/getiri-ilk.png){:width=800px"}](/assets/banka-ozkaynak-getiri/getiri-ilk.png)
<br/>

Yukarıdaki çizgeye göre hisseleri Borsa İstanbul'da işlem gören 12 bankanın ortanca yıllık özkaynak getirileri 2010-2020 yıllarında ortalama %14,6 olarak gerçekleşirken, son iki yılda ortalama eksi %1,7 olmuş. Son yıllardaki düşüşün büyük ölçüde nedeni enflasyonun son iki yıldır yüksek olması ve bankaların yüksek net parasal pozisyon taşıyor olmaları.

Ancak 2010-2020 ve 2021-2022 dönemlerinin getirileri karşılaştırılabilir değil. Çünkü Türkiye'de yıllık tüketici enflasyonunun 2010-2020 dönemi basit ortalaması %10,4'le o kadar düşük değil ve bankalar iş modelleri icabı bu dönemde de yüksek net parasal pozisyonlara sahiptiler.

Bu sorunu gidermek için akla gelen ilk yol yukarıda bahsettiğim yazımdaki modeli kullanarak bankaların 2010-2020 yılları mali tablolarına da enflasyon muhasebesi uygulamak ama bu fikri uygulamak müthiş zor olmasa da bu çalışma için planladığımdan epey daha fazla emek ve zaman gerektirir. Neyse ki kestirme bir yöntem var:

Bankaların mali tablolarına enflasyon muhasebesi uygulandığında asıl fark yaratan kalem net parasal pozisyon karları (zararları). Bunun kaynağı da enflasyon ve bankaların net parasal pozisyonları. Bu çalışmaya konu bankaların varlıklarının genellikle ancak %1-%2'lik kısmı parasal olmayan duran varlıklarda olduğu için bankaların net parasal pozisyonları kabaca özkaynaklarına eşit. 

Dolayısıyla bankaların 2020 öncesi yıllık net karlarından ilgili yıl özkaynakları kullanılarak hesaplanmış net parasal zararları nominal (tarihi) karlarından düşülerek kabaca reel net karları ve böylece reel özkaynak getirilerini gerçeğe yakın bir şekilde hesaplamak mümkün. 

Bu hesapları yapıp bir çizgeye döktüğüm zaman karşımıza çıkan durum şu:

Yukarıdaki çizgeye göre bu çalışmaya konu bankaların 2010-2020 dönemi ortanca yıllık karlarının ortalaması %3,7. Aynı bankaların önceden hesapladığımız 

### Dipnotlar

[^1]: Bir şirket için belli bir yıldaki özkaynak getirisini o yılın net karını ortalama özkaynağa bölerek buluyorum. Bunun matematiksel gösterimi de şöyle: <br/><br/>$${G}_T = \frac{K_T}{Z_T + Z_{T-1}} \times 2 \tag 1$$ <br/>ki bu formülde &nbsp;$${G}_T$$, $$K_T$$ ve $$Z_T$$, $$T$$ senesindeki, sırasıyla, özkaynak getirisi, net kar ve özkaynağı gösteriyor. Enflasyon muhasebesi uygulanmış mali tablolar için de bu formülün şu halini kullanıyorum:<br/><br/>$${G}_T = \frac{K_T}{Z_T + Z_{T-1}(1+E_{T})} \times 2 \tag 2$$<br/>ki bu formülde $$E_{T}$$, $$T$$ senesinde gerçekleşen enflasyonu gösteriyor.