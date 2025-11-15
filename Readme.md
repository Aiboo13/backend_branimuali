🚀 Panduan Instalasi & Menjalankan Backend
📦 Instalasi Dependensi

Jalankan perintah berikut untuk menginstal semua package yang dibutuhkan:

1. npm install
2. npm install dotenv
3. npm install ts-node typescript @types/node --save-dev 
4. npm install express cors 
5. npm install mysql2 
6. npm install --save-dev @types/express @types/cors @types/mysql2 

🌱 Seeder Data ke Database MySQL

### Untuk melakukan seeding data ke database, gunakan perintah berikut:

##### npx ts-node src/seed/seedUMKM.ts 


Pastikan database sudah dibuat sebelum menjalankan perintah ini.

▶️ Menjalankan Backend

Gunakan perintah berikut untuk menjalankan server backend:

npm run dev ||