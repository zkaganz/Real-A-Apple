# Real-Ai-Apple
Bu proje, elma görüntülerini sınıflandırmak için bir derin öğrenme modeli oluşturmayı amaçlamaktadır. Model, gerçek ve yapay elma görüntülerini ayırt etmek için VGG16 modeli üzerinde transfer öğrenme kullanmaktadır.

Proje Amacı
Bu projenin amacı, gerçek dünya uygulamalarında elma sınıflandırması yapmak için bir model geliştirmektir. Model, bir elma görüntüsünü alır ve görüntünün gerçek mi yoksa yapay mı olduğunu tahmin eder.

Gereksinimler
Bu kodun çalıştırılması için aşağıdaki Python kütüphanelerine ihtiyaç vardır:

tensorflow
keras
PIL
matplotlib
numpy
pandas
Gerekli kütüphaneleri yüklemek için aşağıdaki komutu kullanabilirsiniz:

Copy code
pip install tensorflow keras Pillow matplotlib numpy pandas
Veri Seti
Bu projede, gerçek ve yapay elma görüntüleri içeren bir veri seti kullanılmıştır. Veri seti, eğitim ve test klasörlerinde ayrılmış olarak bulunmaktadır. Eğitim klasöründe gerçek ve yapay elma görüntülerini içeren alt klasörler bulunur. Bu projede kullanılan veri seti, Kaggle'dan alınmıştır.
Veri setine şu bağlantıdan erişebilirsiniz. https://www.kaggle.com/datasets/osmankagankurnaz/dataset-of-ai-generated-fruits-and-real-fruits

Kullanım
Gerekli kütüphaneleri yükleyin.
Gerçek ve yapay elma görüntülerini içeren veri setini indirin ve uygun dizinlere yerleştirin.
Kodu çalıştırın.
Kod, VGG16 modelini kullanarak bir sınıflandırma modeli oluşturacak, eğitecek ve test edecektir. Ardından, bir görüntünün gerçek mi yoksa yapay mı olduğunu tahmin edecektir.
