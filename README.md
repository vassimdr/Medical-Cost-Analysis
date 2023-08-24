# Medical-Cost-Analysis
Bu proje, sağlık sigortası maliyetini tahmin etmek için veri bilimi tekniklerini kullanmayı amaçlamaktadır. Veri seti olarak Kaggle'dan elde edilen "Insurance" veri setini kullanmaktayız.

## İçindekiler
Keşifsel Veri Analizi (EDA) <br>
Veri Ön İşleme<br>
Model Seçimi<br>
Hiper-parametre Optimizasyonu<br>
Model Değerlendirme<br>

## Keşifsel Veri Analizi (EDA)
Veri setini detaylı bir şekilde inceledik ve ilgi çekici bulgulara ulaştık:<br>

BMI dağılımını inceleyerek sağlık profili hakkında fikir edindik.<br>
Sigara içenlerin maliyetlerinin, içmeyenlere göre daha yüksek olduğunu belirledik.<br>
Sigara içenlerin bölgelere göre dağılımını harita ile görselleştirdik.<br>
Cinsiyet ile BMI arasındaki ilişkiyi violin plot ile gösterdik.<br>
En fazla çocuğa sahip bölgenin, sağlık hizmeti ihtiyacını etkileyebileceğini analiz ettik.<br>

## Veri Ön İşleme
Veriyi işlemeye alarak modelleme için uygun hale getirdik:<br>

Kategorik değişkenleri etiket kodlama ve tekil kodlama ile dönüştürdük.<br>
Veriyi eğitim ve test kümelerine ayrıldık ve böylece modelin genelleme yeteneğini sağladık.<br>
Veriyi Min-Maks ölçekleme yöntemiyle ölçeklendirdik, böylece farklı özelliklerin ağırlığı dengelendi.<br>


## Model Seçimi
Çeşitli regresyon modelleri kullanarak maliyet tahminini gerçekleştirdik:<br>

Lineer Regresyon: Temel bir model olarak kullandık.<br>
Karar Ağaçları: Veri içindeki karar noktalarını analiz ettik.<br>
Rastgele Orman: Ağaç tabanlı bir model olarak en iyi performansı gösterdi.<br>

## Hiper-parametre Optimizasyonu
En iyi performans gösteren model için hiper-parametre optimizasyonu yaptık:<br>

Rastgele Orman modelinin hiper-parametrelerini Grid Search yöntemiyle ayarladık.<br>
En iyi parametreleri seçerek modelin performansını artırdık.<br>


## Model Değerlendirme

Optimize edilmiş modeli test verileri üzerinde değerlendirdik:<br>

Modelin tahminleri ile gerçek değerleri karşılaştırarak ortalama kare hata (MSE) ve ortalama mutlak hata (MAE) hesapladık.<br>
Modelin R2 skoru ile maliyet tahmini konusundaki başarısını nicel olarak değerlendirdik.<br>

