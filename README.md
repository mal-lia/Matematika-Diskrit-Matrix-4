# Matematika-Diskrit-Matrix-4
Codescript mensimulasikan 500 pola konsumsi makanan selama 31 hari dengan anggaran Rp1.000.000. Setiap pilihan makanan dihitung berdasarkan atribut kenyang, rasa, sehat, dan bosan. Hasilnya dianalisis untuk menemukan pola makan paling optimal, menghitung makanan favorit, serta memvisualisasikan hubungan antara kesehatan, kepuasan, dan pengeluaran.

# Penugasan Sebelumnya:
* (Matriks 03) - https://github.com/mal-lia/Matematika-Diskrit-Matrix-3
* (Matriks 02) - https://github.com/mal-lia/Matematika-Diskrit-Matrix-2
* (Matriks 01) - https://github.com/mal-lia/Matematika-Diskrit-Matrix

---

# 🍽️ Simulasi Pola Konsumsi Makanan
Proyek ini merupakan Penugasan Mata Kuliah Matematika Diskrit (MATDIS) untuk simulasi pola konsumsi makanan menggunakan **Matematika Diskrit** dan **Python**.  
Tujuannya adalah mencari pola makan yang **sehat, memuaskan, dan hemat biaya** berdasarkan atribut makanan yang tersedia.

---

## 📌 Deskripsi
- Data awal diambil dari file `makanan.csv` lalu ditambahkan variasi menu baru.
- Setiap makanan memiliki atribut: **harga, rasa, sehat, kenyang, bosan**.
- Simulasi dilakukan sebanyak **500 pola makan selama 31 hari**, dengan asumsi:
  - Setiap hari makan **2 kali** (pagi & malam).
  - Anggaran total: **Rp 1.000.000**.
- Evaluasi dilakukan untuk menghitung:
  - **Skor total** (gabungan kenyang, rasa, sehat, bosan).
  - **Skor kesehatan**.
  - **Sisa anggaran**.
- Analisis tambahan:
  - Pola makan terbaik.
  - Makanan favorit.
  - Korelasi kesehatan, skor, dan uang.
- Visualisasi hasil dalam bentuk:
  - Histogram distribusi kesehatan.
  - Scatter plot (hubungan pengeluaran & skor).
  - 3D surface plot (variasi pola makan).

---

## ⚙️ Teknologi yang Digunakan
- **Python 3**
- **Pandas** – pengolahan data
- **NumPy** – perhitungan numerik
- **Matplotlib** – visualisasi grafik
- **Collections.Counter** – menghitung frekuensi makanan

---

## 🚀 Cara Menjalankan
1. Clone repositori ini:
   ```bash
   git clone https://github.com/username/nama-repo.git
   cd nama-repo
2. Pastikan Python dan library yang dibutuhkan sudah terinstal:
pip install pandas numpy matplotlib
3. Jalankan script utama:
python simulasi.py

## 📊 Contoh Output
* 10 Pola Makan Terbaik
* Makanan Favorit
* Grafik distribusi & hubungan skor

## ✨ Insight
Proyek ini menunjukkan bahwa pola konsumsi terbaik bukan hanya yang paling sehat atau paling murah, tetapi yang mampu menyeimbangkan gizi, rasa, variasi, dan biaya.

## 👤 Author
24083010034
Aisyah Amalia Hamid
Dibuat sebagai tugas mata kuliah Matematika Diskrit 🎓
