# 📊 Employee Churn Prediction Model 


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
  
 ### 📊  Veri Sözlüğü

| Türkçe Başlık (Dataset) | English Equivalent | Description / Açıklama |
| :--- | :--- | :--- |
| **İşten Çıkma Durumu** | **Churn Status** | **Target Variable (Target)** |
| Yas_Araligi | Age Range | Employee's age group |
| Banka / AVM / Enerji | Sector Indicators | Workplace / Sector type |
| Fabrika / Holding / Universite | Workplace Type | Organization structure |
| Guvenlik / CCVT | Security Roles | Specific security/monitoring roles |
| Vardiya_Amiri | Shift Supervisor | Supervisory role status |
| Guvenlik_Muduru | Security Manager | Managerial level status |
| Emekli/Değil | Retirement Status | Whether the employee is retired |
| Genel_Mudurluk / Istanbul | Location/HQ | Headquarters or city status |
| Tasra | Province/Rural | Working in rural or provincial areas |
| Calisma_Suresi_Grubu | Tenure Group | Seniority/working duration category |
| Calistigi_Gun_Sayisi | Total Days Worked | Number of days employed |
| Kamu / Özel | Public / Private | Employment sector |
| Silahlı/Silahsız | Armed / Unarmed | Security license type |
| Asgari Ücret ORANI | Minimum Wage Ratio | Salary relative to minimum wage |
| Fazla Mesai Ücret Oranı | Overtime Pay Ratio | Percentage of overtime pay |
| YOL / Yemek Ücreti Oranı | Travel/Meal Allowance | Benefit ratios |
| PRİM Ücreti Oranı | Bonus/Premium Ratio | Additional performance pay ratio |

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

 ### 📊 Veri Sözlüğü

| Veri Seti Sütunu (Orijinal) | İngilizce Karşılığı | Açıklama |
| :--- | :--- | :--- |
| **İşten Çıkma Durumu** | **Churn Status** | **Hedef Değişken (Çalışanın ayrılma durumu)** |
| Yas_Araligi | Age Range | Çalışanın yaş grubu |
| Banka / AVM / Enerji | Sector Indicators | Çalışılan iş yeri / Sektör türü |
| Fabrika / Holding / Universite | Workplace Type | Kurumsal yapı türü |
| Guvenlik / CCVT | Security Roles | Güvenlik veya izleme odaklı görevler |
| Vardiya_Amiri | Shift Supervisor | Vardiya amirliği durumu |
| Guvenlik_Muduru | Security Manager | Güvenlik müdürlüğü/yöneticilik durumu |
| Emekli/Değil | Retirement Status | Emeklilik durumu bilgisi |
| Genel_Mudurluk / Istanbul | HQ / Istanbul | Genel müdürlük veya İstanbul lokasyonu |
| Tasra | Province / Rural | Taşra veya kırsal bölgelerde çalışma durumu |
| Calisma_Suresi_Grubu | Tenure Group | Kıdem ve çalışma süresi kategorisi |
| Calistigi_Gun_Sayisi | Total Days Worked | Şirkette çalışılan toplam gün sayısı |
| Kamu / Özel | Public / Private | İstihdam edilen sektör (Kamu veya Özel) |
| Silahlı/Silahsız | Armed / Unarmed | Güvenlik kimlik kartı ve silah türü |
| Asgari Ücret ORANI | Min. Wage Ratio | Maaşın asgari ücrete olan oranı |
| Fazla Mesai Ücret Oranı | Overtime Pay Ratio | Fazla mesai ücretinin toplam içindeki oranı |
| YOL / Yemek Ücreti Oranı | Benefits Ratio | Yol ve yemek ödeneği oranı |
| PRİM Ücreti Oranı | Bonus Ratio | Prim ve ek ödeme oranı |

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
