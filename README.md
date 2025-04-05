# Radyoloji Raporlarından BI-RADS Sınıflandırma ve Varlık İsmi Çıkarımı 

Bu proje şunları içermektedir, **Mamografi Radyoloji Raporlarından BI-RADS Sınıflandırması** ve **Mamografi Radyoloji Raporlarından Varlık İsmi Çıkarımı**.

## 📌 Özellikler
- **Türkçeye Özel Ön İşleme**: Tıbbi metinler için özel veri temizleme ve normalleştirme..
- **Birçok Model Test Edildi**: En iyi doğruluk oranına sahip model seçildi.
- **Çok Sınıflı BI-RADS Sınıflandırması**: BI-RADS 0-5 arası kategorileri sınıflandırır.
- **Varlık İsmi Çıkarımı (NER)**: Hasta bilgileri, hastalıklar ve semptomları algılar.

## 🛠️ Installation
```bash
git clone Mamografi-Raporlarindan-Bi-Rads-Siniflandirmasi-Ve-NER.git
cd Mamografi-Raporlarindan-Bi-Rads-Siniflandirmasi-Ve-NER
```


## 📊 Sonuçlar - Bi Rads Sınıflandırma
- **Metrics Bar Chart**: Bar chart comparing key performance metrics (Precision, recall, F1, test F1 score)

![Metrics](images/metrics_plot.png)

- **Confusion Matrix**: Visual representation of the model's true positives, false positives, true negatives, and false negatives

![Confussion Matrix](images/bi_rads_confusion_matrix.png)

## 📊 Sonuçlar - Varlık İsmi Çıkarımı

- **F1 Score Bar Chart**: Bar chart shows key performance metric F1 Score

![F1-Score](images/f1_score_plot.png)

- **Confusion Matrix**: Visual representation of the model's true positives, false positives, true negatives, and false negatives

![Confussion Matrix](images/ner_confusion_matrix.png)

- **Training - Validation Loss and Training - Validation F1 Score Graphs**: Visual representation of the model's training and validation loss and F1 score, showing learning progression and balance between precision and recall.

![Loss and F1](images/ner_loss_and_f1.png)

## License

[MIT License](LICENSE)
