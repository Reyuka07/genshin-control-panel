# Teyvat Control — Genshin Kontrol Paneli

İlk prototip. Tek dosyalı, mobil uyumlu web arayüzü.

## Özellikler
- UID alanı (varsayılan: 753934980)
- Karakter koleksiyonu ekleme/silme
- Dilek kayıtları ve toplamlar
- Primogem / Fate kaynak takibi
- Hedef dilek hesaplayıcı
- Veriler tarayıcının localStorage alanında tutulur

## Önemli sınırlar
Bu sürüm Enka UID API'sine bağlanmaz. UID tek başına gizli envanter, Primogem veya dilek geçmişini vermez. Bu özellikler için güvenli bir sunucu katmanı ve/veya manuel veri girişi gerekir. Veriler şu an yalnızca kullanılan tarayıcı/cihazda saklanır; bulut senkronizasyonu yoktur.

## Çalıştırma
`index.html` dosyasını bir tarayıcıda açabilir veya GitHub Pages ile yayınlayabilirsin.
