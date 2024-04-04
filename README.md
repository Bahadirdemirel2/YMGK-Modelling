# YMGK-Modelling
Yazılım Mühendisliği Gündüz A grubu Modelleme çalışması 200541011-Bahadır Demirel

## Kuromato-Sivashinsky Denklemi SWOT Analizi Ve Fizibilite Raporu

Kuramoto-Sivashinsky denklemi, dördüncü dereceden nonlineer bir kısmi diferansiyel denklemidir ve düzensizliklerin ve karmaşanın oluştuğu birçok fiziksel sistemde modelleme amacıyla kullanılır. Özellikle, akışkanlar dinamiğindeki turbülansın incelenmesinde kullanılır.

Kuramoto-Sivashinsky denklemi genellikle aşağıdaki formda ifade edilir:

![image](https://github.com/Bahadirdemirel2/YMGK-Modelling/assets/74304801/820f2bad-7027-4d38-9e27-1c0104db2c49)

Burada:

- u akışkan hızını,
- t, zamanı,
- x, uzay koordinatını,
- İlk terim, akışkanın konvektif hareketini,
- İkinci terim, kinetik enerjinin yayılmasını,
- Üçüncü terim, viskoziteyi,
- Son terim, yüksek düzeyde nonlineer etkileri temsil eder.



![image](https://github.com/Bahadirdemirel2/YMGK-Modelling/assets/74304801/7bb049b4-ff7c-4bcb-9032-ed813e861155)

Kuramoto-Sivashinsky denkleminin bir simülasyonunun uzay-zamansal grafiği

# SWOT Analizi

## Güçlü Yönler

- **Türbülansın Karmaşıklığını Modelleme:** Kuramoto-Sivashinsky denklemi, türbülansın karmaşıklığını, özellikle düşük boyutlu türbülansı modelleme konusunda etkili bir şekilde ele alabilir. Bu, akışkan dinamiğinin anlaşılması ve mühendislik uygulamaları için önemli bir avantaj sağlar.

- **Doğal Olayların Modelleme Yeteneği:** Denklem, yangınların yayılması, kimyasal reaksiyonlar, dalga oluşumu ve diğer birçok doğal olayın matematiksel modellemesinde kullanılabilir. Bu, çeşitli bilimsel ve mühendislik alanlarında gerçek dünya olaylarını anlama ve tahmin etme kabiliyetini artırır.

- **Sayısal ve Analitik Çözüm Yeteneği:** Kuramoto-Sivashinsky denklemi, hem sayısal hem de analitik çözüm teknikleri kullanılarak çözülebilir. Bu, denklemin matematiksel analizini ve uygulanabilirliğini artırır.

## Zayıf Yönler

- **Yüksek Hesaplama Gücü Gereksinimi:** Kuramoto-Sivashinsky denklemi bazen yüksek hesaplama gücü gerektirebilir, özellikle de zaman ve uzayda büyük ölçekli simülasyonlar yapılıyorsa. Bu, denklemin uygulanabilirliğini sınırlayabilir ve sayısal çözüm sürelerini uzatabilir.

- **İlk Değer Problemi:** Başlangıç ​​değerlerinin ve sınırların seçimi, Kuramoto-Sivashinsky denkleminin doğru ve güvenilir sonuçlar üretmesi için kritiktir. Bu, modelin hassas parametre ayarlarına ve başlangıç ​​koşullarına duyarlı olduğu anlamına gelir.

- **Karmaşık Yorumlama:** Denklemin çözümleri genellikle karmaşık olabilir ve doğrudan fiziksel yorumlamanın zor olabileceği durumlar ortaya çıkarabilir. Bu, modelin pratik uygulamalarında yorumlama ve sonuçları kullanma sürecini zorlaştırabilir.

## Fırsatlar

- **İleri Uygulamalar İçin Geliştirme:** Kuramoto-Sivashinsky denklemi, türbülans ve diğer karmaşık fenomenlerin daha iyi anlaşılması için daha gelişmiş sayısal tekniklerle birleştirilerek daha etkili bir şekilde kullanılabilir.

- **Gerçek Zamanlı Kontrol ve Tahmin İçin Kullanım:** Denklem, gerçek zamanlı türbülans kontrolü ve hava durumu tahmini gibi alanlarda uygulamalar için potansiyel sunar. Bu, çeşitli endüstriyel ve mühendislik uygulamalarında önemli bir avantaj sağlayabilir.

## Tehditler

- **Alternatif Modellerin Gelişimi:** Kuramoto-Sivashinsky denkleminin başka matematiksel modeller veya alternatif yaklaşımlar tarafından yerini alabileceği tehlikesi vardır. Bu, modelin kullanımını ve popülerliğini azaltabilir.

- **Deneysel Veri ile Uyumsuzluk:** Denklemin teorik sonuçları ile deneysel veriler arasındaki uyumsuzluklar, denklemin pratik uygulamalarını etkileyebilir ve güvenilirliğini azaltabilir.

- **Hassas Parametre Ayarları:** Kuramoto-Sivashinsky denklemi, modelin doğru çalışması için hassas parametre ayarlarını gerektirebilir. Bu parametrelerin belirlenmesi, deneysel verilere ve belirli uygulama alanlarına uygun olmalıdır.

# Fizibilite Raporu 

## 1. Uygulama Alanları

Kuramoto-Sivashinsky denklemi, çeşitli karmaşık sistemlerin modellenmesinde kullanılabilir. Öne çıkan uygulama alanları şunlardır:

- **Akışkan Dinamiği:** Sıvıların ve gazların karmaşık akışkan davranışlarını modeller.
- **Yüzey Morfolojisi:** Malzeme biliminde yüzey morfolojisini ve yüzey desenlenmesini incelemek için kullanılır.
- **Kimyasal Reaksiyonlar:** Kimyasal reaksiyonların kaotik davranışlarını modeller.

## 2. Teknik Zorluklar

Kuramoto-Sivashinsky denkleminin sayısal çözümü, bazı teknik zorluklarla karşılaşabilir:

- **Hesaplama Gücü:** Denklemin sayısal çözümü, yüksek performanslı bilgisayarlar gerektirir.
- **Hesaplama Karmaşıklığı:** Nonlineer doğası ve uzayda yüksek dereceli türevleri içeren yapısı, hesaplama karmaşıklığını artırır.
- **Stabilite ve Hassasiyet:** Sayısal algoritmaların ve parametrelerin doğru seçilmesi önemlidir; aksi takdirde, sonuçlar istenmeyen davranışlar gösterebilir.

## 3. Ekonomik Faktörler

Projenin ekonomik yönleri şunları içerebilir:

- **Donanım Maliyetleri:** Yüksek performanslı bilgisayarlar ve özel yazılımların maliyeti göz önünde bulundurulmalıdır.
- **İnsan Kaynağı:** Matematik, sayısal hesaplama ve programlama alanında uzman personel gereklidir.
- **Zaman ve Kaynaklar:** Projenin tamamlanması için gereken zaman ve kaynaklar, maliyet analizi yapılırken dikkate alınmalıdır.

## 4. Yasal ve Etik Hususlar

Projenin yasal ve etik boyutları şunlardır:

- **Veri Gizliliği:** Kullanılan verilerin gizliliği ve güvenliği sağlanmalıdır.
- **İzleme ve İzinler:** Gerekli izinlerin alınması ve ilgili mevzuata uyulması önemlidir.
- **Etik Standartlar:** Araştırmanın etik standartlara uygun olması ve olumsuz etkilerin önlenmesi gerekmektedir.





  





