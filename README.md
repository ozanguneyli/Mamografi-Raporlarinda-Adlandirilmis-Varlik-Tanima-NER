# Radyoloji Raporlarından BI-RADS Sınıflandırma ve Varlık İsmi Çıkarımı 

Bu proje şunları içermektedir, **Mamografi Radyoloji Raporlarından BI-RADS Sınıflandırması** ve **Mamografi Radyoloji Raporlarından Varlık İsmi Çıkarımı**.

## 📌 Özellikler
- **Türkçeye Özel Ön İşleme**: Tıbbi metinler için özel veri temizleme ve normalleştirme..
- **Birçok Model Test Edildi**: En iyi doğruluk oranına sahip model seçildi.
- **Çok Sınıflı BI-RADS Sınıflandırması**: BI-RADS 0-5 arası kategorileri sınıflandırır.
- **Varlık İsmi Çıkarımı (NER)**: Hasta bilgileri, hastalıklar ve semptomları algılar.

## 🛠️ Installation
```bash
git clone https://github.com/ozanguneyli/Mamografi_Raporlarından_Bi_Rads_Sınıflandırması_Ve_VİÇ.git
cd Mamografi_Raporlarından_Bi_Rads_Sınıflandırması_Ve_VİÇ
```


## 📊 Sonuçlar - Bi Rads Sınıflandırma
```
-Key Metrics:
-Precision Weighted Avg: 0.97
-Recall Weighted Avg: 0.0.97
-F1 Score Weighted Avg: 0.97
-Test F1 Score: 0.9666

```

![Confussion Matrix](bi_rads_confusion_matrix.png)

## 📊 Sonuçlar - Varlık İsmi Çıkarımı
```
-Key Metrics:
-F1 Score Weighted Avg: 0.9529

```

![Confussion Matrix](ner_confusion_matrix.png)
![Confussion Matrix](ner_loss_and_f1.png)
