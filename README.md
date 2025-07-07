# Veri Bilimi Çalışması: Keşifsel Analiz & Makine Öğrenmesi

Bu Jupyter Notebook projesi, iki farklı veri bilimi senaryosunu bir arada sunar:

1. **Titanic Veri Keşfi (EDA)**  
   Titanic yolcu verileri üzerinde veri yükleme, temizleme ve keşifsel analiz  
2. **Palmer Penguins Sınıflandırması (Machine Learning)**  
   Penguenlerin biyometrik özellikleriyle tür sınıflandırması için veri ön işleme, görselleştirme ve Decision Tree modeli

---

## 📁 Dosya Düzeni

- `veri bilimi.ipynb`  
  Tüm adımların yer aldığı Jupyter Notebook.  
- `titanic.csv`  
  Kaggle’dan alınmış Titanic yolcu verileri.  
- `penguins_size.csv`  
  Palmer Penguins veri seti (boyut ve tür bilgileri).

---

## 🛠️ Kullanılan Kütüphaneler

- **pandas, numpy** — Veri yükleme, temizleme, dönüştürme  
- **matplotlib, seaborn** — Statik ve istatistiksel görselleştirmeler  
- **scikit-learn** — `train_test_split`, `DecisionTreeClassifier`, `confusion_matrix`, `classification_report`, `accuracy_score`  
- **Jupyter Notebook** — İnteraktif kod ve açıklamalar  

---

## 🚀 Kurulum ve Çalıştırma

1. Ortamı hazırlayın ve gerekli paketleri yükleyin:  
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn jupyter
