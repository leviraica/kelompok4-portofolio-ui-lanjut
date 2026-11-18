# Team Portfolio Website - Kelompok 4

> Website portofolio tim untuk menampilkan profil anggota dan dokumentasi proyek.
> Tugas Besar Mata Kuliah UI Lanjut.

## 📌 Project Brief

### Goal
Membangun website portofolio tim yang memperkenalkan identitas, anggota, dan karya proyek kelompok.

**Indikator keberhasilan:**
- Seluruh anggota memiliki profil lengkap (nama, peran, keahlian, foto, bio).
- Minimal 3 proyek terdokumentasi lengkap (latar belakang, tujuan, fitur, teknologi, dokumentasi visual, kontribusi anggota).
- Kontak tim mudah diakses.
- Integrasi API berjalan dengan penanganan loading, error, dan empty state.
- Testing

### Kebutuhan Pengguna
- Melihat profil dan keahlian setiap anggota tim.
- Melihat daftar dan detail proyek yang pernah dikerjakan.
- Menghubungi tim melalui tautan profesional (email, GitHub, LinkedIn).

### Scope

**Yang Dikerjakan:**
- Home/Landing: identitas tim, ringkasan, nilai/fokus, highlight proyek.
- About Team: profil anggota (foto/avatar, keahlian, peran, bio).
- Project Showcase: kartu proyek (judul, ringkasan, kategori, teknologi) + pencarian & filter.
- Project Detail: latar belakang, tujuan, fitur, teknologi, dokumentasi visual, kontribusi anggota.
- Contact: email, GitHub, LinkedIn.
- Integrasi minimal 1 API (dengan loading, error, empty state).
- Reusable components (Navbar, ProfileCard, ProjectCard, Button, Footer, Modal, Form).
- State management (pencarian, filter, modal).
- testing (test case, hasil pass/fail terdokumentasi).
- Tampilan responsif desktop & mobile.

## 📋 Requirements

### Functional Requirements (FR)

| ID | Requirement | Kriteria Penerimaan |
|----|-------------|---------------------|
| FR-01 | Pengunjung dapat melihat profil setiap anggota | Nama, kompetensi, foto/avatar, bio tampil; pengunjung dapat membuka detail profil |
| FR-02 | Pengunjung dapat melihat daftar proyek | Minimal 3 kartu proyek: judul, ringkasan, kategori, teknologi |
| FR-03 | Pengunjung dapat membuka detail proyek | Latar belakang, tujuan, fitur, teknologi, dokumentasi visual, kontribusi anggota tampil |
| FR-04 | Pengunjung dapat mencari & memfilter proyek | Input pencarian & filter kategori berfungsi; hasil berubah sesuai state |
| FR-05 | Pengunjung dapat mengakses kontak tim | Tautan email, GitHub, LinkedIn dapat diklik dan mengarah ke tujuan benar |
| FR-06 | Website mengambil data dari API | Request/response berjalan; loading, error, empty state ditampilkan |

### Non-Functional Requirements (NFR)

| ID | Requirement | Kriteria Penerimaan |
|----|-------------|---------------------|
| NFR-01 | Layout responsif | konten tidak terpotong; tidak ada horizontal overflow |
| NFR-02 | Komponen reusable | Navbar, Card, Button, Footer, Modal, Form digunakan konsisten di seluruh halaman |
| NFR-03 | State management berjalan | Perubahan state (pencarian, filter, modal) langsung tercermin pada UI |
| NFR-04 | Unit testing tersedia | test case relevan, hasil pass/fail terdokumentasi |
| NFR-05 | Desain interaksi konsisten | Feedback (hover, loading, error), visibility of system status, error prevention diterapkan |

## 🎯 Milestone & Sprint

### Milestone

| ID | Milestone | Target | Indikator |
|----|-----------|--------|-----------|
| M1 | Struktur & Alur Profil | Akhir Minggu 11  | Halaman About Team & ProfileCard berfungsi; routing dasar jalan |
| M2 | Fitur & Integrasi Lengkap | Akhir Minggu 12  | Showcase, Detail, Contact, filter, dan API berjalan dengan state lengkap |
| M3 | Testing & Presentasi | Minggu 13–15 | Unit test lulus, UI konsisten, pitch deck siap |

### Sprint 1 - 4 Minggu 

- **Durasi:** 4 minggu
- **Sprint Goal:** Website portofolio tim dapat digunakan - pengunjung bisa melihat profil anggota, daftar proyek, detail proyek, dan kontak; integrasi API berjalan dengan loading/error/empty state; lulus testing.


