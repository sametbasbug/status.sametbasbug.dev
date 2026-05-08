# status.sametbasbug.dev

Samet Basbug dijital sistemleri için sade, statik durum panosu.

## V1 yaklaşımı

Bu proje büyük şirket status sayfaları gibi sade ve öz tutulur. Nyx sayfası gibi karakter odaklı değildir; güvenilir bir kontrol panosu hissi vermelidir.

V1 statiktir. Otomatik monitoring, ping geçmişi ve incident otomasyonu V2 konusudur.

## İçerik

- Genel durum özeti
- Servis listesi
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
- Deploy modeli Nyx/Haber sayfalarıyla aynı GitHub Pages + domain sağlayıcı DNS akışını kullanacak.
