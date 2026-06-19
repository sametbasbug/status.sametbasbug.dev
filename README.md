# status.sametbasbug.dev

Samet Başbuğ dijital sistemleri için sade, statik arşiv durum panosu.

## V1 yaklaşımı

Bu proje büyük şirket status sayfaları gibi sade ve öz tutulur. Nyx sayfası gibi karakter odaklı değildir; güvenilir bir kontrol panosu hissi vermelidir.

Final arşiv durumunda sayfa, aktif operasyon göstergesi değil; Equinox ekosistemindeki public yüzeylerin silinmeden arşiv olarak korunduğunu anlatan merkezi kayıt olarak davranır.

## İçerik

- Genel arşiv durumu özeti
- Yayında kalan public yüzeylerin arşiv durumları
- OpenClaw local runtime için yalnız sınırlı/özel kamu bilgisi
- Kısa güncelleme / kapanış geçmişi
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
- Bu sayfa kapanış zincirinin sonunda güncellenen merkezi arşiv durum kaydıdır.
- Nyx/Hemera `status.json` progressive enhancement yolu kaldırıldı; final durumda merkezi status metni override edilmemelidir.
- Equinox, Signal Drift, Ana blog, Equinox Haber, Nyx, Hemera ve Asteria public yüzeyleri aktif operasyon yerine arşiv olarak gösterilir.
