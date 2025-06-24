# ✈️ Yolcu Memnuniyeti Analizi

Bu proje, bir havayolu firmasına ait yolcu memnuniyeti verilerini kullanarak, yolcuların memnuniyet durumunu etkileyen faktörleri analiz etmeyi amaçlamaktadır.

## 📁 Veri Seti

Veri seti; yolcuların cinsiyeti, yaşı, uçuş mesafesi, uçuş sınıfı, gecikme süreleri ve uçuş deneyimiyle ilgili çeşitli hizmetlerden duydukları memnuniyet seviyelerini içermektedir. Veri kümesi ikiye ayrılmıştır:

- `train.csv`
- `test.csv`

## 🔍 Uygulanan Adımlar

1. **İstatistiksel Özet:**
   - Ortalama, medyan, varyans, mod gibi temel istatistikler hesaplandı.

2. **Eksik Değer Analizi:**
   - Eksik değerler belirlendi ve uygun yöntemle dolduruldu.

3. **Aykırı Değer Analizi:**
   - IQR yöntemi ile uç değerler belirlendi.
   - Boxplot görselleştirmeleriyle desteklendi.

4. **Veri Görselleştirme:**
   - Kategorik değişkenler için countplot,
   - Sayısal değişkenler için histogram, boxplot ve barplot kullanıldı.

5. **Hedef Değişken ile İlişki İncelemesi:**
   - "Satisfaction" değişkeni ile diğer değişkenler arasındaki ilişkiler değerlendirildi.
   - Sayısal değişkenler için barplot, kategorik değişkenler için countplot analizleri yapıldı.

## 📌 Kullanılan Kütüphaneler

- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`

## 🗨️ Sonuç

Yapılan analizler, yolcu memnuniyetini en çok etkileyen faktörlerin uçuş sınıfı, uçuş mesafesi, gecikme süreleri ve yaş olduğunu göstermektedir. Proje süresince temel veri analizi teknikleriyle birlikte istatistiksel yorumlama ve görselleştirme becerileri de geliştirilmiştir.


Veri Analizi Bootcamp | Kız Başına

