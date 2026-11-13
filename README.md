Kampüs Platformu

Üniversite öğrencileri ve kulüpler için tasarlanmış bir kampüs web platformu arayüzü. Kulüpler etkinliklerini duyurabilir, öğrenciler günün yemekhane menüsünü, yaklaşan etkinlikleri ve kütüphane/yemekhane doluluk oranlarını tek yerden görebilir.

Durum: Proje geliştirme aşamasındadır. Mevcut sürüm, HTML ve CSS ile hazırlanmış statik bir arayüz prototipidir; backend ve veritabanı henüz eklenmemiştir. Ekrandaki veriler örnek verilerdir ve menüdeki diğer sayfalar henüz hazır değildir.

Mevcut Özellikler (Arayüz)
Kulüp Başkanı / Öğrenci rol seçimli giriş ekranı
Karşılama alanı ve yaklaşan etkinlik kartları
Günün yemekhane menüsü (kalori bilgisiyle)
Akıllı bildirimler paneli
Merkez Kütüphane ve Merkez Yemekhane doluluk oranı göstergeleri
"Soru Sor" (akıllı asistan) bölümü
Kenar çubuğu menüsü (Ana Sayfa, Etkinlikler, Yemekhane, Kütüphane, Bildirimler, Akıllı Asistan, Soru Sor)
Laptop, tablet ve telefon ekranlarına uyum sağlayan duyarlı (responsive) yerleşim; telefonda açılır kenar çubuğu menüsü
Kullanılan Teknolojiler
HTML
CSS (Flexbox, media query)
Proje Yapısı
kampus-platformu/
├── index.html        # Giriş ekranı
├── anasayfa.html     # Ana sayfa
├── css/
│   └── style.css
├── resimler/         # Sayfalarda kullanılan görseller
└── screenshots/      # README ekran görüntüleri
Yol Haritası
 Etkinlikler, Yemekhane, Kütüphane, Bildirimler, Akıllı Asistan ve Soru Sor sayfalarının tamamlanması
 Backend ve MySQL veritabanı entegrasyonu
 QR kod ile kütüphane ve yemekhane giriş-çıkış sistemi, doluluk oranının otomatik hesaplanması
 Akıllı bildirim sistemi (ör. "bugün 2 etkinlik var")
 Yapay zekâ asistanı ("bugün kampüste ne var?" sorusuna etkinlikleri sıralayarak yanıt)
 ESP32 ve sensörlerle IoT tabanlı doluluk ölçümü
Çalıştırma

Projeyi indirin ve index.html dosyasını tarayıcınızda açın.

Ekran Görüntüleri
Giriş ekranı

Giriş ekranı

Ana sayfa

Ana sayfa

Doluluk oranları

Doluluk oranları
