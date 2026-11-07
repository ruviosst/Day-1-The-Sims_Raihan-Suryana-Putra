# Dokumentasi Kegiatan Workshop TIKMENGAJAR - Day 1

## Informasi Peserta
- **Nama Lengkap:** Raihan Suryana Putra
- **Kelompok:** 15 - The Sims
- **Program Studi:** D4 - Teknik Multimedia dan Jaringan
- **Instansi:** Politeknik Negeri Jakarta

---

## Deskripsi Repository
Repository ini dibuat sebagai media penyimpanan, pengelolaan, dan publikasi secara daring untuk seluruh dokumentasi kegiatan, materi pembelajaran, catatan, serta hasil praktik latihan selama mengikuti kegiatan Workshop TIKMENGAJAR (Day 1).

## Tujuan Repository
1. Mendokumentasikan materi dan rangkaian kegiatan workshop secara terstruktur dan terarsip dengan baik.
2. Memenuhi tugas Misi Utama/Individu Proyek Workshop Day 1 TIKMENGAJAR HIMATIK PNJ.
3. Mengimplementasikan pengelolaan versi kode (*version control*) dan kolaborasi menggunakan Git dan GitHub.

---

## Informasi & Dokumentasi Kegiatan Workshop

### Ringkasan Kegiatan
- **Nama Kegiatan:** Workshop TIKMENGAJAR - Day 1
- **Penyelenggara:** Departemen Pendidikan & Teknologi - HIMATIK PNJ
- **Pemateri:** Nugi Farhan (Senior Product Designer)
- **Topik utama:** *Building with AI, Managing Change with GitHub*

### Catatan & Rangkuman Materi Pembelajaran

#### 1. Prompt Engineering & AI Assisted Development
- **Definisi:** Merancang instruksi/input yang tepat agar model AI memberikan jawaban yang spesifik, relevan, dan layak pakai.
- **Struktur Prompt yang Baik:**
  1. **Role:** Menentukan peran AI (misal: *Web Developer*).
  2. **Task:** Menyebutkan tugas spesifik yang harus dikerjakan.
  3. **Context:** Memberikan latar belakang dan kebutuhan proyek.
  4. **Format/Constraints:** Menentukan batasan (misal: HTML/CSS/JS murni) dan bentuk *output* yang diinginkan.

#### 2. Konsep Dasar Git & Version Control
- **Git:** Sistem *Distributed Version Control* (DVCS) untuk melacak perubahan berkas secara lokal.
- **Komponen Git Workflow:**
  - **Working Directory:** Direktori kerja tempat berkas dimodifikasi secara lokal.
  - **Staging Area (Index):** Tempat penampungan sementara berkas yang siap di-*commit*.
  - **Git Directory (Repository):** Database Git tempat seluruh metadata dan riwayat perubahan disimpan.

#### 3. Perbedaan Git dan GitHub
- **Git:** Alat/sistem pengontrol versi berbasis CLI yang berjalan di komputer lokal.
- **GitHub:** Platform berbasis web untuk menyimpan repository Git secara daring serta memfasilitasi kolaborasi tim.

#### 4. Hasil Praktik Proyek
- Membuat aplikasi web sederhana **Student Task Planner** menggunakan bantuan prompt AI.
- Melakukan inisialisasi repository Git lokal, membuat *commit*, mendefinisikan *remote repository*, dan melakukan *push* perubahan ke GitHub.

---

## Perintah Dasar Git yang Digunakan

```bash
# Inisialisasi repository baru
git init

# Menambahkan file ke staging area
git add .

# Menyimpan perubahan ke repository lokal
git commit -m "feat: initial commit project student task planner"

# Menghubungkan ke remote repository GitHub
git remote add origin [https://github.com/USERNAME_KAMU/NAMA_REPO.git](https://github.com/USERNAME_KAMU/NAMA_REPO.git)

# Mengunggah branch main ke remote repository
git push -u origin main
