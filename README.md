# TUGASRTC - Sistem Klasifikasi dan Prediksi Tanaman Berbasis Rust

## SUPERVISOR : Ahmad Radhy, S.Si., M.Si
## KELOMPOK 1 DEPARTEMEN TEKNIK INSTRUMENTASI - INSTITUT TEKNOLOGI SEPULUH NOPEMBER 
## 1. AHMAD ZIDAN ANFA'A - 2042221005
## 2. JEA AYU FATMASARI - 2042221083
## 3. CHELYA JUNIAR PRASANTI - 2042221128
Proyek ini terdiri dari beberapa modul berbasis Rust yang digunakan untuk melakukan klasifikasi tanaman menggunakan algoritma **Neural Network**, **SVM**, dan **k-Nearest Neighbor (kNN)**. Beberapa modul terintegrasi dengan Qt untuk antarmuka pengguna.

## 🧭 Struktur Proyek

- `lookupTable/`: Program lookup sederhana untuk konversi nilai.
- `nnqt/`: Neural Network + integrasi Qt GUI. Meliputi pelatihan model, simpan model (`model.bin`), dan prediksi.
- `svmnkn/`: Program klasifikasi tanaman menggunakan SVM dan kNN. Hasil prediksi divisualisasi dalam `.png`.
- `deret taylor/`: Proyek perhitungan nilai sudut sinus dan cosinus.

## 📦 Setup & Instalasi
# tata cara membuat program rush 
1. deret taylor
- pertama download rust dalam ubuntu dan bisa dijalankan dalam visual studio code
- lalu masukkan // Fungsi untuk menghitung faktorial
- dan masukkan // Fungsi untuk menghitung sinus menggunakan deret Taylor
- dan masukkan // Fungsi untuk menghitung cosinus menggunakan deret Taylor
- lalu buat fungsi main untuk mengintegrasikan fungsi fungsi diatas
- semua codingan terdapat di file zip jadi bisa didownload dan tata caranya bisa dilihat dibawah

2. lookuptable
- pertama download rust dalam ubuntu dan bisa dijalankan dalam visual studio code
- lalu masukkan // Fungsi pemetaan tabel
- dan masukkan // Fungsi untuk menghitung sinus 
- dan masukkan // Fungsi untuk menghitung cosinus
- dan masukkan // fungsi untuk mengihutng aktual sinus-cosinus
- lalu buat fungsi main untuk mengintegrasikan fungsi fungsi diatas
- semua codingan terdapat di file zip jadi bisa didownload dan tata caranya bisa dilihat dibawah

3. SVM (Support Vector Machine) & KNN (Klasifikasi-Nearest Neighbor)
- pertama download rust dalam ubuntu dan bisa dijalankan dalam visual studio code
- lalu masukkan library terlebih dahulu yaitu
csv = "1.3.1"
linfa = "0.7.1"
linfa-svm = "0.7.2"
linfa-nn = "0.7"
linfa-kernel = "0.7.1"
linfa-logistic = "0.7.1"
ndarray = "0.15.6"
rand = "0.8.5"
plotters = "0.3.7"

librrary diatas sangat dibutuhkan dalam proses pembuatan svm knn dan jangan lupa datasetnya juga 
- lalu masukkan // DATA LOADER
- dan masukkan // EUCLIDEAN DISTANCE 
- dan masukkan // KNN
- dan masukkan // SVM
- dan masukkan // AKURASI 
- lalu buat fungsi main untuk mengintegrasikan fungsi fungsi diatas
- semua codingan terdapat di file zip jadi bisa didownload dan tata caranya bisa dilihat dibawah

4. Neural Network
- pertama download rust dalam ubuntu dan bisa dijalankan dalam visual studio code
- lalu masukkan library terlebih dahulu yaitu
ndarray = "0.15"
rand = "0.8"
csv = "1.1"

