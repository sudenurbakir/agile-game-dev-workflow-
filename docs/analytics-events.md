# Analytics Event’leri Nedir ve Nasıl Yönetilir?

Oyunlarda oyuncu davranışlarını ölçmek için kullanılan kayıtlara **Analytics Event** denir.

## Neden Önemlidir?

- Oyuncuların nerede zorlandığını anlarız
- Hangi feature’ların işe yaradığını görürüz
- Para kazanma (monetization) performansını takip ederiz
- Daha iyi kararlar almamızı sağlar

## Örnek Analytics Event’leri

| Event Adı            | Ne Zaman Çalışır?                     | Ne İşe Yarar?                          |
|----------------------|---------------------------------------|----------------------------------------|
| level_complete       | Oyuncu bir seviyeyi geçtiğinde        | Hangi seviyeler zor, hangileri kolay?  |
| purchase_success     | Oyuncu bir şey satın aldığında        | En çok ne satılıyor?                   |
| ad_watched           | Oyuncu reklam izlediğinde             | Reklam geliri ne kadar?                |
| session_start        | Oyun açıldığında                      | Günlük aktif kullanıcı sayısı          |
| tutorial_complete    | Eğitim tamamlandığında                | Eğitim ne kadar etkili?                |

## Süreç Nasıl İlerler?

1. **İhtiyaç Belirlenir**  
   Business Analyst + Game Designer + Analytics sorumlusu hangi verilerin gerekli olduğuna karar verir.

2. **Event Listesi Oluşturulur**  
   Net bir liste hazırlanır (event adı, ne zaman tetikleneceği, hangi verilerin gideceği).

3. **Developer’a Verilir**  
   User Story veya task olarak yazılır.

4. **Kodlanır ve Test Edilir**  
   Developer ekler, QA ve BA test eder.

5. **Canlıya Çıkar ve Takip Edilir**  
   Veriler dashboard’lardan izlenir ve yorumlanır.

## Business Analyst’in Rolü

- Hangi event’lerin gerekli olduğunu belirlemeye yardımcı olmak
- Event listesini net ve anlaşılır yazmak
- Developer’a doğru şekilde aktarmak
- Gelen verileri yorumlayıp öneriler sunmak

---
