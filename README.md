# TomatoDiseaseAI

Bu proje, yapay zeka ve derin öğrenme yöntemlerini kullanarak domates yapraklarındaki hastalıkları sınıflandırmak için geliştirilmiştir. **DenseNet121** mimarisi tabanlı bir model eğitilmiş ve %94 doğruluk oranıyla yüksek bir başarı elde edilmiştir.

## Projenin Amacı
Tarım sektöründe ürün kayıplarını en aza indirmek ve verimliliği artırmak için domates yapraklarındaki hastalıkların erken teşhisini sağlamak.

## Kullanılan Teknolojiler
- **Python**: Proje geliştirme dili
- **Keras & TensorFlow**: Modelin oluşturulması ve eğitilmesi
- **Matplotlib**: Eğitim sonuçlarının görselleştirilmesi
- **DenseNet121**: Transfer öğrenme tabanlı derin öğrenme modeli

## Veri Seti
Proje, her biri **1000 eğitim** ve **100 test** görüntüsüne sahip 10 farklı domates hastalığı türü ile çalışmaktadır:

- **Bacterial Spot (Bakteriyel Leke)**
- **Early Blight (Erken Yanıklık)**
- **Healthy (Sağlıklı)**
- **Late Blight (Geç Yanıklık)**
- **Leaf Mold (Yaprak Küfü)**
- **Septoria Leaf Spot (Septoria Yaprak Lekesi)**
- **Spider Mites (Two-Spotted) (İki Noktalı Kırmızı Örümcek)**
- **Target Spot (Hedef Leke)**
- **Tomato Mosaic Virus (Domates Mozaik Virüsü)**
- **Tomato Yellow Leaf Curl Virus (Domates Sarı Yaprak Kıvırcık Virüsü)**

## Model Eğitimi
Model, **DenseNet121** mimarisi ve transfer öğrenme yöntemleriyle eğitildi. Aşağıdaki optimizasyon algoritmaları ve parametreler kullanıldı:

- **Giriş Boyutu**: 224x224 piksel
- **Optimizasyon Algoritması**: Adam
- **Kayıp Fonksiyonu**: Categorical Crossentropy
- **Epoch Sayısı**: 25

### Eğitim Sonuçları
- **Doğruluk**: %94

## Eğitim ve Doğrulama Grafikleri
Eğitim sürecinin analizine yönelik kayıp ve doğruluk grafikleri proje kapsamında oluşturulmuştur:

1. **Eğitim ve Doğrulama Kayıpları**
2. **Eğitim ve Doğrulama Doğrulukları**
3. **Eğitim ve Doğrulama Kayıpları (Aynı Grafik)**

Grafiklerin detayları, 
![image](https://github.com/user-attachments/assets/f2d94287-72dc-4753-a227-ef396563accf)
![image](https://github.com/user-attachments/assets/050fd9c6-c187-4950-9dad-8571eb1ad111)




## Kurulum ve Kullanım

1. Bu projeyi bilgisayarınıza klonlayın:
   ```bash
   git clone https://github.com/kullaniciadi/TomatoDiseaseAI.git
   cd TomatoDiseaseAI
