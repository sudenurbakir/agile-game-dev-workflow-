# Agile Metrikleri ve Raporlama

Oyun geliştirme sürecinde ilerlemeyi ölçmek ve doğru kararlar almak için kullanılan temel metrikler.

## 1. Burndown Chart

Sprint içinde kalan iş miktarını gün gün gösteren grafiktir.

**Örnek:**
- Sprint başında 40 Story Point iş var.
- İdeal çizgi her gün eşit şekilde azalarak 0’a iner.
- 5. günde hâlâ 28 Story Point kaldıysa takım geride demektir.

**Ne işe yarar?**
- Takım planlandığı gibi ilerliyor mu hemen görülür.

## 2. Velocity (Hız)

Takımın bir sprintte ortalama ne kadar iş bitirdiğini gösterir.

**Örnek:**
- Sprint 1 → 32 Story Point
- Sprint 2 → 28 Story Point
- Sprint 3 → 35 Story Point
- Ortalama Velocity ≈ 32 Story Point

**Ne işe yarar?**
- Gelecek sprintte “Biz yaklaşık 30-35 Story Point iş alabiliriz” diye plan yapılır.

## 3. Cycle Time

Bir işin “In Progress” durumundan “Done” durumuna gelene kadar geçen süredir.

**Örnek:**
- “Günlük giriş ödülü” feature’ı 4 gün sürdü.
- “Yeni karakter ekleme” 11 gün sürdü.
- Ortalama Cycle Time 6-7 gün çıkıyorsa süreç yavaş demektir.

## 4. Lead Time

Bir işin backlog’a eklendiği andan tamamlanana kadar geçen toplam süredir.

**Örnek:**
- Bir fikir 12 Mart’ta backlog’a eklendi.
- 5 Nisan’da canlıya çıktı.
- Lead Time = 24 gün

## 5. Throughput

Belirli bir sürede tamamlanan iş sayısıdır.

**Örnek:**
- Son 2 haftada 9 User Story tamamlandı.
- Haftalık Throughput = 4.5 User Story

## 6. Sprint Goal Success Rate

Sprint hedefinin ne kadar başarıldığını gösterir.

**Örnek:**
- Son 6 sprintten 5’inde Sprint Goal tamamen başarıldı.
- Success Rate = %83

## Oyun Sektöründe Özellikle Takip Edilenler

- Feature’ların canlıya çıkış süresi
- Live Ops event’lerinin hazırlanma süresi
- Bug’ların çözülme süresi (özellikle major bug’lar)
- Oyuncu feedback’ine göre yapılan değişikliklerin hızı

## Business Analyst Olarak Senin Rolün

- Metrikleri düzenli takip etmek
- Anlamlı raporlar hazırlamak
- “Neden böyle oldu?” sorusunu sormak
- Süreç iyileştirme önerileri getirmek

---

**Not:**  
Metrikler amaç değil araçtır. Sadece sayıya bakıp takımı yargılamak yerine, süreci iyileştirmek için kullanılmalıdır.
