# 🐦 Bird Species Classification — Deep Learning Project

Bu proje, Kaggle üzerindeki [Bird Species Classification](https://www.kaggle.com/datasets/akash2907/bird-species-classification) veri setini kullanarak farklı kuş türlerini sınıflandırmayı amaçlamaktadır.  
Derin öğrenme yöntemleri, transfer learning ve görselleştirme teknikleri adım adım uygulanmıştır.  

---

## 📑 İçindekiler
- Proje Hakkında  
- Proje Adımları  
- Veri Seti  
- Kullanılan Yöntemler  
- Çalıştırma  
- Sonuçlar  
- Katkıda Bulunma  
- Lisans  
- İletişim  
- Teşekkür  

---

## 📌 Proje Hakkında
Bu proje, görüntü sınıflandırma alanında **kuş türlerini ayırt eden bir model** geliştirmeye odaklanır.  
EfficientNetB0 tabanlı transfer learning modeli ve veri artırma teknikleri ile yüksek doğruluk hedeflenmiştir.  

---

## 📌 Proje Adımları
Notebook toplamda 11 adımdan oluşmaktadır:

1. Proje Tanıtımı  
2. Ortam Hazırlığı ve Gereksinimler  
3. Veri Setini İndirme  
4. Veri Yapısı ve Keşifsel Analiz (EDA)  
5. Veri Ön İşleme ve Data Augmentation  
6. Model Kurulumu (EfficientNetB0 ile Transfer Learning)  
7. Modelin Eğitilmesi  
8. Modelin Değerlendirilmesi  
9. Grad-CAM ile Görselleştirme  
10. Hiperparametre Optimizasyonu (Keras Tuner)  
11. Genel Değerlendirme ve README İçin Notlar  

---

## 📂 Veri Seti
- Kaynak: [Kaggle - Bird Species Classification](https://www.kaggle.com/datasets/akash2907/bird-species-classification)  
- ~9.000 görüntü, 15 kuş türü  
- Eğitim, doğrulama ve test setlerine ayrılmış  

---

## ⚙️ Kullanılan Yöntemler
- **Veri Ön İşleme:** Normalizasyon, yeniden boyutlandırma  
- **Data Augmentation:** Flip, Rotation, Zoom, Contrast  
- **Model:** EfficientNetB0 tabanlı Transfer Learning, Dropout  
- **Değerlendirme:** Accuracy, Loss grafikleri, Confusion Matrix, Classification Report  
- **Görselleştirme:** Grad-CAM  
- **Hiperparametre Taraması:** Keras Tuner ile learning rate ve dropout  

---

## 🚀 Çalıştırma
1. Kaggle API anahtarınızı (`kaggle.json`) ekleyin.  
2. Notebook içindeki veri indirme hücresini çalıştırın.  
3. Hücreleri sırayla çalıştırarak modeli eğitin.  
4. Sonuçları inceleyin (grafikler, confusion matrix, Grad-CAM görselleri).  

---

## 📊 Sonuçlar
- Eğitim doğruluğu: %90+  
- Doğrulama doğruluğu: %88–90  
- Model, kuş türlerini ayırt etmede yüksek performans göstermektedir.  

---

## 📜 Lisans

Bu proje MIT lisansı ile lisanslanmıştır. Ayrıntılar için `LICENSE` dosyasına bakınız.

---

## 📬 İletişim

* İsim: Aleyna Çamlıbel
* GitHub: https://github.com/aleynacamlibel
* Kaggle: https://www.kaggle.com/aleynacamlibel

---

## 🙏 Teşekkür

Bu proje **Akbank Derin Öğrenme Bootcamp** kapsamında geliştirilmiştir.
Emeği geçen tüm eğitmenlere ve katılımcılara teşekkürler!

```
