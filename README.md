# TUGASRTC - Sistem Klasifikasi dan Prediksi Tanaman Berbasis Rust

Proyek ini terdiri dari beberapa modul berbasis Rust yang digunakan untuk melakukan klasifikasi tanaman menggunakan algoritma **Neural Network**, **SVM**, dan **k-Nearest Neighbor (kNN)**. Beberapa modul terintegrasi dengan Qt untuk antarmuka pengguna.

## 🧭 Struktur Proyek

- `lookupTable/`: Program lookup sederhana untuk konversi nilai.
- `nnqt/`: Neural Network + integrasi Qt GUI. Meliputi pelatihan model, simpan model (`model.bin`), dan prediksi.
- `svmnkn/`: Program klasifikasi tanaman menggunakan SVM dan kNN. Hasil prediksi divisualisasi dalam `.png`.
- `taylor/`: Proyek tambahan/eksperimen lainnya.

## 📦 Setup & Instalasi

1. **Clone Repository**
   ```bash
   git clone https://github.com/Aang14/TugasRTC.git
   cd TugasRTC
2. Code (kanan atas)
3. atau bisa download di local yang sudah berzip
5. pilih codespace
6. atau klik link berikut (https://bookish-giggle-g9wp5wpw6pjhvpwj.github.dev/)
7. Pilih Tugas Rtc 
8. sebelah tugasrtc ada titik 3 lalu klik
9. lalu pilih dijalankan dalam visual studio code
10. bisa dijalankan di vs code masing masing

# TugasRTC
# StrukturProject
TUGASRTC/
├── lookupTable/
│   ├── src/
│   │   └── main.rs          # Main program untuk modul Lookup Table
│   ├── Cargo.toml           # Konfigurasi dependensi dan metadata proyek
│   └── Cargo.lock
│
├── nnqt/                    # Neural Network + Qt Frontend
│   ├── data/                # Folder untuk dataset
│   ├── output/              # Folder untuk hasil output
│   ├── QtFrontend/          # Folder untuk UI Qt
│   ├── src/
│   │   ├── data.rs          # Modul untuk load/preproses data
│   │   ├── main.rs          # Main program Neural Network
│   │   ├── model.rs         # Modul definisi model NN
│   │   └── utils.rs         # Fungsi pembantu
│   ├── model.bin            # File hasil pelatihan model
│   ├── results.json         # Hasil evaluasi model
│   ├── scaler.bin           # File scaler (normalisasi)
│   ├── Cargo.toml
│   └── Cargo.lock
│
├── svmnkn/                  # Proyek SVM dan kNN
│   ├── src/
│   ├── data_core.csv        # Dataset utama
│   ├── knn_predictions.png  # Hasil prediksi kNN (grafik)
│   ├── svm_predictions.png  # Hasil prediksi SVM (grafik)
│   ├── Cargo.toml
│   └── Cargo.lock
│
├── taylor/                  # Submodul atau proyek lain bernama taylor
│   ├── src/
│   ├── Cargo.toml
│   └── Cargo.lock
│
├── README.md                # Dokumentasi utama proyek
└── Cargo.toml (root - optional jika menggunakan workspace)

