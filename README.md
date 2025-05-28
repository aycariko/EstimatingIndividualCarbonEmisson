# EstimatingIndividualCarbonEmisson


## 🔍 Proje Açıklaması

Bu proje, çeşitli araç özelliklerine göre bireysel karbon emisyonlarını tahmin etmeyi amaçlamaktadır. Makine öğrenmesi teknikleri kullanılarak, eksik veriler doldurulmuş, kategorik değişkenler encode edilmiş, veriler normalize edilmiş ve farklı modeller kıyaslanmıştır. GridSearchCV ile hiperparametre optimizasyonu yapılmış ve en iyi model test verisi üzerinde değerlendirilmiştir.

## ✨ Özellikler

- Eksik verilerin doldurulması
- Ordinal ve One-Hot Encoding uygulamaları
- Min-Max normalizasyon
- Farklı regresyon modelleriyle karşılaştırma
- K-Fold Cross Validation ile model değerlendirme
- GridSearchCV ile hiperparametre ayarı
- MAE, RMSE ve R² skorlarıyla performans ölçümü

## 🛠 Kullanılan Teknolojiler

- Python 3.x
- Pandas
- NumPy
- Scikit-learn
- Matplotlib / Seaborn (isteğe bağlı görselleştirme için)

## ⚙️ Kurulum

```bash
git clone https://github.com/kullanici-adi/carbon-emission-prediction.git
cd carbon-emission-prediction
pip install -r requirements.txt
```

Alternatif olarak notebook'u Google Colab'de açabilirsiniz.

## ▶️ Kullanım

1. `carbon_emission.ipynb` dosyasını açın.
2. Adım adım kod hücrelerini çalıştırarak:
   - Veriyi yükleyin
   - Eksik verileri doldurun
   - Encoding işlemlerini gerçekleştirin
   - Veriyi normalize edin
   - Model oluşturun, eğitin ve değerlendirin
3. Sonuçları yorumlayın

## 📊 Sonuçlar ve Model Performansı

- **Test R² Skoru:** 0.981  
- **Test RMSE:** 138.98  
- **Test MAE:** 101.88  

Bu sonuçlar, Gradient Boosting Regressor modelinin veri üzerinde oldukça başarılı olduğunu göstermektedir.

