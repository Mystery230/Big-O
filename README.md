# Koleksi Skrip Python: Konsep Dasar dan Notasi Big O

Repositori ini berisi kumpulan skrip Python sederhana yang dirancang untuk mengilustrasikan konsep-konsep dasar dalam pemrograman dan analisis kompleksitas waktu menggunakan Notasi Big O.

## Deskripsi

Setiap file dalam repositori ini menunjukkan ide atau prinsip tertentu, mulai dari dasar-dasar Pemrograman Berorientasi Objek (OOP) hingga berbagai kompleksitas waktu seperti O(1), O(n), dan O(n²). Skrip ini sangat baik untuk tujuan pembelajaran dan untuk meninjau kembali bagaimana berbagai struktur kode memengaruhi kinerja suatu algoritma.

## Daftar Skrip

Berikut adalah rincian dari setiap skrip yang disertakan:

### 1. `Cookie.py`

* **Konsep:** Pemrograman Berorientasi Objek (OOP) Dasar.
* **Deskripsi:** Skrip ini mendefinisikan sebuah *class* `Cookie` dengan *constructor* (`__init__`) untuk menginisialisasi warna cookie, serta *method* untuk mendapatkan dan mengatur warnanya. Ini menunjukkan bagaimana objek dibuat dari sebuah *class* dan bagaimana keadaannya (*state*) dapat dimodifikasi secara independen.
* **Untuk Menjalankan:**
    ```bash
    python Cookie.py
    ```

### 2. `O(1).py`

* **Konsep:** Kompleksitas Waktu Konstan - $O(1)$.
* **Deskripsi:** Skrip ini berisi fungsi yang melakukan jumlah operasi yang sama terlepas dari ukuran input `n`. Ini adalah contoh dari kompleksitas waktu $O(1)$, atau "waktu konstan".
* **Untuk Menjalankan:**
    ```bash
    python O(1).py
    ```

### 3. `O(n).py`

* **Konsep:** Kompleksitas Waktu Linier - $O(n)$.
* **Deskripsi:** Fungsi dalam skrip ini melakukan iterasi dari 0 hingga `n-1`. Jumlah operasi tumbuh secara linier seiring dengan meningkatnya nilai `n`. Ini adalah representasi klasik dari kompleksitas waktu $O(n)$.
* **Untuk Menjalankan:**
    ```bash
    python O(n).py
    ```

### 4. `Drop+Const.py`

* **Konsep:** Menyederhanakan Notasi Big O - Menghilangkan Konstanta.
* **Deskripsi:** Skrip ini memiliki fungsi dengan dua *loop* terpisah yang masing-masing berjalan `n` kali. Meskipun total operasinya adalah $O(2n)$, dalam Notasi Big O kita menghilangkan konstanta, sehingga kompleksitasnya disederhanakan menjadi $O(n)$.
* **Untuk Menjalankan:**
    ```bash
    python Drop+Const.py
    ```

### 5. `Different+Terms.py`

* **Konsep:** Notasi Big O dengan Input Berbeda - $O(a + b)$.
* **Deskripsi:** Fungsi ini menerima dua argumen, `a` dan `b`, dan memiliki dua *loop* terpisah yang masing-masing bergantung pada salah satu input. Kompleksitas waktunya adalah $O(a + b)$, menunjukkan bagaimana kita menganalisis kompleksitas ketika ada beberapa variabel input yang tidak saling bergantung.
* **Untuk Menjalankan:**
    ```bash
    python Different+Terms.py
    ```

### 6. `Non+Dom.py`

* **Konsep:** Menyederhanakan Notasi Big O - Menghilangkan Suku Non-Dominan.
* **Deskripsi:** Fungsi ini berisi *loop* bersarang ($O(n²)$) diikuti oleh *loop* tunggal ($O(n)$). Kompleksitas totalnya adalah $O(n² + n)$. Saat menganalisis Big O, kita hanya menyimpan suku yang paling signifikan (dominan), sehingga kompleksitasnya disederhanakan menjadi $O(n²)$.
* **Untuk Menjalankan:**
    ```bash
    python Non+Dom.py
    ```

## Cara Menggunakan

1.  **Clone Repositori:**
    ```bash
    git clone https://github.com/Mystery230/Big-O.git
    cd Big-O
    ```
2.  **Jalankan Skrip:**
    Anda dapat menjalankan setiap file secara individual menggunakan Python untuk mengamati output dan memahami cara kerjanya.
    ```bash
    python Cookie.py
    
    python O(1).py
    
    python O(n).py
    
    python Drop+Const.py
    
    python Different+Terms.py
    
    python Non+Dom.py
    ```
