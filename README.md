# 📊 Projek PDS – Analisis IPM Jawa Tengah (2020–2024)
Proyek ini merupakan Team Based Project (50%) mata kuliah Pemodelan dan Simulasi (PDS).
Kelompok ini menganalisis faktor-faktor yang mempengaruhi Indeks Pembangunan Manusia (IPM) dengan Regresi Linier Berganda, uji asumsi klasik, prediksi, serta visualisasi peta sebaran IPM di Provinsi Jawa Tengah.

## 👥 Anggota Kelompok
1. Trisha Garnis Wahningyun – L0224012
2. Bagus Muhammad Razan Wahyudi - L0224015
3. Ibrahim Syauqi - L0224019
4. Michael Christian Shan Geraldo - L0224035
5. Nadhifa Sakha Tri Yasmin - L0224036
6. Talitha Sukma Mahardika - L0224037

## 🧪 Variabel Penelitian (2021-2023)
### 🎯 Y (Variabel Dependen):
IPM (Indeks Pembangunan Manusia)
### 🔢 X (Variabel Independen):
1. UHH (Umur Harapan Hidup)
2. HLS (Harapan Lama Sekolah)
3. RLS (Rata-rata Lama Sekolah)
4. Pengeluaran Per Kapita
5. Tingkat Pengangguran Terbuka (TPT)
6. Kepadatan Penduduk
7. Indeks Kedalaman Kemiskinan (P1)
8. Indeks Keparahan Kemiskinan (P2)

## 🔧 Panduan GIT untuk Semua Anggota (Sangat Penting)
Gunakan Git Bash.

#### 1. Clone Repository (WAJIB untuk semua anggota)
Ini hanya dilakukan sekali saat awal:
- git clone https://github.com/trishagarniss/projek-PDS-IPM.git
- cd projek-PDS-IPM
#### 2. Cara Membuat Branch (tiap anggota wajib)
Contoh untuk Talitha:
git checkout -b talitha
#### 3. Edit File di Branch Masing-Masing**
Setiap anggota hanya mengedit:
- notebook bagian masing-masing (dalam folder /src)
- tidak menyentuh folder orang lain
#### 4. Menyimpan Perubahan (add, commit, push)**
Setelah mengedit notebook:
- git add .
- git commit -m "Update notebook Talitha - model regresi"
- git push -u origin talitha
#### 5. Membuat Pull Request (PR)
- Buka GitHub repo
- Klik “Compare & Pull Request”
- Isi deskripsi
- Klik Create Pull Request
- Nanti akan review & merge.
#### 6.Update Folder Lokal (git pull)
Sebelum mengerjakan apapun, wajib lakukan:
- git pull
atau kalau di branch:
- Sebelum mengerjakan apapun, wajib lakukan:

## 📝 CATATAN
- Tidak boleh semua orang kerja di branch main → untuk menghindari tabrakan file
- Kalau mau pindah laptop / ganti device, lakukan git pull dulu sebelum ngedit
- Jangan pernah hapus folder yang dipakai orang lain
- Folder kosong harus ada .gitkeep supaya muncul di repo
- Shapefile jangan dihapus (banyak ekstensi)
