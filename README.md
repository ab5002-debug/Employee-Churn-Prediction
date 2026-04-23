# 📊 Employee Churn Prediction Model | Personel Ayrılma Tahmin Modeli



---

## 🇺🇸 English

> [!NOTE]
> **Language Disclaimer:** The technical explanations and code comments within the Jupyter Notebook (`.ipynb`) are written in **Turkish**. If you do not speak Turkish, I recommend using a browser translator or an AI tool to follow the analysis steps more easily.

### 🚀 Project Overview
This project focuses on predicting employee turnover (churn) by analyzing demographic and performance data. Using a **Gradient Boosting Classifier**, the model identifies employees at risk of leaving with high accuracy, enabling HR departments to implement data-driven retention strategies.

### 🎯 Objectives
- Build a decision-support mechanism for Human Resources.
- Proactively detect potential resignations to prevent talent loss.
- Optimize model sensitivity for identifying "at-risk" employees.

### 🛠️ Technical Specifications
- **Algorithm:** Gradient Boosting Classifier
- **Optimization:** Hyperparameter tuning via **GridSearchCV** (450 and 540 combinations tested).
- **Dataset:** 2500+ Rows / 28 Features.
- **Tech Stack:** Python, Scikit-learn, Pandas, NumPy, Matplotlib, Seaborn.

### 📈 Model Performance
After fine-tuning and threshold optimization, the model achieved the following metrics:

| Metric | Score |
| :--- | :--- |
| **Accuracy** | **%89.92** |
| **Optimal Threshold** | **0.44** |
| **Training Success** | **%92.78** |

### 🚀 How to Run
1. Clone this repository.
2. Install dependencies: `pip install -r requirements.txt`
3. Run the analysis: Open `Employee_Churn_Analysis.ipynb` in Jupyter Notebook and execute all cells.

---

## 🇹🇷 Türkçe

> [!IMPORTANT]
> **Dil Notu:** Jupyter Notebook (.ipynb) dosyası içerisindeki teknik açıklamalar ve kod yorumları **Türkçe** olarak kaleme alınmıştır.

### 🚀 Proje Hakkında
Bu proje, demografik ve performans verilerini analiz ederek çalışanların işten ayrılma olasılıklarını (churn) tahmin etmeye odaklanmaktadır. **Gradient Boosting Classifier** algoritması kullanılan model, ayrılma riski olan çalışanları yüksek doğrulukla tespit ederek İK departmanlarının veri odaklı elde tutma stratejileri geliştirmesine olanak tanır.

### 🎯 Projenin Amacı
- İnsan Kaynakları departmanları için bir karar destek mekanizması oluşturmak.
- Potansiyel istifaları önceden tespit ederek yetenek kaybını önlemek.
- "Risk altındaki" çalışanları belirlemek için model duyarlılığını optimize etmek.

### 🛠️ Teknik Özellikler
- **Algoritma:** Gradient Boosting Classifier
- **Optimizasyon:** **GridSearchCV** ile hiperparametre optimizasyonu (450 ve 540 farklı kombinasyon denenmiştir).
- **Veri Seti:** 2500+ Satır / 28 Özellik (Feature).
- **Kullanılan Araçlar:** Python, Scikit-learn, Pandas, NumPy, Matplotlib, Seaborn.

### 📈 Başarı Oranları
İnce ayarlar ve eşik değeri (threshold) optimizasyonu sonucunda model şu değerlere ulaşmıştır:

| Metrik | Skor |
| :--- | :--- |
| **Doğruluk (Accuracy)** | **%89.92** |
| **Optimal Eşik Değeri** | **0.44** |
| **Eğitim Seti Başarısı** | **%92.78** |

### 🚀 Nasıl Çalıştırılır?
1. Bu depoyu klonlayın.
2. Gerekli kütüphaneleri kurun: `pip install -r requirements.txt`
3. Analizi başlatın: `Employee_Churn_Analysis.ipynb` dosyasını Jupyter üzerinden açın ve tüm hücreleri çalıştırın.

---
*Developed as a case study with AI assistance.* *Yapay zeka asistanı desteğiyle bir vaka çalışması olarak yürütülmüştür.*
