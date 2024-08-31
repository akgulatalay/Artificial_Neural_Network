# Artificial_Neural_Network

## Proje Açıklaması: Müşteri Kaybı Analizi ve Yapay Sinir Ağları ile Çözüm Önerileri

**Giriş**

Bu proje, bir Avrupa bankasının müşteri kaybı sorununu anlamak ve yapay sinir ağları (ANN) kullanarak çözüm önerileri geliştirmeyi amaçlamaktadır. Banka tarafından sağlanan `Churn_Modelling.csv` isimli veri seti, 10.000 müşterinin demografik bilgilerini, bankacılık alışkanlıklarını ve müşteri kaybı durumlarını içermektedir. Veri setindeki değişkenler arasında müşteri ID, soyadı, kredi skoru, yaş, cinsiyet, müşterilik süresi, hesap bakiyesi, sahip olunan ürün sayısı, kredi kartı sahipliği, aktif müşteri durumu, tahmini maaş ve müşteri kaybı durumu yer almaktadır.

**Problem Tanımı**

Banka, son dönemde müşteri kaybında önemli bir artış yaşamıştır. Bu durum, hem gelir kaybına hem de rekabet gücünün zayıflamasına neden olmaktadır. Projenin temel amacı, müşteri kayıplarının nedenlerini belirlemek ve bu bilgilere dayanarak bankanın müşteri sadakatini artırmak için stratejiler geliştirmektir.

**Veri Analizi ve Hazırlık**

Projenin ilk aşamasında, veri seti detaylı bir şekilde analiz edilerek eksik ve tutarsız değerler tespit edilmiştir. Gerekli ön işleme işlemleri (eksik değerlerin doldurulması, aykırı değerlerin tespiti ve giderilmesi, veri dönüşümleri) gerçekleştirilmiştir. Daha sonra, verinin görselleştirilmesi ile değişkenler arasındaki ilişkiler ve dağılımlar incelenmiştir.

**Modelleme**

Müşteri kaybı durumunu tahmin etmek için yapay sinir ağları (ANN) kullanılmıştır. ANN modelinin tasarımı ve eğitimi aşamalarında farklı hiperparametreler denenmiş ve en iyi performansı gösteren model seçilmiştir.

**Sonuçlar ve Öneriler**

Eğitilen ANN modeli, müşteri kaybını belirli bir doğruluk oranında tahmin edebilmektedir. Modelin öne çıkardığı önemli faktörler, kredi skorları, yaşadıkları yer, müşterinin yaş, cinsiyet, müşterilik süresi, sahip olduğu ürün sayısı, kredi kartı sahipliği ve tahmini maaşı gibi değişkenlerdir. Bu sonuçlara dayanarak banka için aşağıdaki öneriler sunulmuştur:

* **Kişiselleştirilmiş Pazarlama:** Müşteri segmentlerine göre farklı pazarlama stratejileri geliştirilerek müşteri memnuniyeti artırılabilir.
* **Ürün Geliştirme:** Müşterilerin ihtiyaçlarına yönelik yeni ürün ve hizmetler sunularak müşteri sadakati güçlendirilebilir.
* **Müşteri İlişkileri Yönetimi:** Müşterilerle daha sıkı ilişkiler kurarak sorunlarını zamanında tespit etmek ve çözmek önemlidir.
* **Mali Analiz:** Müşteri kazanma ve elde tutma maliyetleri analiz edilerek karlılık odaklı bir yaklaşım benimsenmelidir.


**Sonuç**

Bu proje, yapay sinir ağlarının müşteri kaybı analizinde etkili bir araç olduğunu göstermiştir. Elde edilen sonuçlar, bankanın müşteri kaybını azaltmak ve rekabet gücünü artırmak için önemli bir başlangıç noktası olacaktır.

**Ek Bilgiler:**

* Python, TensorFlow, Numpy, Pandas, ScikitLearn programa dili ve kütüphaneleri kullanılmıştır.
* %86 lık bir doğruluk oranı yakalanmıştır
