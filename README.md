[EN]

# World Military Power Clustering Analysis

## Project Objective
The goal of this project is to analyze the military capabilities of countries around the world and group them using clustering techniques. The analysis uses military and economic indicators such as air power, submarine fleets, defense budgets, and manpower to identify differences and similarities in the military capacities of various nations.

## Dataset
The dataset includes a comprehensive range of parameters that reflect the military and economic strengths of countries. Some of these parameters include:

- Air power
- Number of fighter jets
- Helicopter fleet
- Number of tanks
- Submarine fleet
- Defense spending
- Population
- Geographic factors such as land and sea borders

These parameters are used to better understand the military capacity of each country.

## Libraries Used
The following Python libraries were used in this project:

- `pandas`: For data manipulation and analysis
- `numpy`: For numerical computations
- `scikit-learn`: For machine learning models (K-Means)
- `yellowbrick`: For visualization and Elbow method
- `seaborn` and `matplotlib`: For data visualization
- `scipy`: For hierarchical clustering and dendrograms

## Project Steps

1. **Data Loading and Preprocessing**  
   - The dataset is loaded from an Excel file.
   - Missing values are cleaned, and relevant columns are selected for the analysis.

2. **Data Normalization**  
   - `StandardScaler` is used to normalize the data, ensuring all features are on the same scale.

3. **Clustering Analysis**  
   - The `K-Means` algorithm is applied for clustering analysis.
   - The Elbow method is used to determine the optimal number of clusters.

4. **Results Visualization**  
   - The distribution of countries within clusters is visualized and analyzed.
   - A dendrogram is created for hierarchical clustering.

## Results
The project groups countries into clusters based on their military capacities. These clusters provide insights into the global military balance and enable deeper analysis of the defense capabilities of different nations.

[TR]

# World Military Power Clustering Analysis

## Proje Amacı
Bu projenin amacı, dünyanın çeşitli ülkelerinin askeri kapasitelerini analiz etmek ve bu ülkeleri kümeleme teknikleri kullanarak gruplamaktır. Analiz, hava gücü, denizaltı filoları, savunma bütçeleri ve insan gücü gibi askeri ve ekonomik göstergeleri kullanarak ülkelerin askeri kapasitelerindeki benzerlik ve farklılıkları ortaya çıkarmayı hedeflemektedir.

---

## Veri Seti
Veri seti, ülkelerin askeri ve ekonomik güçlerini yansıtan geniş bir parametre yelpazesini içermektedir. Bu parametrelerden bazıları şunlardır:

- Hava gücü
- Savaş uçağı sayısı
- Helikopter filosu
- Tank sayısı
- Denizaltı filosu
- Savunma harcamaları
- Nüfus
- Coğrafi faktörler (kara ve deniz sınırları)

Bu parametreler, her ülkenin askeri kapasitesini daha iyi anlamak için kullanılmıştır.

---

## Kullanılan Kütüphaneler
Projede aşağıdaki Python kütüphaneleri kullanılmıştır:

- `pandas`: Veri işleme ve analiz
- `numpy`: Sayısal hesaplamalar
- `scikit-learn`: Makine öğrenimi modelleri (K-Means)
- `yellowbrick`: Görselleştirme ve Elbow Method
- `seaborn` ve `matplotlib`: Veri görselleştirme
- `scipy`: Hiyerarşik kümeleme ve dendrogramlar

---

## Proje Adımları

1. **Veri Yükleme ve Ön İşleme**
   - Veri seti bir Excel dosyasından yüklendi.
   - Eksik değerler temizlendi ve analiz için ilgili sütunlar seçildi.

2. **Veri Normalizasyonu**
   - Tüm özelliklerin aynı ölçeğe getirilmesi için `StandardScaler` kullanıldı.

3. **Kümeleme Analizi**
   - K-Means algoritması kümeleme analizi için uygulandı.
   - Elbow Method kullanılarak optimum küme sayısı belirlendi.

4. **Sonuçların Görselleştirilmesi**
   - Kümelerdeki ülkelerin dağılımı görselleştirildi ve analiz edildi.
   - Hiyerarşik kümeleme için bir dendrogram oluşturuldu.

---

## Sonuçlar
Bu proje, ülkeleri askeri kapasitelerine göre kümelere ayırarak küresel askeri dengeler hakkında önemli içgörüler sunmaktadır. Bu kümeler, farklı ülkelerin savunma kapasitelerini daha derinlemesine analiz etmeye olanak tanımaktadır.
