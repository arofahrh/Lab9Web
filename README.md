_Nama : Arofah Raudlatul Hasanah_  
_Kelas : TI.24.A2_  
_NIM  : 312410231_  
## Praktikum 9: PHP Modular
Pada praktikum ini saya mengembangkan project CRUD dari praktikum sebelumnya (Praktikum 8) menjadi lebih rapi dengan konsep modularisasi, template, dan routing.
Tujuan utamanya adalah agar struktur project lebih terorganisir dan setiap halaman memiliki tampilan yang konsisten.
- Struktur Folder
  ```
  lab9_php_modular/
  ├── index.php
  ├── koneksi.php
  ├── style.css
  ├── img/
  │   └── (file gambar)
  ├── template/
  │   ├── header.php
  │   └── footer.php
  └── user/
      ├── list.php
      ├── add.php
      ├── edit.php
      ├── delete.php
  ```
  - Konsep Modularisasi  
    Saya memisahkan bagian halaman menjadi beberapa modul:
- header.php → berisi bagian atas halaman (HTML, navbar, judul)
- footer.php → berisi bagian bawah halaman (penutup layout)
- list/add/edit/delete → modul CRUD
Semua halaman memanggil template dengan require() agar tampilannya konsisten.

  - Tampilan akhir :  
    <img width="957" height="459" alt="Screenshot 2025-11-24 135637" src="https://github.com/user-attachments/assets/d27dc67f-ac54-40ad-affe-442ed0062a78" />

- langkah-langkah praktikum
1. Buat file baru dengan nama header.php  
   <img width="1029" height="521" alt="Screenshot 2025-11-24 123936" src="https://github.com/user-attachments/assets/2fdbdcbe-3018-488d-8b54-bac2ab31f849" />
   
2. Buat file baru dengan nama footer.php  
  <img width="720" height="132" alt="Screenshot 2025-11-24 124258" src="https://github.com/user-attachments/assets/334b0cf5-2119-4d04-9225-0c11d3318399" />

3. Buat file baru dengan nama home.php  
   <img width="531" height="176" alt="image" src="https://github.com/user-attachments/assets/3e525147-5051-44e9-8f4b-91c580cd77a4" />
   
4. Buat file baru dengan nama about.php  
   <img width="697" height="198" alt="image" src="https://github.com/user-attachments/assets/3e54f831-ab0f-4af7-8107-96db84165f8d" />  



