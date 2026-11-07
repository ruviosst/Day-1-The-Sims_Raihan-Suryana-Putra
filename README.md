# Dokumentasi Kegiatan Workshop TIKMENGAJAR - Day 1

## Informasi Peserta
- **Nama Lengkap:** Raihan Suryana Putra
- **Program Studi:** D4 Teknik Multimedia dan Jaringan
- **Instansi:** Politeknik Negeri Jakarta

---

## Deskripsi Repository
Repository ini dibuat sebagai media penyimpanan, pengelolaan, dan publikasi secara daring untuk seluruh dokumentasi kegiatan, materi pembelajaran, catatan, serta hasil praktik latihan selama mengikuti kegiatan Workshop TIKMENGAJAR (Day 1).

## Tujuan & Kegunaan Repository
1. Mendokumentasikan materi dan seluruh rangkaian kegiatan workshop secara terstruktur dan terarsip dengan baik.
2. Memenuhi tugas Misi Utama / Individu Proyek Workshop Day 1 TIKMENGAJAR HIMATIK PNJ.
3. Mengimplementasikan pengelolaan versi kode (*version control*) dan kolaborasi menggunakan Git dan GitHub secara langsung.

---

## Dokumentasi Kegiatan Workshop

### 1. Rangkuman Materi Workshop
Workshop Day 1 TIKMENGAJAR membawakan topik utama ***Building with AI, Managing Change with GitHub*** yang dibawakan oleh Mas Nugi Farhan (Senior Product Designer). Rangkuman materinya mencakup:

- **Prompt Engineering & AI Assisted Development:** 
  Teknik merancang instruksi (prompt) yang tepat agar model AI memberikan luaran yang spesifik dan layak pakai. Prompt yang baik terdiri dari elemen **Role**, **Task**, **Context**, dan **Format/Constraints**.
- **Konsep Dasar Git & Version Control System (VCS):**
  Git adalah sistem *Distributed Version Control* lokal untuk melacak perubahan berkas. Memahami alur kerja Git dari *Working Directory* (tempat edit kode), *Staging Area/Index* (penampungan sementara perubahan), hingga *.git Directory/Repository* (database penyimpanan riwayat *commit*).
- **Perbedaan Git vs GitHub:**
  Git berfungsi sebagai alat pengontrol versi berbasis CLI di komputer lokal, sedangkan GitHub adalah platform web untuk menyimpan repository Git secara publik/privat serta memfasilitasi kolaborasi antarpengembang.
- **Praktik Proyek Web Sederhana:**
  Membuat aplikasi web *Student Task Planner* menggunakan bantuan prompt AI, lalu menginisialisasi repository Git lokal dan melakukan *push* kode ke GitHub.

---

### 2. Poin-Poin Penting & Pengetahuan Baru yang Dipelajari
- **Strukturasi Prompt yang Sistematis:** Mempelajari bahwa AI bekerja jauh lebih presisi ketika kita memberikan konteks batasan (*constraints*) dan format luaran yang jelas.
- **Perintah Penting Git (Git Essentials):**
  - `git init` untuk menginisialisasi repository lokal.
  - `git add .` untuk memindahkan perubahan ke *Staging Area*.
  - `git commit -m "pesan"` untuk menyimpan riwayat perubahan.
  - `git remote add origin <url>` dan `git push -u origin main` untuk menyinkronkan repository lokal ke GitHub secara daring.
- **Pentingnya Pengelolaan Perubahan (*Managing Change*):** Memahami bagaimana pengontrol versi membantu mencegah kehilangannya riwayat kode saat terjadi perbaikan atau penambahan fitur.

---

### 3. Pendapat Pribadi tentang Day 1 Proyek Workshop
Menurut saya, kegiatan Day 1 Proyek Workshop TIKMENGAJAR ini sangat bermanfaat, interaktif, dan relevan dengan kebutuhan mahasiswa Teknik Multimedia dan Jaringan. Penyampaian materi mengenai kombinasi *AI Prompting* dan *GitHub* memberikan wawasan praktis yang bisa langsung diterapkan dalam pengerjaan proyek-proyek perkuliahan maupun kolaborasi ke depannya. Meskipun pada kesempatan kali ini saya berhalangan hadir secara langsung di lokasi, materi dan tugas praktik yang diberikan tetap sangat aplikatif untuk dipelajari secara mandiri.

---

## Perintah Dasar Git yang Digunakan

```bash
git init
git add .
git commit -m "feat: initial commit project student task planner"
git remote add origin [https://github.com/ruviosst/NAMA_REPO.git](https://github.com/ruviosst/NAMA_REPO.git)
git push -u origin main
