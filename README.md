
Setiap folder mewakili **kelas** (label) yang digunakan dalam pelatihan model CNN.

---

## 📊 Informasi Dataset

| Kategori   | Subkategori       | Jumlah Citra | Keterangan |
|-------------|------------------|---------------|-------------|
| Organik     | Buah, Sayur, Sisa Makanan, Tanaman | ±800 | Citra hasil pengambilan langsung di lingkungan sekolah dan rumah |
| Anorganik   | Plastik, Kertas, Kaleng, Kain, Styrofoam | ±1200 | Citra dari berbagai sumber dan variasi kondisi pencahayaan |
| B3          | Baterai, HP, Bohlam, Kabel | ±600 | Fokus pada sampah berbahaya dan elektronik kecil |

Total data: **±2600 citra**  
Format gambar: `.jpg`, `.jpeg`, `.png`  
Resolusi: 224x224 px  

---

## ⚙️ Tujuan Penggunaan

Dataset ini digunakan untuk:
- Melatih model CNN berbasis **TensorFlow.js / MobileNetV1**  
- Membangun sistem klasifikasi real-time dalam aplikasi edukasi **Jagabumi**
- Mendukung kegiatan edukatif dan penelitian non-komersial di bidang lingkungan dan pembelajaran digital

---

## 🧠 Pelabelan Data

Setiap gambar diberi label sesuai jenis dan subkategori sampahnya berdasarkan standar **KLHK Indonesia**:
- **Organik:** Dapat terurai alami
- **Anorganik:** Tidak mudah terurai
- **B3:** Berbahaya atau beracun

---

## 🧩 Pembagian Data

| Set | Persentase | Tujuan |
|------|-------------|--------|
| Train | 70% | Melatih model |
| Validation | 15% | Menyesuaikan parameter model |
| Test | 15% | Mengukur performa model |

---

## 📈 Evaluasi Model

Model yang dilatih menggunakan dataset ini diuji dengan metrik:
- **Akurasi:** 90.4%
- **Presisi:** 89.7%
- **Recall:** 88.9%
- **F1-Score:** 89.3%

---

## ⚖️ Lisensi

Dataset ini digunakan hanya untuk **keperluan penelitian dan edukasi**, bukan untuk tujuan komersial.  
Jika ingin menggunakan dataset ini, mohon mencantumkan atribusi ke proyek:

> Antonius, N. (2025). *Jagabumi: Aplikasi Edukasi Klasifikasi Sampah Berbasis Web dan Deep Learning.*

---

## 🤝 Kontribusi

Kontribusi berupa tambahan data gambar, anotasi, atau perbaikan struktur dataset sangat disambut.  
Hubungi: **nicholasanonius46@gmail.com**

---

## 📅 Versi Dataset

**Versi:** 1.0  
**Tanggal Rilis:** November 2025  
**Format:** Folder terstruktur  
**Total Data:** ±2600 gambar

---

