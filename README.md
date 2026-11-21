# SSFitness sitesi

Tek sayfa, statik. JavaScript ve dış kaynak yok (yazı tipleri projede, OFL). Kart sistemi ayrı bir adreste çalışır; site üye verisine erişmez.

- QR kodu (`qr-whatsapp.svg`) salonun WhatsApp hattını açar; yeniden üretmek için kart sistemi projesindeki `araclar/site-qr.js`.
- Google için işletme bilgisi `index.html` içindeki JSON-LD bloğunda (ExerciseGym: ad, adres, telefon, fiyatlar).

## Açılış listesi (alan adı bağlanınca)

1. `CNAME` dosyası: `ssfitness.com.tr`.
2. `index.html`: `robots` satırını `index, follow` yap; `canonical`, `og:image`, JSON-LD `url` / `logo` / `image` adreslerini yeni alan adına çevir; KVKK linkini kart sisteminin yeni adresine (`kapi.ssfitness.com.tr`) çevir.
3. Samet Şen'in teyidiyle:
   - adres (1A / 1B),
   - çalışma saatleri: hangi günler açık? (JSON-LD `openingHours` da eklenir),
   - telefonun sitede görünmesi,
   - "Salonda" kutuları: ağırlık alanı, soyunma odası, beslenme programını kimin hazırladığı (hoca / Samet).
4. Fotoğraflar: `.foto-yer` kutuları (kapak + 5 galeri) gerçek fotoğraflarla değişir (`<img>`, webp, genişlik/yükseklik verilerek). Stok fotoğraf kullanılmaz.
5. `robots.txt` ve `sitemap.xml` ekle; Google Search Console'a alan adını ekleyip site haritasını gönder.
6. Google İşletme Profili'ne site adresini yaz.
