# 🏋️‍♂️ Fitness Tracker Analysis & Prediction

## 📌 Proje Hakkında
Bu proje, **Fitness Tracker Dataset** üzerinde veri analizi, temizleme, makine öğrenmesi ve kullanıcı segmentasyonu çalışmalarını kapsamaktadır.  
Amaç:
- **Kalori yakımı tahmini** için regresyon modelleri geliştirmek  
- **Kullanıcı segmentasyonu** (K-Means) ile farklı kullanıcı profilleri çıkarmak  

---

## 📂 İçerik
1. **Veri Ön İşleme**
   - Eksik değerlerin incelenmesi ve doldurulması  
   - Kategorik değişkenlerin encode edilmesi  
   - Verilerin ölçeklenmesi  

2. **Keşifsel Veri Analizi (EDA)**
   - Demografik dağılımlar (yaş, cinsiyet, boy, kilo)  
   - Egzersiz süreleri, kalori yakımı, kalp atış hızları  
   - Korelasyon analizi (BMI, BPM, Kalori ilişkisi)  

3. **Makine Öğrenmesi Modelleri (Kalori Tahmini)**
   - Linear Regression  
   - Ridge Regression  
   - Lasso Regression  
   - Random Forest Regressor  
   - **Sonuçlar:** R² ≈ 0.01 → Özellikler ile kalori yakımı arasında güçlü bir tahmin gücü bulunamadı  

4. **Kullanıcı Segmentasyonu**
   - K-Means algoritması kullanıldı  
   - Özellikler: `Age, BMI, Workout_Frequency, Session_Duration, Calories_Burned`  
   - Kullanıcılar farklı kümelere ayrıldı (ör. düşük BMI – düşük kalori, orta seviye, yüksek performanslı kullanıcılar)  

---

## ⚙️ Kullanılan Kütüphaneler
```bash
pandas  
numpy  
matplotlib  
seaborn  
scikit-learn  
