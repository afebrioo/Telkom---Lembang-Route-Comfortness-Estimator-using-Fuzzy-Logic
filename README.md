# Telkom - Lembang Fuzzy Router

## Deskripsi Proyek
Sistem fuzzy ini dirancang untuk menentukan waktu terbaik melakukan perjalanan dari Telkom University ke Lembang. Tujuan utama dari sistem ini adalah mengurangi risiko perjalanan yang disebabkan oleh cuaca buruk atau kemacetan lalu lintas yang parah.

## Fitur Utama
- **Input Parameter:**
  - **Cuaca:** Cerah, Berawan, Hujan, Sangat Hujan
  - **Intensitas Kendaraan:** Sepi, Ramai, Macet
  - **Waktu Keberangkatan:** Pagi, Siang, Malam
- **Output:** Rekomendasi waktu perjalanan terbaik untuk kenyamanan maksimal.

## Metodologi
1. **Fuzzifikasi:** Menggunakan fungsi keanggotaan trapesium dan linear untuk mengonversi input menjadi nilai fuzzy.
2. **Inferensi:** Menggunakan aturan berbasis fuzzy untuk menentukan rekomendasi perjalanan.
3. **Defuzzifikasi:** Metode Sugeno dan Mamdani untuk menghasilkan output akhir.

## Instalasi
1. Clone repository ini:
   ```bash
   git clone https://github.com/username/telkom-lembang-fuzzy-router.git
   ```
2. Masuk ke direktori proyek:
   ```bash
   cd telkom-lembang-fuzzy-router
   ```
3. Install dependensi yang diperlukan:
   ```bash
   pip install -r requirements.txt
   ```

## Cara Penggunaan
1. Jalankan notebook Jupyter yang tersedia:
   ```bash
   jupyter notebook 4_1103223024_RahmandaAfebrio.ipynb
   ```
2. Ikuti instruksi dalam notebook untuk memasukkan parameter cuaca, intensitas kendaraan, dan waktu keberangkatan.
3. Dapatkan rekomendasi waktu terbaik untuk perjalanan Anda.

## Studi Kasus
- **Kasus 1:**
  - **Waktu:** 11:00
  - **Intensitas Kendaraan:** 12
  - **Cuaca:** 19
  - **Hasil:** Perjalanan kurang nyaman dengan nilai output 34.

- **Kasus 2:**
  - **Waktu:** 06:00
  - **Intensitas Kendaraan:** 7
  - **Cuaca:** 35
  - **Hasil:** Perjalanan lebih nyaman dengan nilai output 34.

## Kontributor
- Rahmanda Afebrio Yuris Soesatyo (110223024)
- Rafly Fasha Purnomo Putra (1103223050)
- Rifqi Muhammad Harahap (1103223138)

## Lisensi
Proyek ini menggunakan lisensi [MIT License](LICENSE).

## Referensi
- Google Colab
- ChatGPT
- Gemini AI
- Modul Kecerdasan Buatan I-Smile Laboratory

