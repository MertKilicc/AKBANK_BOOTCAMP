# AKBANK_BOOTCAMP

proje için gerekli kütüphaneleri indirmek ilk adımım oldu daha sonra kullanacağım datayı çağırıp içerdiği sınıflara göz attım 
daha sonra görüntü dosylarını ve görüntü dosyalarının hangi balık türüne ait olduğunu kaydetmek için iki sınıf oluşturdum ve pandas kütüphanesi içerisine yerleştiridm
sonra veri tipimi ve yapımı görebilmek adına bazı keşifsel veri analizi adımları kullandım daha sonrasında da her bir balık sınıfına ait ilk fotoğrafı görüntüleyerek 
data hakkında daha fazla fikir sahibi oldum 
modelimi kurmadan önce daha iyi öğrenebilmesi adına her bir pikseli 255 e böldüm ve 0-1 aralığına çektim 
aynı kod satırında da verimi %20 si validation %80 i eğitim seti olmak üzere 2 parçaya böldüm 
one - hot encoding - eğitim veri setimdeki her bir sınıfa karşılık gelen indeks ssayılarımı gördüm

keras kullanarak bir ANN modeli oluşturdum 
sequentinal modülünukullanarak katmanlarımın sıralı bir yapı olduğunu tanımladım 
görüntülerimin boyutlarını biliyordum bunları kullanarak flatten koduyla tek boyutlu bir vektör haline getirdim 
Dense kullandım ve modelime bir girdi katmanı iki gizli katman ve bir çıkış katmanıyla oluşturdum 
aktivasyon fonksiyonu olaraksa Relu kullandım Relu sıfırdan küçük olan değerleri 0 olarak yazar sıfırdan büyük değerleri ise olduğu gibi bırakan bir fonksiyondur
çıkış katmanımda ise softmax kullandım softmax fonksiyonu çok sınıflı sınıflandırma fonksiyonlarında kullanılıyor
20 epochsluk bir seriyle modelimi eğitmeye başladım eğitim sonucunda
Validation loss: 0.9959872364997864
Validation accuracy: 0.7630555629730225   olarak buldum
daha sonra grafikleri ve model doğruluğunu gösterdim 
sonuçlar pek istediğim gibi çıkmasada bu projede kendimi gerçekten çokca geliştirdiğimi düşünüyorum emeği geçen herkese teşekkürler....




https://www.kaggle.com/code/lucimert/bootcamp
https://github.com/MertKilicc/AKBANK_BOOTCAMP/blob/main/bootcamp.ipynb
