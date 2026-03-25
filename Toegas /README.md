## 1.Penjelasan Array
Array adalah struktur data yang digunakan untuk menyimpan banyak nilai dalam satu variabel. Di Python, array biasanya disebut sebagai *list*. Contohnya seperti `nilai = [80, 75, 90]`. Dengan menggunakan array, data dapat diolah dengan lebih mudah, misalnya untuk mencari nilai tertinggi, terendah, atau rata-rata. Array juga memiliki indeks yang dimulai dari 0, sehingga setiap data bisa diakses berdasarkan posisinya. Secara sederhana, array membantu kita mengelola banyak data sekaligus dengan lebih rapi dan efisien.


## Analisis Kelebihan dan Kekurangan
### ✅ Kelebihan
- **Sederhana dan mudah dipahami**  
  Struktur kode jelas sehingga cocok untuk pembelajaran dasar Python.

- **Menggunakan list (array)**  
  Data nilai tersimpan dalam satu variabel sehingga mudah diolah.

- **Memanfaatkan fungsi bawaan Python**  
  Penggunaan `max()`, `min()`, dan `sum()` membuat kode lebih ringkas.

- **Sudah ada visualisasi data**  
  Program tidak hanya menampilkan output teks, tetapi juga grafik (bar dan pie) sehingga lebih informatif.

- **Alur program terstruktur**  
  Mulai dari input, proses, hingga output tersusun dengan baik.

### ❌ Kekurangan
- **Tidak ada validasi input**  
  Program langsung menerima input tanpa pengecekan (misalnya nilai di luar 0–100 atau input non-angka).

- **Jumlah data masih statis**  
  Hanya bisa memasukkan 10 nilai (tidak fleksibel).

- **Belum modular (tidak menggunakan fungsi)**  
  Semua kode ditulis dalam satu blok, sehingga kurang rapi jika program diperbesar.

- **Visualisasi masih sederhana**  
  Grafik belum memiliki detail tambahan seperti label nilai atau styling yang lebih informatif.

- **Tidak ada penyimpanan data**  
  Data hanya ditampilkan dan tidak disimpan ke file.

### 💡 Saran Pengembangan
- Menambahkan validasi input
- Menggunakan fungsi agar kode lebih terstruktur
- Membuat jumlah input lebih fleksibel
- Menambahkan fitur penyimpanan (file .txt / .csv)
- Memperbaiki tampilan grafik agar lebih informatif

  ## Screenshot hasil eksekusi
  ## Input Nilai
  <img width="433" height="295" alt="Screenshot 2026-03-25 114838" src="https://github.com/user-attachments/assets/09162329-8763-4ba3-b9ea-6de76bb8a31e" />

  
  ## Output Teks di terminal
  <img width="719" height="136" alt="Screenshot 2026-03-25 115436" src="https://github.com/user-attachments/assets/876f3686-df31-42f0-b081-f055c0123081" />

  
  ## Grafik bar (Min – Max)
  <img width="701" height="567" alt="Screenshot 2026-03-25 115605" src="https://github.com/user-attachments/assets/dddc7692-7b53-423d-b826-1e1030bfc6f0" />

  ## Grafik Data Kelulusan
  <img width="472" height="498" alt="Screenshot 2026-03-25 122942" src="https://github.com/user-attachments/assets/4baf0f00-9872-4b8c-b4d0-77d24e4f5158" />


-----------------------------------
## ⚙️ Kompleksitas

| Proses               | Operasi yang Dilakukan                | Kompleksitas | Keterangan                          |
|----------------------|--------------------------------------|-------------|-------------------------------------|
| Input data           | Menginput 10 nilai ke dalam list     | O(n)        | Dilakukan perulangan sebanyak n data |
| Max & Min            | Mencari nilai terbesar & terkecil    | O(n)        | Mengecek seluruh elemen dalam list  |
| Rata-rata            | Menjumlahkan lalu membagi data       | O(n)        | Menggunakan fungsi `sum()`          |
| Hitung lulus         | Mengecek nilai ≥ 60                  | O(n)        | Iterasi untuk menentukan kelulusan  |

---------------------------------

## 💭 Refleksi Pembelajaran
- Saya memahami cara mengolah data sederhana menggunakan Python, khususnya dengan menggunakan list sebagai tempat penyimpanan data.
- Saya belajar menggunakan perulangan (loop) untuk memproses data secara berulang dan lebih efisien.
- Saya mulai terbiasa memanfaatkan fungsi bawaan Python seperti `max()`, `min()`, dan `sum()` untuk menyederhanakan kode.
- Saya mendapatkan pengalaman baru dalam membuat visualisasi data menggunakan matplotlib.
- Saya menyadari bahwa penyajian data dalam bentuk grafik dapat membantu memahami informasi dengan lebih jelas.
- Program ini membantu saya memahami dasar-dasar logika pemrograman dan alur pengolahan data.
- Ke depannya, saya ingin mengembangkan program ini agar lebih fleksibel dan memiliki validasi input yang lebih baik.


  
