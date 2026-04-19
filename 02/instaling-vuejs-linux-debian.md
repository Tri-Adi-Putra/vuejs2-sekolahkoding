
Menginstal Vue.js di Kali Linux umumnya dilakukan melalui Node Package Manager (npm). Karena Kali Linux berbasis Debian, langkah-langkahnya hampir sama dengan distribusi Linux populer lainnya. [1, 2] 
Berikut adalah langkah-langkah untuk menginstal Vue.js menggunakan metode Vite (rekomendasi terbaru) atau Vue CLI:
## 1. Update Sistem dan Instal Node.js
Vue.js memerlukan Node.js. Pastikan sistem Anda mutakhir dan instal Node.js beserta npm melalui terminal: [1, 3, 4, 5] 

* Update repositori: sudo apt update
* Instal Node.js & npm: sudo apt install nodejs npm -y
* Verifikasi instalasi:
* node -v
   * npm -v [3] 
* 
<img width="749" height="444" alt="image" src="https://github.com/user-attachments/assets/7d37e257-b426-43be-9979-a9fe4b7da02d" />

<img width="745" height="796" alt="image" src="https://github.com/user-attachments/assets/8f7b2342-7dc5-4337-ac9f-4d6dc3e6f2a7" />


## 2. Opsi A: Membuat Proyek dengan Vite (Direkomendasikan)
Metode ini adalah standar terbaru untuk memulai proyek Vue 3 karena jauh lebih cepat daripada CLI lama. [6] 

   1. Jalankan perintah berikut di folder proyek Anda:
   
   npm create vue@latest
   
   2. Ikuti instruksi interaktif di terminal (seperti memberi nama proyek, memilih TypeScript, dll).
   3. Masuk ke folder proyek, instal dependensi, dan jalankan server:
   
   cd nama-proyek-anda
   npm install
   npm run dev
   
   [7] 

## 3. Opsi B: Instal Vue CLI (Metode Klasik)
Jika Anda membutuhkan Vue CLI untuk proyek lama atau fitur tertentu, Anda bisa menginstalnya secara global: [8, 9] 

* Instal secara global: sudo npm install -g @vue/cli
* Cek versi: vue --version
* Buat proyek baru: vue create nama-proyek [1, 10, 11, 12] 
* 

## 4. Opsi C: Menggunakan CDN (Tanpa Instalasi)
Jika Anda hanya ingin mencoba Vue di file HTML sederhana tanpa build tools, Anda bisa langsung menambahkan tag script ke file HTML Anda: [13, 14, 15] 

<script src="https://unpkg.com"></script>

Tips Tambahan:

* NVM: Untuk mengelola banyak versi Node.js, sangat disarankan menggunakan Node Version Manager (nvm) daripada apt install.
* Visual Studio Code: Gunakan ekstensi Volar (Vue Language Features) untuk pengalaman coding terbaik di Linux. [16] 
* 

