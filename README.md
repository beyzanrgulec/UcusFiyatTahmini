# Uçuş Analizi ve Tahmin Projesi

Bu proje, havayolu operasyonlarıyla ilgili verilere dayanarak uçuş analizleri yapmayı ve belirli uçuş özelliklerine göre tahmin modelleri geliştirmeyi amaçlamaktadır. Projede veri görselleştirme, keşifçi veri analizi (EDA) ve makine öğrenimi yöntemleri uygulanmıştır.

---

## Veri Seti Hakkında

Veri seti, uçuşlarla ilgili çeşitli temel özelliklere odaklanarak, havayolu operasyonlarının kapsamlı bir görünümünü sunar. Aşağıdaki bilgileri içerir:

- **Havayolu**: Uçağı işleten havayolu şirketi.
- **Kalkış ve Varış Şehirleri**: Uçuşun başladığı ve bittiği şehirler.
- **Toplam Durak Sayısı**: Uçuşların yaptığı durak sayısı.
- **Fiyat**: Uçuşun bilet fiyatı.
- **Uçuş Tarihleri**: Uçuşun gerçekleştiği tarih, ay ve yıl.
- **Kalkış ve Varış Saatleri**: Uçuşun kalkış ve varış saatleri.
- **Süre**: Uçuş süresi.

**Veri Kaynağı**: [Kaggle, https://www.kaggle.com/datasets/viveksharmar/flight-price-data]

---

## Proje Özeti

- **Amaç**:
  - Uçuş fiyatlarını etkileyen faktörleri analiz etmek.
  - Makine öğrenimi kullanarak uçuş fiyatlarını tahmin etmek.
- **Yaklaşım**:
  - Keşifçi veri analizi (EDA) ile içgörüler elde etme.
  - K-Means
  - Havayolu endüstrisindeki maliyet ve yolcu davranışı trendlerini anlama.

---

## Kullanılan Araçlar ve Teknolojiler

- **Programlama Dili**: Python
- **Kütüphaneler**:
  - Pandas
  - NumPy
  - Matplotlib
  - Seaborn
  - Scikit-learn
- **Makine Öğrenimi Teknikleri**:
  -K-Means
  





## Kurulum

Projeyi çalıştırmak için aşağıdaki adımları izleyin:

1. Bu projeyi klonlayın:
   ```bash
   git clone https://github.com/beyzanrgülec/ucus-analizi.git

