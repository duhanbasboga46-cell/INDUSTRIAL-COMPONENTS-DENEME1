Görev:Sadece tek bir HTML/JS dosyası (veya React bileşeni) halinde çalışan, tamamen etkileşimli, 
son derece sade ve modern tasarıma sahip bir "Endüstriyel Sektör, Makine ve Komponent Gezgini" uygulaması oluştur.

1. Mimari ve Çalışma Mantığı (Hiyerarşi)

Uygulama 3 aşamalı bir gezinti mantığına sahip olmalıdır. Kullanıcı sayfayı yenilemeden (Single Page) şu adımları takip etmelidir:

a. Sektör Seçimi (Ana Ekran): Kullanıcı tanımlı sektörlerin listesini görür. Bir sektöre tıklar.

b. Makine Seçimi (2. Ekran): Tıklanan sektöre ait makineler listelenir. Kullanıcı bir makineye tıklar. 
(Üstte her zaman geri dönmek için bir "Geri" butonu veya Breadcrumb/Ekmek kırıntısı navigasyonu olmalıdır).

c. Komponent Listesi (3. Ekran): Tıklanan makinenin içerisinde bulunan endüstriyel komponentler temiz bir liste halinde alt alta sıralanır.


2. Tasarım ve Kullanıcı Deneyimi (UX/UI)

Sadelik: Uygulama karmaşık grafiklerden uzak, kurumsal ve endüstriyel bir sadelikte olmalıdır. Gri, beyaz ve koyu mavi/lacivert tonları tercih edilmelidir.

Navigasyon: Kullanıcı hangi sektörde ve hangi makinede olduğunu ekranın üstündeki yoldan 
(Örn: Sektörler > Maden Sektörü > Konveyör) net bir şekilde görmeli ve geriye tek tıkla dönebilmelidir.

Kart Yapısı: Sektörler ve makineler geniş, tıklanabilir minimalist kartlar (cards) şeklinde listelenmelidir. Hover (üzerine gelince renk değişimi) efekti olmalıdır.
Responsive: Hem bilgisayar ekranlarında hem de mobil telefonlarda tam uyumlu çalışmalıdır.


3. Başlangıç Veri Seti (Mock Data)

Uygulama açıldığında içerisine gömülü (hardcoded) olarak şu örnek veri seti ile başlamalıdır:

Sektör: Maden Sektörü
  Makine: Konveyör
    Komponentler (Sırasıyla):
      Redüktör
      Elektrik Motoru
      Termal Switch
      Şase
      Aksiyel Fan Soğutma
      PT 100

(Geliştirici Notu: Kod yapısını öyle kur ki, ileride ben kodun en üstündeki veri objesine yeni sektörler, makineler ve komponentler eklediğimde uygulama otomatik olarak genişleyebilsin.)


4. Çıktı FormatıKodu bana Claude Artifact (React veya HTML/Tailwind) penceresinde, doğrudan "Önizleme" (Preview) modunda çalışacak şekilde tek bir parça halinde ver.



