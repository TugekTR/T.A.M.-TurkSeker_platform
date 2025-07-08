# T.A.M. Platformu

**Teknoloji ve Akıl Modülü (T.A.M.)**, üretimden sevkiyata kadar tüm tedarik zinciri süreçlerini dijital olarak yöneten, modüler bir yönetim platformudur.

## 📁 Klasör Yapısı (Önerilen)

```bash
📦 tam-platform
├── README.md
├── docs/                      # Proje dokümantasyonları (toplantı notları, akış şemaları)
├── sql/                       # SQL şemaları ve örnek sorgular
│   ├── schema/                # Tabloların oluşturulma scriptleri
│   └── seed/                  # Örnek veri ekleme scriptleri
├── json/                      # Örnek veri setleri (API input/output, payload örnekleri)
├── modules/                   # Modül bazlı kaynaklar
│   ├── order-management/      # Sipariş Yönetimi
│   ├── job-orders/            # İş Emirleri
│   ├── inventory/             # Stok Yönetimi
│   ├── logistics/             # Lojistik ve Taşıma
│   └── master-data/           # Ana Veri Yönetimi
└── assets/                    # Görseller, diyagramlar, figmalar vb.
```

## 🎯 Amaç
Bu proje; şeker üretimi, paketleme ve sevkiyat süreçlerinin izlenebilirliğini sağlamak ve karar destek sistemleri oluşturmak için tasarlanmıştır.

## 🔧 Ana Modüller
- **Müşteri Sipariş Yönetimi**
- **Sipariş İşleme ve Karar Motoru**
- **İş Emri Yönetimi** (Üretim, Paketleme, Taşıma)
- **Stok Yönetimi**
- **Lojistik ve Taşıyıcı Yönetimi**
- **Destekleyici Modüller** (MDM, Bildirim, Sözleşme vb.)

## 📌 Katkı ve Kullanım
Bu depo şu an aktif geliştirme aşamasındadır. Öneri, düzeltme ve katkılar için issue/pull request açabilirsiniz.
