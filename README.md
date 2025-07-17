# Aİ PROJECT

### Kurulumlar
- [x] **LibTorch C++** - PyTorch C++
- [x] **Matplot++** - grafik kütüphanesi
- [x] **CUDA** - GPU hızlandırma
- [x] **cuDNN** - Öğrenme için CUDA kütüphanesi

### ANN Modelleri
- [x] **Multiclass Classification** - Çok sınıflı sınıflandırma
- [x] **Binary Classification** - İkili sınıflandırma  
- [x] **Regression** - Regresyon

## Dosya Yapısı

```
aiprojectcpp/
├── main.cpp                 
├── CMakeLists.txt        
├── README.md             
└── matplotplusplus/      
```


- ANN modellerini test eder
- grafiklerini oluşturur
- sonuçları PNG dosyaları olarak kaydeder



Program çalıştığında şu grafikler oluşturulur:

- `multiclass_loss.png` - Çok sınıflı sınıflandırma loss grafiği
- `loss_binary.png` - İkili sınıflandırma loss grafiği  
- `loss_regression.png` - Regresyon loss grafiği
- `loss_multiclass.png` - Regresyon tahmin vs gerçek değerler
- `iris_loss.png` - dataset loss grafiği

örnek terminal
```
CUDA var
Epoch sayısı: 50
Gizli katman boyutu: 64
Learning rate: 0.001
Binary Classification (Churn) Accuracy: 0.8137
Regression (TotalCharges) MSE: 435.22
Multiclass Classification (PaymentMethod) Accuracy: 0.6549
```


### 1. **Multiclass Classification**
- Birden fazla sınıfı sınıflandırma
- Cross-entropy loss kullanımı
- Accuracy hesaplama

### 2. **Binary Classification** 
- İki sınıf arasında ayrım
- Binary cross-entropy loss
- Sigmoid aktivasyon fonksiyonu

### 3. **Regression**
- Sürekli değer tahmini
- Mean squared error loss
- Linear regression

