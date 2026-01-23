# test

# 📘 Panduan Git & GitHub

Memahami konsep dasar dan perintah-perintah penting dalam Git dan GitHub.

---

## 1. Git vs GitHub

### 🔹 Git
Git adalah **alat (software) Version Control System** yang dipasang di komputer.  
Fungsinya untuk mencatat setiap perubahan pada file di dalam sebuah proyek.

### 🔹 GitHub
GitHub adalah **layanan berbasis internet** untuk menyimpan repository Git.  
GitHub memudahkan kolaborasi dan sinkronisasi kode secara online.

---

## 2. Istilah Penting yang Wajib Diketahui

- **Repository (Repo)**  
  Folder proyek yang berisi semua file kode dan riwayat perubahannya.

- **Commit**  
  Seperti tombol *Save*, tetapi dengan catatan.  
  Setiap commit menyimpan perubahan yang dilakukan beserta pesan penjelasan.

- **Push**  
  Mengirim perubahan dari komputer lokal ke server GitHub.

- **Pull**  
  Mengambil pembaruan terbaru dari server GitHub ke komputer lokal.

- **Branch**  
  Cabang dari kode utama untuk mengembangkan fitur baru tanpa merusak versi stabil.

---

## 3. Memahami Mengapa Kita Menjalankan Perintah Git

### `git init`
**Fungsi:**  
Mengubah folder biasa menjadi Git Repository.

**Mengapa:**  
Git akan membuat folder tersembunyi `.git` yang berfungsi sebagai *mesin waktu* untuk mencatat perubahan file.

---

### `git add .`
**Fungsi:**  
Memasukkan file ke **Staging Area**.

**Mengapa:**  
Git tidak otomatis mencatat perubahan.  
Tanda titik (`.`) berarti memilih semua file.

Analogi:  
Seperti memilih barang yang akan dimasukkan ke dalam kardus sebelum dikirim.

---

### `git commit -m "pesan"`
**Fungsi:**  
Menyimpan perubahan secara permanen di repository lokal.

**Mengapa:**  
Commit adalah proses *mengunci* perubahan dan memberi label penjelasan (`-m`).

---

### `git branch -M main`
**Fungsi:**  
Mengubah nama cabang utama menjadi `main`.

**Mengapa:**  
Standar modern (termasuk GitHub) menggunakan `main` sebagai cabang utama, bukan `master`.

---

### `git remote add origin <URL>`
**Fungsi:**  
Menghubungkan repository lokal dengan repository GitHub.

**Mengapa:**  
`origin` adalah alias agar kita tidak perlu mengetik URL panjang setiap saat.

---

### `git push -u origin main`
**Fungsi:**  
Mengunggah kode dari komputer ke GitHub.

**Penjelasan singkat:**
- `push` → mengirim
- `origin` → tujuan (GitHub)
- `main` → cabang utama
- `-u` → menyimpan pengaturan agar ke depan cukup `git push`

---

## 🔁 Alur Kerja Sederhana Git & GitHub

1. **Siapkan folder** → `git init`
2. **Pilih file** → `git add`
3. **Simpan dengan catatan** → `git commit`
4. **Tentukan tujuan** → `git remote`
5. **Kirim ke GitHub** → `git push`

---

📌 *Dengan memahami alur ini, kamu tidak sekadar menghafal perintah Git, tapi tahu alasan di balik setiap langkah.*
