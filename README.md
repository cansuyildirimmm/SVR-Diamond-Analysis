# 💎 Diamond Price Prediction (SVR)

This project aims to predict diamond prices based on various physical attributes using the popular **Kaggle Diamonds Dataset**. The model is built using **Support Vector Regression (SVR)** and optimized via **GridSearchCV**.

Bu proje, popüler **Kaggle Diamonds** veri setini kullanarak elmasların fiziksel özelliklerine göre fiyatlarını tahmin etmeyi amaçlamaktadır. Model, **Destek Vektör Regresyonu (SVR)** ile kurulmuş ve **GridSearchCV** ile optimize edilmiştir.

---

## 🚀 Project Overview / Proje Özeti

### English
In this notebook, I performed an end-to-end machine learning workflow:
* **Data Cleaning:** Handling missing values and exploring data structures.
* **EDA:** Visualizing correlations between features like carat, cut, clarity, and price.
* **Preprocessing:** Encoding categorical variables and feature scaling (StandardScaler).
* **Modeling:** Implementing `SVR` from Scikit-Learn.
* **Hyperparameter Tuning:** Finding the best `C`, `gamma`, and `epsilon` values using `GridSearchCV`.

### Türkçe
Bu çalışmada uçtan uca bir makine öğrenmesi iş akışı uygulanmıştır:
* **Veri Temizleme:** Eksik verilerin kontrolü ve veri yapısının incelenmesi.
* **EDA (Keşifçi Veri Analizi):** Karat, kesim, berraklık ve fiyat arasındaki ilişkilerin görselleştirilmesi.
* **Ön İşleme:** Kategorik verilerin dönüştürülmesi ve verilerin ölçeklendirilmesi (StandardScaler).
* **Modelleme:** Scikit-Learn kütüphanesi ile `SVR` modelinin kurulması.
* **Hiperparametre Optimizasyonu:** `GridSearchCV` kullanarak en iyi `C`, `gamma` ve `epsilon` değerlerinin belirlenmesi.

---

## 📊 Dataset / Veri Seti

The dataset contains nearly 54,000 diamonds with 10 features:
Veri seti yaklaşık 54.000 elmas ve 10 özellik içermektedir:

* **Carat:** Weight of the diamond. / Elmasın ağırlığı.
* **Cut:** Quality of the cut (Fair, Good, Very Good, Premium, Ideal). / Kesim kalitesi.
* **Color:** Diamond colour, from J (worst) to D (best). / Elmas rengi.
* **Clarity:** A measurement of how clear the diamond is. / Berraklık ölçüsü.
* **Dimensions:** x, y, z (length, width, depth in mm). / Boyutlar (uzunluk, genişlik, derinlik).
* **Price:** Target variable in US dollars. / Hedef değişken (ABD Doları).

---


### 📈 Results / Sonuçlar


The model performance was evaluated using MAE, MSE, and R² Score. Grid search helped significantly in reducing the error margins by finding the optimal SVR parameters.

Model performansı MAE, MSE ve R² Skoru kullanılarak değerlendirilmiştir. Grid search, optimum SVR parametrelerini bularak hata paylarının azaltılmasında önemli rol oynamıştır.

