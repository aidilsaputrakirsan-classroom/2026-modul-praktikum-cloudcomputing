# Laporan Penilaian Kelompok ignite – Kelas B
## Fase 6: Minggu Kuliah 15–16 (1 – 14 Jun 2026) — Final + UAS

> Lingkup: **C17 (Security, kelompok)** & **C18 (Dok C4 + Reflection, Mix per anggota)**. C19–C22 dinilai dosen. F6 = semua role prime (tanpa baseline floor).
>
> **Catatan:** role Desnita (10231030 = Lead QA & Docs) dan Putri (10231074 = Lead Frontend) sempat tertukar di penilaian awal; sudah dibetulkan. Nilai tiap mahasiswa memakai skor masing-masing (kuis/viva/git per NIM sesuai sumber).

---

### Informasi Kelompok

| Field | Detail |
|---|---|
| Nama Kelompok | ignite |
| Repo | cc-kelompok-ignite |
| Project | **E-commerce / Inventory** — katalog produk + statistik inventori, Auth + Item Service + API Gateway |

**Anggota:**

| Nama | NIM | Role |
|---|---|---|
| Andini Permata Dewanti | 10231014 | Lead Backend |
| Desnita Dwi Putri | 10231030 | Lead QA & Docs |
| Krishandy Dhanysa Pratama | 10231050 | Lead DevOps |
| Putri Rahmawati | 10231074 | Lead Frontend |

---

### A. C17 — Security Checklist & Best Practices (Kelompok)

| Kriteria | Bukti | Nilai |
|---|---|:---:|
| Container hardening | `USER` non-root di `backend/Dockerfile` | 70 |
| Input validation & CORS | validation di 4 file; CORS backend + auth + item-service | 70 |
| Secrets management | env-based config; tidak ada hardcoded SECRET_KEY | 70 |
| Network & gateway | **rate limiting tidak ditemukan**; tanpa commit security hardening eksplisit di F6 | 62 |

**Nilai C17: 68** · **Grade: B**

---

### B. C18 — Dokumentasi C4 + Reflection Paper (Mix, per anggota)

**Komponen kelompok (C4 + README):** `docs/architecture.md`, README. Base dokumentasi memadai (80).

**Reflection paper per anggota:** keempat anggota menulis reflection paper di `docs/reflection-paper/<NIM>_*.md` (volume besar, 7–19KB).

| NIM | Nama | Reflection | C18 |
|---|---|---|:---:|
| 10231014 | Andini Permata Dewanti | `docs/reflection-paper/10231014-LeadBackend.md` (~19KB, paling lengkap) | **86** |
| 10231030 | Desnita Dwi Putri | `docs/reflection-paper/10231030-LeadQADocs.md` (~7KB) | **82** |
| 10231050 | Krishandy Dhanysa Pratama | `docs/reflection-paper/10231050-LeadDevops.md` (~8.4KB) | **84** |
| 10231074 | Putri Rahmawati | `docs/reflection-paper/10231074-LeadFrontend.md` (~10KB) | **84** |

---

### C. Ringkasan untuk Gradebook

**C17 — Security (4%):** semua anggota **68**

**C18 — Dok C4 + Reflection (6%):**

| NIM | Nama | Skor |
|---|---|:---:|
| 10231014 | Andini Permata Dewanti | **86** |
| 10231030 | Desnita Dwi Putri | **82** |
| 10231050 | Krishandy Dhanysa Pratama | **84** |
| 10231074 | Putri Rahmawati | **84** |
