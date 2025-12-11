# Atölye_VB — Bitirme Projesi

Bu repo, TechCareer Veri Bilimi Atölyesi kapsamında gerçekleştirilen **Veri Görselleştirme Bitirme Projesi**ni içermektedir. Proje kapsamında, *50_Startups.csv* veri seti kullanılarak temel veri analizi (EDA) ve veri görselleştirme adımları uygulanmıştır. Çalışma, Jupyter Notebook üzerinde yürütülmüş ve veri ile ilgili çıkarımlar grafiklerle desteklenmiştir.

---

## İçindekiler

* [Projenin Amacı](#projenin-amacı)
* [Özellikler](#özellikler)
* [Kullanılan Teknolojiler](#kullanılan-teknolojiler)
* [Veri Seti](#veri-seti)
* [Notebooks](#notebooks-içerik-açıklaması)
* [Çalıştırma ve Kurulum (Adım Adım)](#çalıştırma-ve-kurulum-adım-adım)
* [Reprodüksiyon (Sonuçları Tekrarlama)](#reprodüksiyon-sonuçları-tekrarlama)
* [Proje Yapısı](#proje-yapısı)
* [Geliştirme ve Katkıda Bulunma](#geliştirme-ve-katkıda-bulunma)
* [Lisans](#lisans)

---

## Projenin Amacı

Bu projenin amacı, **50 Startups** veri seti üzerinde veri görselleştirme tekniklerini uygulayarak değişkenler arasındaki ilişkileri analiz etmektir. Özellikle:

* Harcama kalemlerinin kâr ile ilişkisi
* Eyalet bazlı kâr farklılıkları
* Veri dağılımlarının grafiklerle incelenmesi

gibi konular ele alınmıştır.

Proje, veri biliminin temel aşamalarından olan veri hazırlama, analiz ve görselleştirme adımlarını öğretici bir formatta sunar.

---

## Özellikler

* Jupyter Notebook formatında detaylı anlatım
* Scatter plot, bar chart ve boxplot görselleri
* Değişkenler arasındaki ilişkilerin görsel analizi
* Eyalet bazlı ortalama kâr karşılaştırmaları
* Temel EDA fonksiyonlarının kullanımı

---

## Kullanılan Teknolojiler

**Python Sürümü:** 3.8+

**Kütüphaneler:**

* pandas
* numpy
* matplotlib
* seaborn (opsiyonel)

**Ortam:**

* Jupyter Notebook / JupyterLab

---

## Veri Seti

Projede kullanılan veri seti: **50_Startups.csv**

Veri setinde bulunan değişkenler:

| Değişken        | Açıklama                  |
| --------------- | ------------------------- |
| R&D Spend       | Ar-Ge harcamaları         |
| Administration  | Yönetim harcamaları       |
| Marketing Spend | Pazarlama harcamaları     |
| State           | Şirketin bulunduğu eyalet |
| Profit          | Elde edilen kâr           |

Bu veri seti, startup harcamalarının kârlılıkla ilişkisini analiz etmek için uygundur.

---

## Notebooks (İçerik Açıklaması)

### **Veri_Görselleştirme_odevi.ipynb**

Bu not defteri aşağıdaki görevleri içerir:

1. **R&D Spend – Profit ilişkisinin scatter plot ile gösterilmesi**
2. **Administration – Profit ilişkisinin scatter plot ile gösterilmesi**
3. **State bazlı ortalama kâr değerlerinin bar chart ile görselleştirilmesi**
4. **R&D, Administration ve Marketing harcamalarının boxplot ile karşılaştırılması**

Her görevde grafikler oluşturulmuş ve kısaca yorumlanmıştır.

---

## Çalıştırma ve Kurulum (Adım Adım)

### 1) Depoyu klonlayın

```bash
git clone https://github.com/Bugraozdemir/Atolye_VB-Bitirme-Projesi.git
cd Atolye_VB-Bitirme-Projesi
```

### 2) Sanal ortam oluşturun (Önerilir)

```bash
python -m venv venv
source venv/bin/activate      # macOS / Linux
venv\Scripts\activate         # Windows
```

### 3) Gerekli kütüphaneleri yükleyin

```bash
pip install pandas numpy matplotlib seaborn notebook
```

### 4) Notebook’u başlatın

```bash
jupyter notebook
```

### 5) Notebook'u açın

`Veri_Görselleştirme_odevi.ipynb` dosyasını açarak hücreleri sırayla çalıştırın.

---

## Reprodüksiyon (Sonuçları Tekrarlama)

Aynı sonuçları tekrar elde etmek için:

1. Aynı Python sürümü ile bir ortam oluşturun
2. *50_Startups.csv* dosyasını proje dizinine ekleyin
3. Notebook’u baştan sona çalıştırın
4. Grafiklerin generation adımlarını inceleyin

---

## Proje Yapısı

```
.
├── Veri_Görselleştirme_odevi.ipynb
├── 50_Startups.csv
└── README.md
```

İsteğe bağlı olarak `images/` klasörü eklenerek grafik çıktıları kaydedilebilir.

---

## Geliştirme ve Katkıda Bulunma

Bu proje eğitim amaçlıdır.
Dilerseniz:

* Ek grafikler ekleyebilir
* Veri setini genişletebilir
* Modelleme adımları ekleyebilir
* Dashboard / rapor formatına dönüştürebilirsiniz

Katkılar için pull request açmanız yeterlidir.

---

## Lisans

Bu proje, TechCareer Veri Bilimi Atölyesi kapsamında eğitim amacıyla hazırlanmıştır. Özel bir lisans belirtilmemiştir.
