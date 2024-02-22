# Explainable Shoes Project


Bu proje, ayakkabı görüntülerini sınıflandırmak için derin öğrenme modelleri (ResNet50 ve Vgg16) kullanılarak gerçekleştirilmiştir. Ayrıca, modelin tahminlerini yorumlamak için GradCAM ve Layer-wise Relevance Propagation (LRP) gibi görselleştirme tekniklerinin kullanımı sağlanarak, modelin tahminlerinin hangi piksel değerlerine odaklandığı gösterilmiş ve modelin açıklanabilirliği sağlanmıştır.

## ResNet50 ile Explainable Shoes Project

Bu projede, 3 farklı ayakkabı markasını ResNet50 modeline eğitmek ve sınıflandırmak için derin öğrenme yöntemleri kullanılmıştır. Ayrıca, modelin doğruluğunu GradCAM gibi yöntemlerle görselleştirerek, modelin doğru sonuçları doğru bir şekilde tespit edip etmediği görsterilmiştir.

### Proje Amacı

Bu projenin temel amacı, ayakkabı görüntülerini doğru bir şekilde sınıflandırmak ve modelin tahminlerini yorumlanabilir hale getirmektir.

### Kullanılan Teknolojiler

- PyTorch: Model oluşturmak, eğitmek ve değerlendirmek için kullanılmıştır.
- torchvision: Önişleme ve veri yükleme işlemleri için kullanılmıştır.
- pytorch-grad-cam: GradCAM yöntemini kullanarak model tahminlerini görselleştirmek için kullanılmıştır.
- NumPy: Veri manipülasyonu için kullanılmıştır.
- Matplotlib ve seaborn: Sonuçları görselleştirmek için kullanılmıştır.

### Veri Seti

Veri seti, Kaggle platformundan alınmış ve manuel olarak etiketlenmiştir. Veri seti, eğitim ve test olarak iki bölüme ayrılmıştır. Eğitim veri seti modelin öğrenmesi için kullanılmış, test veri seti ise modelin performansının değerlendirilmesi için ayrılmıştır.

### Sonuçlar

- Karışıklık Matrisi: Modelin sınıflandırma performansını görselleştirmek için bir karışıklık matrisi oluşturulmuştur.
- GradCAM Görselleştirmeleri: Modelin sınıflandırma yaparken odaklandığı bölgeleri görselleştirmek için GradCAM tekniği kullanılmıştır.
- <img src="https://github.com/AbdulbariSoylemez/ExplainableShoesProject/blob/main/ResNetCikti/Resnet50output2.png" alt="Description">

## Vgg16 ile Explainable Shoes Project

Bu projede, ayakkabı görüntülerini sınıflandırmak için Vgg16 modeli kullanılmıştır. Ayrıca, GradCAM ve Layer-wise Relevance Propagation (LRP) gibi görselleştirme tekniklerinin kullanımıyla modelin tahminlerinin yorumlanabilirliği sağlanmıştır.

### Proje Amacı

Bu projenin amacı, ayakkabı görüntülerini farklı sınıflara doğru sınıflandırmak ve modelin tahminlerini yorumlanabilir hale getirmektir.

### Kullanılan Teknolojiler

- PyTorch: Model oluşturmak, eğitmek ve değerlendirmek için kullanılmıştır.
- torchvision: Önişleme ve veri yükleme işlemleri için kullanılmıştır.
- matplotlib: Sonuçları görselleştirmek için kullanılmıştır.
- NumPy: Veri manipülasyonu için kullanılmıştır.
- pandas: Veri işleme ve analizi için kullanılmıştır.
- sklearn.metrics: Model performansını değerlendirmek için kullanılmıştır.
- copy: Modelin kopyasını oluşturmak için kullanılmıştır.

### Veri Seti

Veri seti, eğitim ve test olarak iki bölüme ayrılmıştır. Eğitim veri seti modelin öğrenmesi için kullanılmış, test veri seti ise modelin performansının değerlendirilmesi için ayrılmıştır.

### Sonuçlar

- Karışıklık Matrisi: Modelin sınıflandırma performansını görselleştirmek için bir karışıklık matrisi oluşturulmuştur.
- GradCAM Görselleştirmeleri: Modelin sınıflandırma yaparken odaklandığı bölgeleri görselleştirmek için GradCAM tekniği kullanılmıştır.
<img src="https://github.com/AbdulbariSoylemez/ExplainableShoesProject/blob/main/VggCikti/Vgg16output2.png" alt="Description">


