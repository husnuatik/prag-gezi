# 🇨🇿 Prag Gezi Asistanı & Canlı Rota (iOS PWA)

Prag seyahati için özel olarak tasarlanmış, iOS Safari ve modern mobil tarayıcılarla tam uyumlu, çevrimdışı (offline) çalışabilen kişisel gezi rehberi ve canlı rota asistanı.

---

## ✨ Öne Çıkan Özellikler

1. **iOS Native Mini Uygulama Deneyimi (PWA):**
   - iPhone çentik (Notch) ve Dynamic Island ile tam uyumlu Safe-Area tasarımı.
   - iOS cam efekti (*Glassmorphism*), akıcı mikro animasyonlar ve haptic dokunma hissi.
   - **Service Worker** altyapısı sayesinde yurt dışında internet çekmese bile çevrimdışı çalışabilme.

2. **Eşle WhatsApp Paylaşım Entegrasyonu:**
   - **Sıradaki Hedefi Gönder:** O an sıradaki durağın adını, açıklamasını ve harita linkini tek tıkla eşinize WhatsApp'tan atabilme.
   - **Günün Rotasını Gönder:** Günün tüm duraklarını ve saatlerini şık bir liste olarak WhatsApp'tan paylaşma.
   - **Uygulama Linkini Gönder:** Eşinizin de kendi iPhone'unda uygulamayı açıp takip edebilmesi için hazır mesaj şablonu.
   - **Her Durak İçin "WP'den At" Butonu:** Belirli bir mekanın detayını ve navigasyon linkini tek tıkla WhatsApp sohbetine aktarma.

3. **Çift Harita Desteği:**
   - **🍏 Apple Haritalar:** iOS kullanıcıları için doğrudan Apple Maps'te yürüyüş/ulaşım rotası çizme.
   - **🗺️ Google Haritalar:** Alternatif tercih edenler için Google Maps ile canlı navigasyon.

4. **Canlı Mesafe & Sıradaki Hedef (Hero Card):**
   - GPS konumunu alarak duraklara olan uzaklığı anlık hesaplama (örn: *350 m*, *1.2 km*).
   - Tamamlanan duraklar otomatik elenir, sıradaki durak en üstte parlayan kart olarak öne çıkar.

5. **🔴 Canlı Prag Haber & Şehir Akışı (Live Ticker & Feed):**
   - Sayfanın en üstünde parlayan canlı kırmızı bildirim bandı (*Live Ticker*) 5 saniyede bir son dakika Prag haberlerini ve duyurularını otomatik akıtır.
   - **Prague Morning RSS** entegrasyonu ile Prag'ın en taze haberlerini canlı çeker.
   - 17 Kasım resmi tatili festival duyuruları, DPP tramvay hat değişiklikleri, meteoroloji don/ayaz uyarıları ve Noel pazarı hazırlıkları gibi seyahat için kritik duyuruları kategorize ederek listeler.
   - Çevrimdışı (offline) modda bile son bültenleri kesintisiz görüntüler.

6. **Prag Sahra Araçları (iOS Dock):**
   - **📰 Akış:** Canlı şehir nabzı ve Prag haberleri paneline tek tıkla erişim.
   - **💱 Çok Yönlü Canlı Kur Çevirici (CZK / EUR / TL / USD):** İster Euro, ister TL, ister Koruna girerek diğer para birimlerine anında canlı piyasa paritesiyle çeviri yapabilme.
   - **🚕 Taksi & Toplu Taşıma Rehberi:** Bolt & Uber tek tıkla çağırma butonları, 30 dk / 90 dk / 24 saatlik bilet fiyatları, 1.000 CZK ceza uyarısı ve panoramik tramvay hatları.
   - **🚻 Acil WC:** Konumunuza en yakın halka açık tuvaletleri tek tıkla haritada bulma.
   - **☕ Kafe & Dinlenme:** Çocukla dinlenebileceğiniz aile dostu kafeleri haritada bulma.
   - **🆘 İmdat & Çekçe Sözlük:** 112, Prag Büyükelçiliği, 6 yaş çocuk ulaşım kuralları ve sesli telaffuzlu Çekçe kalıplar.

7. **👟 Salomon & Outdoor Alışveriş Rehberi (18 Kasım Çarşamba):**
   - 17 Kasım Salı resmi tatili bozulmadan, mağazaların tam açık olduğu 18 Kasım Çarşamba gününe Lego Müzesi sonrası özel Salomon ve spor alışveriş durağı.
   - **Salomon Factory Outlet (Fashion Arena):** %30-%70 fabrika indirimi, Metro A + ücretsiz shuttle ulaşım rehberi.
   - **Sportisimo (Palladium AVM & Nový Smíchov):** Çekya'nın en büyük spor zincirinde Výprodej (tasfiye) fırsatları ve yerel kur avantajı.
   - **HalfPrice (Václavské Náměstí):** Çok katlı off-price devinde marka ayakkabı sürpriz indirimleri.
   - **💶 Tax-Free (%12-%14 İade):** 2.001 CZK üzeri alışverişlerde havalimanı KDV iadesi rehberi.

---

## 🚀 GitHub Pages Üzerinde Yayına Alma (2 Dakika)

1. Bu klasördeki dosyaları (`index.html`, `manifest.json`, `sw.js`, `README.md`) GitHub'da yeni bir depoya (repository) yükleyin.
2. Deponuzun **Settings (Ayarlar)** sekmesine gidin.
3. Soldaki menüden **Pages** seçeneğine tıklayın.
4. **Build and deployment > Branch** kısmından `main` (veya `master`) dalını ve `/ (root)` klasörünü seçip **Save** butonuna basın.
5. 1-2 dakika içinde size verilen `https://kullaniciadi.github.io/depo-adi/` bağlantısı canlıya geçecektir.

---

## 📱 iPhone'da Mini Uygulama Olarak Kurma

1. iPhone'unuzda **Safari** tarayıcısını açıp sitenizin linkine gidin.
2. Ekranın alt ortasındaki **Paylaş** simgesine (kare içinden yukarı çıkan ok) dokunun.
3. Menüyü aşağı kaydırıp **"Ana Ekrana Ekle" (Add to Home Screen)** seçeneğini seçin.
4. Artık ana ekranınızda tıpkı App Store'dan indirilmiş gibi tam ekran, çentikle uyumlu çalışan bir mini uygulamanız hazır!
