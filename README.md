# 📊 Customer Analysis Dashboard

Dashboard interaktif untuk menganalisis distribusi pelanggan berdasarkan kota dan state menggunakan Streamlit.

---

## 👤 Informasi Proyek

* **Nama**: Andhias Abdillah Ridho
* **Email**: [cdcc001d6y1194@student.devacademy.id](mailto:cdcc001d6y1194@student.devacademy.id)
* **ID Dicoding**: CCDC001D6Y1194

---

## 🎯 Tujuan Analisis

Proyek ini bertujuan untuk menjawab pertanyaan bisnis berikut:

1. Kota mana yang memiliki jumlah pelanggan unik terbanyak?
2. Bagaimana distribusi pelanggan di setiap state?
3. State mana yang memiliki kontribusi pelanggan terbesar?

---

## 📁 Struktur Proyek

```
project_dashboard/
│
├── dashboard.py        # File utama Streamlit
├── all_data.csv        # Dataset hasil preprocessing
└── README.md           # Dokumentasi proyek
```

---

## ⚙️ Instalasi

Pastikan Python sudah terinstall, lalu install library berikut:

```
pip install streamlit pandas matplotlib seaborn babel
```

---

## ▶️ Menjalankan Dashboard

Jalankan perintah berikut di terminal:

```
streamlit run dashboard.py
```

Dashboard akan terbuka di browser pada:

```
http://localhost:8501
```

---

## 📊 Fitur Dashboard

* 📌 Filter data berdasarkan state
* 📈 Total pelanggan unik
* 🏙️ Top 10 kota dengan pelanggan terbanyak
* 🗺️ Distribusi pelanggan per state
* 📋 Tabel data mentah

---

## 📌 Insight Utama

* Beberapa kota memiliki jumlah pelanggan yang jauh lebih tinggi dibandingkan kota lainnya
* Distribusi pelanggan antar state tidak merata
* Terdapat peluang ekspansi di state dengan jumlah pelanggan rendah

---

## 🚀 Rekomendasi

* Fokuskan strategi pemasaran pada kota dengan pelanggan terbanyak
* Optimalkan performa di state dengan kontribusi tinggi
* Lakukan ekspansi ke wilayah dengan potensi pertumbuhan

---

## 🛠️ Tools yang Digunakan

* Python
* Streamlit
* Pandas
* Matplotlib
* Seaborn

---

## 📄 Catatan

Pastikan file `customers_dataset.csv` berada di folder yang sama dengan `dashboard.py` sebelum menjalankan aplikasi.

---

## ©️ Copyright

Dashboard ini dibuat untuk keperluan submission Dicoding.
