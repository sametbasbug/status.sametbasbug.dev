# status.sametbasbug.dev

Equinox ürünleri ve çalışma hatları için sade, statik durum panosu.

## Yaklaşım

Bu proje büyük şirket status sayfaları gibi sade ve öz tutulur. Karakter sitesi veya ürün vitrini değildir; kamusal yüzeylerin erişilebilirliğini ve önemli çalışma hattı durumlarını tek yerde gösterir.

Sayfa statiktir. Durumlar doğrulanıp bilinçli olarak güncellenir; kaldırılmış servislerden veri çekmez ve çalışmayan otomasyonları canlıymış gibi göstermez. Otomatik monitoring, ping geçmişi ve incident otomasyonu ileride ayrı bir geliştirme konusu olabilir.

## İzlenen yüzeyler

- **Equinox** — ekosistemin ana kapısı
- **Equinox Orbit** — Nyx, Hemera ve Asteria’nın ortak kamusal akışı
- **Ana blog** — kişisel yayın, sözlük ve içerik merkezi
- **Equinox Haber** — haber yüzeyi ve yayın arşivi
- **Signal Drift** — açık alpha oyun prototipi
- **Asteria yayın otomasyonu** — kamusal siteden ayrı izlenen çalışma hattı
- **Equinox ajan çalışma ortamı** — yalnız sınırlı bilgi gösterilen özel sistem

Ayrı Nyx, Hemera ve Asteria web odaları 10 Temmuz 2026 tarihinde emekliye ayrıldı. Ajanların ortak kamusal yüzeyi artık `orbit.sametbasbug.dev` adresidir.

## İçerik

- Genel durum özeti
- Kamusal servis listesi
- Duraklatılmış ve özel çalışma hatları
- Kısa değişiklik / incident geçmişi
- Açık ve koyu tema
- Özel 404 sayfası
- Sitemap

## Komutlar

```bash
npm install
npm run dev
npm run build
npm run preview
```

## Teknik notlar

- Build çıktısı: `dist/`
- Hedef domain: `status.sametbasbug.dev`
- Deploy modeli: GitHub Pages + özel domain
- Ana kapı: `https://equinox.sametbasbug.dev`
- Ortak ajan akışı: `https://orbit.sametbasbug.dev`
- Haber yüzeyi: `https://haber.sametbasbug.dev`
- Oyun yüzeyi: `https://play.sametbasbug.dev`
