# SSFitness sitesi

Tek sayfa, statik. JavaScript ve dış kaynak yok (yazı tipleri projede, OFL). Kart sistemi ayrı bir adreste çalışır; site üye verisine erişmez.

- QR kodu (`qr-whatsapp.svg`) salonun WhatsApp hattını açar; yeniden üretmek için kart sistemi projesindeki `araclar/site-qr.js`.
- Google için işletme bilgisi `index.html` içindeki JSON-LD bloğunda (ExerciseGym: ad, adres, telefon, fiyatlar).

## Açılış listesi (alan adı bağlanınca)

1. `CNAME` dosyası: `ssfitness.com.tr`.
2. `index.html`: `robots` satırını `index, follow` yap; `canonical`, `og:image`, JSON-LD `url` / `logo` / `image` adreslerini yeni alan adına çevir; KVKK linkini kart sisteminin yeni adresine (`kapi.ssfitness.com.tr`) çevir.
3. Doğancan teyit etti (21 Kas): adres 1A; Pazartesi–Cumartesi 10:00–22:00, Pazar kapalı; ağırlık ve kardiyo alanı, soyunma odası ve duş var. Samet'e sorulacaklar: telefonun sitede görünmesi, beslenme programını kimin hazırladığı.
4. Fotoğraflar (`foto/`) eski ve küçük (680×382), geçici. Yenileri aynı dosya adlarıyla değişir: webp, en az 1600 px genişlik, `width`/`height` güncellenir. Yüzü seçilen kişi varsa ya izni alınır ya yüzü bulanıklaştırılır (KVKK). Stok fotoğraf kullanılmaz.
5. `robots.txt` ve `sitemap.xml` ekle; Google Search Console'a alan adını ekleyip site haritasını gönder.
6. Google İşletme Profili'ne site adresini yaz.
