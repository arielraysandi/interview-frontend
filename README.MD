# SOAL INTERVIEW WEB DEVELOPER

Buatlah sebuah project website dengan mengimplementasikan **single-page application (SPA)** menggunakan **JavaScript (Vue.js atau Nuxt.js), HTML, dan CSS**. Website tersebut harus memiliki fitur-fitur berikut yang mengambil data dari file `images.json` yang disediakan.


## Fitur Utama:

1.  **Autocomplete Search**
    
    -   Fitur pencarian di mana pengguna dapat mengetik nama gambar atau deskripsi untuk menemukan gambar yang sesuai.
    -   Autocomplete ini harus menampilkan saran secara real-time berdasarkan teks yang diketik pengguna.
    -   Hasil pencarian harus menampilkan kartu gambar yang relevan di bawah input pencarian.
2.  **Photo Gallery**
    
    -   Halaman utama harus menampilkan semua gambar dalam format grid yang responsif.
    -   Setiap kartu gambar di dalam galeri harus memiliki **title**, **image**, dan **rating**.
3.  **Image Carousel**
    
    -   Carousel harus mendukung fitur navigasi (panah kiri dan kanan) untuk melihat gambar sebelumnya atau selanjutnya.
    -   Tambahkan efek transisi untuk mempercantik pergantian gambar.
4.  **Tooltip**
    
    -   Tambahkan tooltip pada setiap gambar di galeri untuk menampilkan deskripsi singkat.
    -   Tooltip akan muncul saat kursor diarahkan ke gambar.
5.  **Rating Widget / Star Rating**
    
    -   Pengguna dapat melihat rating pada gambar dengan widget bintang.
    

## **Nice to Have:**

1.  **ESLint Integration**
    
    -   Gunakan **ESLint** untuk menganalisa kode dan memastikan bahwa tidak ada error, bug, atau pelanggaran konvensi kode.
    -   Lampirkan file konfigurasi ESLint dalam proyek.
2.  **Dark Mode**
    
    -   Tambahkan tombol untuk mengaktifkan dark mode di seluruh website.
    -   Gunakan preferensi tema pengguna (localStorage) untuk menyimpan pilihan mode.
3.  **Sorting and Filtering**
    
    -   Tambahkan filter untuk menampilkan gambar dengan rating di atas nilai tertentu (misalnya, hanya gambar dengan rating > 4).
4.  **SEO Optimization**
    
    -   Optimalkan website untuk search engine dengan menerapkan praktik SEO, seperti:
        -   Menambahkan **meta tags** (title, description, keywords).
        -   Menggunakan **semantic HTML** untuk meningkatkan aksesibilitas.
        -   Menambahkan **alt text** pada semua gambar.


>### **Catatan Teknis:**

1.  **Dilarang menggunakan library/package pihak ketiga** untuk membuat fitur-fitur di atas (misalnya, tidak boleh menggunakan library carousel).
2.  **Tidak dianjurkan menggunakan Bootstrap atau framework CSS lainnya.** Styling harus dilakukan dengan CSS murni.
3.  Gunakan desain yang responsif dan user-friendly. Pastikan tampilan website tetap nyaman diakses melalui perangkat mobile.
4.  Gunakan modul ES6 jika memungkinkan untuk memisahkan file JS berdasarkan fitur.


>**Output yang Diharapkan:**

-   Kode sumber lengkap dengan struktur folder yang rapi.
-   File konfigurasi **ESLint**.
-   File dokumentasi `README.md` yang berisi:
    -   Penjelasan singkat tentang cara menjalankan proyek.
    -   Daftar fitur yang diimplementasikan.
    -   Tantangan yang dihadapi dan bagaimana Anda mengatasinya.
