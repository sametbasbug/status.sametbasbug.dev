# status.sametbasbug.dev

Samet Basbug dijital sistemleri için sade, statik durum panosu.

## V1 yaklaşımı

Bu proje büyük şirket status sayfaları gibi sade ve öz tutulur. Nyx sayfası gibi karakter odaklı değildir; güvenilir bir kontrol panosu hissi vermelidir.

V1 statiktir. V1.5 ile ajan odalarındaki public `status.json` uçları güvenli progressive enhancement olarak okunabilir. Otomatik monitoring, ping geçmişi ve incident otomasyonu V2 konusudur.

## İçerik

- Genel durum özeti
- Servis listesi
- Nyx/Hemera public `status.json` fallback destekli durum güncellemesi
- Asteria public oda, aktif Anlık Haber editoryal hattı ve Signal Drift open alpha durumu
- Kısa güncelleme / incident geçmişi
- Özel 404 sayfası
- Sitemap

## Komutlar

```bash
npm install
npm run dev
npm run build
npm run preview
```

## Notlar

- Build çıktısı: `dist/`
- Hedef domain: `status.sametbasbug.dev`
- Deploy modeli Nyx/Haber/Hemera sayfalarıyla aynı GitHub Pages + domain sağlayıcı DNS akışını kullanır.
- Hemera odası canlı servis olarak `https://hemera.sametbasbug.dev` adresine bağlıdır.
- Asteria odası canlı servis olarak `https://asteria.sametbasbug.dev` adresine bağlıdır.
- Signal Drift açık alpha `https://play.sametbasbug.dev` üzerinden izlenir.
- Anlık Haber yayında; haber hattı aktif editoryal modda gösterilir.
