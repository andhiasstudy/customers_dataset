# 📊 E-Commerce Data Analysis Dashboard ✨

## 📌 Deskripsi

Dashboard ini merupakan proyek akhir dari analisis dataset E-Commerce (Olist) di Brasil.
Proyek ini mencakup proses:

* Data Wrangling
* Exploratory Data Analysis (EDA)
* Geospatial Analysis

Tujuannya untuk memahami:

* Performa produk
* Kepuasan pelanggan
* Distribusi geografis pengguna

---

## 📂 Struktur Proyek

```bash
.
├── dashboard.py
├── Salinan_Proyek_Analisis_Data (1).ipynb
├── requirements.txt
├── README.md
├── url.txt
```

---

## ⚙️ Instalasi & Menjalankan

### 1. Clone Repository

```bash
git clone <repository-url>
cd <nama-folder>
```

---

### 2. Setup Environment (Anaconda)

```bash
conda create --name main-ds python=3.9
conda activate main-ds
pip install -r requirements.txt
```

---

### 3. Alternatif Setup (Terminal / pipenv)

```bash
pip install pipenv
pipenv install
pipenv shell
pip install -r requirements.txt
```

---

### 4. Menjalankan Dashboard

```bash
streamlit run dashboard/dashboard.py
```

Jika terjadi error:

```bash
streamlit run "path/dashboard.py"
```

---

## 📊 Dataset

Dataset yang digunakan adalah dataset E-Commerce publik dari Olist (Brasil), yang mencakup:

* Customer
* Orders
* Products
* Sellers

---

## 📄 Catatan

* Pastikan file `all_data.csv` berada di dalam folder `dashboard/`
* Jangan gunakan path absolut seperti `C:/Users/...`
* Gunakan path relatif agar dapat berjalan di semua environment

---

## 🌐 Demo

Link dashboard dapat dilihat pada file `url.txt`

---

## 👤 Author

Andhias Abdillah Ridho

---

## ©️ Copyright

Project ini dibuat untuk keperluan submission Dicoding.
