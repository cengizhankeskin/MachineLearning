# Machine Learning Eğitim Notları

Bu depo; Python, Jupyter Notebook ve yaygın veri bilimi kütüphaneleriyle hazırlanmış makine öğrenmesi eğitim notlarını, uygulamaları ve örnek veri kümelerini içerir.

## Konular

- Makine öğrenmesine giriş
- Basit ve çoklu doğrusal regresyon
- Polinom regresyon
- Ridge, Lasso ve Elastic Net
- Lojistik regresyon
- Support Vector Machines (SVM, SVC ve SVR)
- Hiperparametre çalışmaları ve pipeline kullanımı
- K-Nearest Neighbors (KNN)
- Sınıflandırma ve regresyon örnekleri

## Depo düzeni

- Numaralı `.ipynb` dosyaları konu anlatımı ve temel uygulamalardır.
- `Example` adını taşıyan notebook'lar ek uygulama örnekleridir.
- `.csv` ve `.xlsx` dosyaları notebook'larda kullanılan veri kümeleridir.

Notebook'ların veri dosyalarına verdiği göreli yolların bozulmaması için özgün dosya yerleşimi korunmuştur. Jupyter'ın otomatik oluşturduğu `.ipynb_checkpoints` dosyaları depoya dahil edilmemiştir.

## Kurulum

Anaconda Prompt veya bir terminal açıp aşağıdaki ortamı oluşturabilirsiniz:

```bash
conda create -n machine-learning python pandas numpy matplotlib seaborn scikit-learn openpyxl jupyterlab
conda activate machine-learning
jupyter lab
```

Ardından notebook'ları numaralarına göre veya ilgilendiğiniz örnekten başlayarak çalıştırabilirsiniz.

## Not

Bu depo eğitim ve uygulama amaçlıdır. Veri kümelerini farklı bir amaçla kullanmadan önce özgün kaynaklarının kullanım koşullarını kontrol edin.
