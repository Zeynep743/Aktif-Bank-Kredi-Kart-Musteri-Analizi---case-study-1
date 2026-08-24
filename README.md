# AKTİFBANK – Kredi Kartı Müşteri Analizi

## Proje Hakkında

Bu proje, kredi kartı müşteri verilerinin analiz edilmesi, müşterilerin segmentlere ayrılması ve sonuçların iş kararlarını destekleyecek şekilde görselleştirilmesi amacıyla hazırlanmıştır.

Çalışmada veri temizleme, PivotTable, müşteri segmentasyonu, Pareto analizi, etkileşimli Dashboard ve VBA otomasyonu kullanılmıştır.

## Yapılan Analizler

- Veri temizleme ve kalite kontrolleri
- Müşteri segmentasyonu
- PivotTable analizleri
- Kredi limiti ve işlem tutarı analizi
- Demografik analizler
- Pasiflik süresi analizi
- Pareto analizi
- En yüksek harcama yapan 10 müşterinin analizi

## Müşteri Segmentleri

- Düzenli
- Pasif
- Potansiyel VIP
- Risk Altında
- VIP

## Dashboard ve Otomasyon

Excel üzerinde etkileşimli bir yönetim Dashboard'u oluşturulmuştur.

Dashboard'da:

- Toplam müşteri
- Ortalama kredi limiti
- Ortalama işlem tutarı
- Ortalama kullanım oranı
- Dinamik filtreler
- Ortalama, maksimum ve minimum metrik değerleri

bulunmaktadır.

VBA ile **Veri Yenile** ve **Rapor Oluştur** butonları geliştirilmiştir.

## Pareto Analizi

Müşterilerin işlem tutarlarının dağılımını incelemek ve yüksek harcama yapan müşteri grubunu belirlemek amacıyla Pareto analizi gerçekleştirilmiştir.

Ayrıca en yüksek işlem tutarına sahip 10 müşteri belirlenmiştir.

## Temel Bulgular

- VIP müşteriler en yüksek ortalama işlem tutarı ve kredi limitine sahiptir.
- Risk Altında segmenti müşteri sayısı bakımından en büyük segmenttir.
- Risk Altında segmentinde kullanım oranı yüksektir.
- Potansiyel VIP müşteriler müşteri değerini artırmak için önemli bir hedef gruptur.
- Yüksek harcama yapan müşteriler VIP ve sadakat stratejileri açısından değerlendirilebilir.

## İşletmesel Öneriler

- VIP müşterilere özel kampanya ve sadakat uygulamaları
- Potansiyel VIP müşterilere yönelik hedefli teklifler
- Yüksek riskli müşteriler için erken uyarı ve takip sistemi
- Düşük limit veya kullanım oranına sahip müşteriler için çapraz satış fırsatları

## Requirements

- Microsoft Excel 2016 veya üzeri
- VBA makrolarının çalıştırılmasına izin verilmesi
- `.xltm` dosya formatını destekleyen Excel
- Windows işletim sistemi önerilir

## Proje Dosyaları

- `excel/` → Excel analiz, Dashboard ve VBA otomasyon dosyası
- `rapor/` → Proje raporu

## Sonuç

Bu çalışma ile müşteri verilerinin analiz edilmesi, müşterilerin davranışlarına göre segmentlere ayrılması ve analiz sonuçlarının Dashboard ve otomasyonlar aracılığıyla yönetim kararlarını destekleyecek şekilde sunulması amaçlanmıştır.
