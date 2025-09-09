# Kod-Adi-Dijital-CASE_CALISMASI

# Vehicle Pricing & Market Analysis Cases

Bu repo, **US Used Car Dataset** üzerinden hazırlanmış iki farklı case çalışmasını içerir.  
Her case, SQL veri hazırlama adımlarından başlayıp Python ile analiz/modelleme, görselleştirme ve ürün perspektifi önerileriyle tamamlanmaktadır.  

---

## 📂 CASE_1 – Exploratory  
**Başlık:** Adil Fiyatlandırma ve Kullanıcı Güveni  

- **Senaryo:** Kullanıcılar, araç fiyatlarının adil olup olmadığını anlamakta zorlanıyor. Şirket, fiyat şeffaflığını artıracak bir modül geliştirmeyi hedefliyor.  
- **Amaç:** Fiyat algısını etkileyen faktörleri veri üzerinden keşfetmek ve “Fiyat Şeffaflığı Modülü” önerisi sunmak.  
- **Adımlar:**
  - SQL ile veri hazırlama (marka, model, yıl, km, fiyat, satış süresi vb.)
  - Python + istatistik ile keşifsel analiz (fiyat dağılımı, varyans, korelasyonlar)
  - Görselleştirmeler: scatter, heatmap, histogram
  - KPI seti geliştirme (güven skoru, fiyat karşılaştırma CTR vb.)
  

---

## 📂 CASE_2 – Prescriptive  
**Başlık:** Dynamic Pricing ile Stok Yönetimi Optimizasyonu  

- **Senaryo:** Şirket, bazı araçları uzun süre satamıyor. Dynamic pricing engine ile stok devir süresini optimize etmek istiyor.  
- **Amaç:** Hem kârı koruyarak hem de elde kalan araçları azaltarak fiyatlama stratejisini geliştirmek.  
- **Adımlar:**
  - SQL ile stok devir süresi hesaplama (CTE + WINDOW fonksiyonları)  
  - Python ile regresyon analizi (fiyatın satış süresine etkisi)  
  - Simülasyon: %5, %10, %15 fiyat indirimi → satış süresine etkisi  
  - KPI trade-off analizi (hızlı satış vs. yüksek kâr)  
  - Dynamic Pricing MVP Roadmap  


---

🔎 Veri Kaynağı: [US Used Car Dataset (Kaggle)](https://www.kaggle.com/datasets/ananaymital/us-used-cars-dataset/data)  
