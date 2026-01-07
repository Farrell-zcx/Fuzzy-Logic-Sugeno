# Fuzzy-Logic-Sugeno
Program ini dibangun untuk menentukan 5 Bengkel Terbaik berdasarkan data bengkel yang memiliki atribut Kualitas Servis dan Harga.  Sistem menggunakan logika Fuzzy Sugeno untuk mengolah input menjadi skor kelayakan yang tegas (crisp value) untuk perankingan.

PANDUAN MENJALANKAN PROJECT FUZZY LOGIC
=========================================
-----------------------------------------
PRASYARAT
-----------------------------------------
Pastikan komputer Anda memiliki:
1. Python 3
2. Jupyter Notebook atau VS Code dengan ekstensi Jupyter.
3. Library Python standar: `csv`, `random`, `os`.
4. Library tambahan (HANYA untuk visualisasi grafik): `matplotlib`, `numpy`.

-----------------------------------------
CARA MENJALANKAN PROGRAM
-----------------------------------------
1.  Buka file `fuzzy.ipynb` menggunakan Jupyter Notebook atau VS Code.
2.  Jalankan semua sel dari atas ke bawah secara berurutan (Menu: Run All / Restart & Run All).
3.  Tunggu hingga proses selesai. Notebook akan melakukan hal berikut:
    a.  **Generate Dataset**: Membuat file `bengkel.csv` (100 data dummy) secara otomatis jika belum ada.
    b.  **Visualisasi**: Menampilkan grafik kurva Fungsi Keanggotaan (Membership Functions).
    c.  **Fuzzy Process**: Melakukan Fuzzifikasi, Inferensi, dan Defuzzifikasi murni menggunakan kode Python (tanpa library fuzzy).
    d.  **Visualisasi 3D**: Menampilkan diagram 3D hubungan antara Servis, Harga, dan Skor.
    e.  **Output**: 
        - Menampilkan tabel "Top 10 Bengkel Terbaik" di layar.
        - Menampilkan Grafik Batang (Bar Chart) hasil perankingan.
        - Menyimpan hasil perhitungan lengkap seluruh data ke file `peringkat_bengkel.csv`.

-----------------------------------------
FILE DALAM FOLDER
-----------------------------------------
1. Readme.txt            : File panduan ini.
2. fuzzy.ipynb           : File Program Utama (All-in-One: Kode, Desain, Visualisasi).
3. bengkel.csv           : Dataset input (Akan dibuat otomatis oleh program).
4. peringkat_bengkel.csv : Output hasil perankingan (Akan dibuat otomatis oleh program).

-----------------------------------------
CATATAN PENTING (SESUAI INSTRUKSI TUGAS)
-----------------------------------------
- Logika Fuzzy (Fuzzifikasi, Inferensi, Defuzzifikasi) dibangun MURNI MENGGUNAKAN PYTHON dari nol.
- TIDAK MENGGUNAKAN library khusus fuzzy (seperti scikit-fuzzy) untuk perhitungan logika utamanya.
- Library eksternal (`matplotlib`, `numpy`) hanya digunakan untuk keperluan Visualisasi Grafik agar tampilan lebih menarik ("Amazing").
- Penjelasan Desain Fuzzy (Aturan, Himpunan, dll) sudah terdokumentasi lengkap di dalam markdown `fuzzy.ipynb`.