librrary diatas sangat dibutuhkan dalam proses pembuatan neural network dan jangan lupa datasetnya juga 
- lalu masukkan // impl NeuralNetwork
- dan masukkan // one hot encode
- dan masukkan // load dataset
- lalu buat fungsi main untuk mengintegrasikan fungsi fungsi diatas
- semua codingan terdapat di file zip jadi bisa didownload dan tata caranya bisa dilihat dibawah

5. Neural Network and Frontend qt.py
- pertama download rust dalam ubuntu dan bisa dijalankan dalam visual studio code
- lalu masukkan library terlebih dahulu yaitu
rand = { version = "0.8", features = ["small_rng"] }
plotters = "0.3.5"
serde = { version = "1.0", features = ["derive"] }
serde_json = "1.0"
librrary diatas sangat dibutuhkan dalam proses pembuatan neural network & Frontend qt.py dan jangan lupa datasetnya juga
- buat folder qt.py yang isinya adalah codingan integrasi rust dan frontend tampilan nantinya
- lalu untuk proses pembuatan rust terdapat 4 folder yaitu main.rs, data.rs, model.rs, utils.rs
- data.rs berfungsi untuk memanggil dataset .csv dan membaca data untuk codingan dan fungsi terdapat di file zip.
- main.rs berfungsi untuk pembuatan codingan neural network dan memuat data.rs, model.rs, utils.rs dan yang pasti di integrasikan dengan qt.py
- model.rs berfungsi untuk penyesuaian font huruf dan angka yang akan ditampilkan dalam forntend nanti tetapi berfokus didalam rust
- utils.rs berfungsi untuk plot akurasi dan membedakan tiap fungsi neural network nantinya
- semua codingan terdapat di file zip jadi bisa didownload dan tata caranya bisa dilihat dibawah
- 
# tata cara menjalankan program rush

1. deret taylor
- download file zip berjudul taylor
- simpan file tersebut didalam home os ubuntu dan sudah di extract
- lalu buka terminal ketik (code .) didalam terminal
- atau bisa langsung klik visual studio code
- lalu buka open folder dan dan buka file extrac lalu open didalam vs code
- jalankan program tersebut di terminal vs code new terminal
- ketik cargo build
- lalu cargo run
- maka deret taylor siap dilaksanakan

2. Lookuptable 
- download file zip berjudul lookuptable
- simpan file tersebut didalam home os ubuntu dan sudah di extract
- lalu buka terminal ketik (code .) didalam terminal
- atau bisa langsung klik visual studio code
- lalu buka open folder dan dan buka file extrac lalu open didalam vs code
- jalankan program tersebut di terminal vs code new terminal
- ketik cargo build
- lalu cargo run
- maka lookuptable siap dilaksanakan

3. Svm-Knn
- download file zip berjudul svmknn
- simpan file tersebut didalam home os ubuntu dan sudah di extract
- lalu buka terminal ketik (code .) didalam terminal
- atau bisa langsung klik visual studio code
- lalu buka open folder dan dan buka file extrac lalu open didalam vs code
- jalankan program tersebut di terminal vs code new terminal
- ketik cargo build
- lalu cargo run
- maka svm knn siap dilaksanakan

4. Neural Network
- download file zip berjudul NN_lama
- simpan file tersebut didalam home os ubuntu dan sudah di extract
- lalu buka terminal ketik code . didalam terminal
- atau bisa langsung klik visual studio code
- lalu buka open folder dan dan buka file extrac lalu open didalam vs code
- jalankan program tersebut di terminal vs code new terminal
- ketik cargo build
- lalu cargo run
- maka neural network siap dilaksanakan

5. Neural Network dan Frontend QT
- download file zip berjudul nnqt
- simpan file tersebut didalam home os ubuntu dan sudah di extract
- lalu buka terminal ketik (code .) didalam terminal
- atau bisa langsung klik visual studio code
- lalu buka open folder dan dan buka file extrac lalu open didalam vs code
- jalankan program tersebut di terminal vs code new terminal
- ketik cargo build --release
- lalu cargo run
- maka nnqt siap dilaksanakan

# Terima Kasih selamat mencoba
