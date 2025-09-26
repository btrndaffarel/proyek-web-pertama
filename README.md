# 🌐 Proyek Web Pertama

Repositori ini adalah contoh sederhana penggunaan **Git** dan **GitHub** dalam pengembangan web.  
Proyek ini berisi file **HTML** dan **CSS** dasar serta contoh penggunaan **branching** dan **merging** di Git.

## 🚀 Langkah Pembuatan Proyek

### 1️⃣ Buat Folder Proyek 📂
```bash
mkdir proyek1-web 
cd proyek1-web
<img width="331" height="78" alt="ss1" src="https://github.com/user-attachments/assets/7d147f7c-726d-43e5-a099-04c3395fdcff" />

### 2️⃣ Inisialisasi Repository Git ⚙️
git init
<img width="593" height="52" alt="ss2" src="https://github.com/user-attachments/assets/c36e3142-a794-4646-9814-4e4c5e265e66" />

### 3️⃣ Buat Beberapa File 📄
echo "<h1>Selamat Datang</h1>" > index1.html 
mkdir css
echo "body { font-family: sans-serif; }" > css/style1.css
<img width="477" height="78" alt="ss3" src="https://github.com/user-attachments/assets/b113216d-6bd4-4cbe-a117-61eab385a6ed" />
<img width="472" height="35" alt="ss4" src="https://github.com/user-attachments/assets/0b627c9c-1662-41c9-b9fa-0fc0adf91cd5" />

### 4️⃣ Commit Pertama di Branch Utama 📝
git add .
git commit -m "feat: inisialisasi proyek dengan index.html dan style.css"
<img width="750" height="163" alt="ss6" src="https://github.com/user-attachments/assets/c68cd5dc-4560-436f-8380-d082dca47810" />

### 5️⃣ Buat Branch Baru untuk Fitur 🌱
git checkout -b fitur-kontak
<img width="477" height="48" alt="ss7" src="https://github.com/user-attachments/assets/02856c22-8e64-464f-8f30-8a568e93a52a" />

### 6️⃣ Tambah File Baru ➕
echo "<h1>Halaman Kontak</h1>" > kontak1.html 
git add .
git commit -m "feat: tambah halaman kontak"
<img width="736" height="173" alt="ss8" src="https://github.com/user-attachments/assets/adba8a2d-99d0-4deb-8a09-724ece53d0ce" />

### 7️⃣ Kembali ke Branch Utama 🔄
git checkout master
<img width="518" height="48" alt="ss9" src="https://github.com/user-attachments/assets/d8f53c0e-9d24-4feb-8365-3261347ac0b5" />

### 8️⃣ Gabungkan Branch Fitur ke Main 🤝
git merge fitur-kontak
<img width="481" height="108" alt="ss10" src="https://github.com/user-attachments/assets/8b0b78f6-e095-4f15-b424-82b9670306cc" />

### 9️⃣ Hubungkan & Push ke GitHub ☁️
git remote add origin https://github.com/btrndaffarel/proyek-web-pertama.git 
git branch -M main 
git push -u origin main
<img width="560" height="276" alt="ss11" src="https://github.com/user-attachments/assets/744bc866-a9ba-4e6b-bb46-12fa189d4485" />

📂 Struktur Direktori
proyek1-web/
│── index1.html
│── kontak1.html
└── css/
    └── style1.css
