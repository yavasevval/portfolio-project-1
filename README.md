# Portfolyo Projem - 1
Bu projemin amacı, görüntü sınıflandırması, veri analizi ve derin öğrenme modellemesi konularında edindiğim bilgileri uygulamaktır. Projede temel derin öğrenme kavramları, veri ön işleme, model geliştirme ve performans değerlendirmesi, hiperparametre optimizasyonu ve heatmap görselleştirme gibi konulara odaklanılmıştır.

# Giriş
Bu projenin temelini oluşturan veri setini Kaggle üzerinden seçtim ve bu veri seti, kedi ve köpek görsellerinden oluşmaktadır. Bu veri seti, her biri kedi ve köpek görsellerinden oluşan yaklaşık 25.000 eğitim ve 12.500 test görseli içermektedir. Projenin teknik anlatımını ve tüm adımlarını, Kaggle notebook'umda, markdown formatındaki hücreler kullanarak detaylı bir şekilde anlattım.

# Metrikler
Çalışmamın sonucunda, modelimin performansını değerlendirmek için çeşitli metrikleri kullandım.

### Veri Ön İşleme ve Veri Çoğaltma: 
ImageDataGenerator kullanılarak görseller yeniden boyutlandırılmış, normalleştirilmiş ve modelin daha iyi genelleme yapması için rastgele döndürme, kaydırma ve yakınlaştırma gibi teknikler uygulanmıştır.

### CNN Mimarisi:
Model, evrişim (Convolutional), havuzlama (Pooling), dropout ve yoğun (Dense) katmanlarından oluşan özel bir CNN yapısıdır.

### Hiperparametre Optimizasyonu: 
Modelin performansını artırmak amacıyla farklı öğrenme oranları (1e-4 ve 1e-3) üzerinde denemeler yapılmıştır.

### Model Yorumlama: 
Modelin bir görseli sınıflandırırken hangi bölgelere odaklandığını göstermek için Grad-CAM görselleştirme tekniği kullanılmıştır.

## Kayıp (Loss):
Eğitim sürecinde modelimin hata oranı sürekli azaldı.

## Doğruluk (Accuracy):
Modeli farklı hiperparametrelerle eğittikten sonra, en iyi doğrulama doğruluğunu %84.70 olarak elde ettim. Bu sonuç, modelimin daha önce görmediği görselleri doğru bir şekilde sınıflandırabildiğini göstermektedir.

## Yorum: 
Bu projede, yalnızca kod yazmakla kalmayıp, hiperparametre optimizasyonu gibi adımlarla modelimin performansını nasıl artırabileceğimi de öğrendim ve bunu başarıyla gösterdim.

# Ekler
Projemin kalitesini artırmak amacıyla, modelimin bir görseli nasıl sınıflandırdığını anlamak için Grad-CAM görselleştirme tekniğini kullandım. Bu teknik, modelimin karar verirken görselin hangi bölgelerine odaklandığını gösteren bir ısı haritası (heatmap) oluşturarak, modelin yorumlanabilirliğini artırdı.

# Sonuç ve Gelecek Çalışmalar
Bu proje, derin öğrenme alanındaki temel yetkinliklerimi pekiştirmemi sağladı. Gelecekte bu projeyi daha da geliştirmeyi hedefliyorum. Örneğin, modeli daha büyük bir veri setiyle eğitebilir, farklı CNN mimarilerini (Transfer Learning) deneyebilir veya modelimi bir web uygulamasına entegre ederek gerçek zamanlı sınıflandırma yapabilirim.

# Link
Projenin tüm kodlarını ve detaylı teknik anlatımını içeren Kaggle notebook'umun linki aşağıdadır:

[[Kaggle Notebook'umun Linki](https://www.kaggle.com/code/yavasevval/dogs-vs-cats-proje-26-09-25)]










