# VitrinKodu

Jekyll tabanlı, GitHub Pages ile yayınlanabilen statik web sitesi.

## Ortak alanlar
- Üst menü: `_includes/header.html`
- Alt alan: `_includes/footer.html`
- Genel SEO meta etiketleri ve ortak stiller: `_includes/head.html`
- Sayfa şablonları: `_layouts/`

Header/footer birden fazla sayfaya kopyalanmaz; değişiklikler ilgili ortak include dosyasından yapılır.

## Demo kataloğu
- Katalog: `demolar/index.html`
- Her demo ayrı URL ve sayfa: `demolar/ornekler/<slug>/index.html`
- Yeni demo eklerken katalog kartını, örnek sayfayı ve `sitemap.xml` girdisini birlikte ekleyin.
- Demo işletme adları ve içerikleri temsilidir; gerçek müşteri referansı değildir.

## Yayınlama
Dosyaları GitHub deposuna yükleyip Pages iş akışının tamamlanmasını bekleyin. Canlı ortamda yayın sonrası mobil görünüm, bağlantılar, canonical ve sitemap ayrıca kontrol edilmelidir.
