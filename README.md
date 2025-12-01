# Vehicle Classifier with PyTorch

Bu proje, **PyTorch** kullanarak araç sınıflandırması yapan bir derin öğrenme modelini içerir.  
CIFAR-10 benzeri bir veri seti yerine kendi araç veri setinizi kullanabilirsiniz.

## Özellikler
- CNN tabanlı model (4 Convolutional Block + 2 Fully Connected Layer)
- Veri artırma (Random Rotation, Horizontal Flip, Color Jitter)
- Eğitim ve doğrulama grafikleri
- GPU destekli eğitim
- Model kaydetme (`vehicle_classifier.pth`)

## Kurulum
```bash
git clone <repository-url>
cd <repository-name>
pip install -r requirements.txt
