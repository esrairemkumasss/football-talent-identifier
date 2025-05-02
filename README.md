
# Football Talent Identifier

Bu proje, genç ve potansiyeli yüksek futbolcuları tespit etmek amacıyla veri analizi kullanılan bir Python projesidir. FIFA 21 oyuncu verileri kullanılarak keşfedilmemiş yetenekler belirlenmiş ve analiz edilmiştir.

## 📁 Proje Yapısı

```
football-talent-identifier/
│
├── data/                      # Veriseti ve çıktı dosyaları
│   └── players_21.csv
│   └── genclik_yetenek_listesi.csv
├── analysis.ipynb            # Ana analiz dosyası
└── README.md                 # Proje açıklaması
```

## 📊 Kullanılan Veri

- **Veri seti:** `players_21.csv` (FIFA 21 veriseti)
- **Kaynak:** [Kaggle - FIFA 21 complete player dataset](https://www.kaggle.com/datasets/stefanoleone992/fifa-21-complete-player-dataset)

## 🔍 Amaç

- Potansiyeli yüksek genç futbolcuları belirlemek
- Kulüplerin bu oyunculara göre sıralamasını çıkarmak
- Verileri görselleştirmek

## 📈 Analiz Adımları

1. Veriyi yükleme ve filtreleme
2. Potansiyel & yaş kriterlerine göre sıralama
3. Genç (21 yaş altı) ve potansiyeli 85+ olan oyuncuların seçimi
4. Görselleştirme ile analiz sonuçlarının sunulması
5. Çıktının `.csv` formatında kaydedilmesi

## 🧰 Kullanılan Kütüphaneler

- `pandas`
- `matplotlib`
- `seaborn`
- `os`

## 📦 Kurulum

```bash
pip install pandas matplotlib seaborn
```

## 🖼️ Örnek Görselleştirme

![Örnek Grafik](path/to/screenshot.png)

## 📁 Çıktı

- `data/genclik_yetenek_listesi.csv`: Genç ve potansiyelli oyuncuların listesi

## ✍️ Katkı

Katkı yapmak isterseniz PR (pull request) gönderebilirsiniz.
