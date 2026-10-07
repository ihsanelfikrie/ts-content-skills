# Framework Brainstorming: Pohon Percabangan Ide (Idea Branching Tree)

Framework ini digunakan ketika pengguna ingin memulai dari **Topik Besar / Tema Kampanye**, kemudian dipecah secara sistematis hingga menghasilkan rekomendasi tipe konten spesifik (Reels/TikTok vs Carousel).

---

## 🌳 Struktur 4 Tingkat Percabangan

```text
[Tingkat 1] Topik Besar / Tema Kampanye
   └── [Tingkat 2] Ranting Pertanyaan Kritis (5W + 1H Audiens)
          └── [Tingkat 3] Sudut Pandang / Angle Spesifik
                 └── [Tingkat 4] Rekomendasi Format Konten (Reels/TikTok vs Carousel Feed)
```

---

## 🧭 Panduan Matriks Keputusan Format Konten

| Karakteristik Kebutuhan Pesan | Format Paling Efektif | Alasan & Karakteristik |
|---|---|---|
| Membangun rasa penasaran (*curiosity*), emosi, atmosfer visual bergerak | **Video Pendek (Reels/TikTok)** | Menggunakan hook 3 detik, transisi, atau format POV/BTS untuk retensi tontonan tinggi. |
| Informasi padat, panduan rute/peta, perbandingan fitur, daftar harga | **Carousel Feed** | Mudah di-*swipe* berulang kali, memiliki tingkat penyimpanan (*save rate*) tinggi untuk dibaca ulang. |
| Pengumuman tanggal mendesak, promo flash diskon satu hari | **Single Post Feed / Story** | Pesan visual tunggal yang lugas (*hard selling*). |

---

## 📌 Studi Kasus: "Launching Photobox Baru Tegoer Sapa"

```mermaid
graph TD
    ROOT["🎯 TOPIK BESAR: Launching Photobox Baru Tegoer Sapa"]

    ROOT --> B_WHERE["📍 DIMANA LOKASINYA? (Where)"]
    B_WHERE --> W1["Clue / Teaser Fasad & Kafe Mitra"]
    W1 --> W1_FMT["🎬 Reels/TikTok: POV Nemu Hidden Gem Baru"]
    B_WHERE --> W2["Rute Akses & Peta Lokasi Jelas"]
    W2 --> W2_FMT["📑 Carousel: Infografis / Panduan Rute & Denah"]

    ROOT --> B_WHEN["⏰ KAPAN BUKANYA? (When)"]
    B_WHEN --> T1["Countdown Menjelang Hari H"]
    T1 --> T1_FMT["🎬 Reels/TikTok: Trend Transisi H-3 ke Hari H"]
    B_WHEN --> T2["Jadwal Jam Operasional & Sesi Perdana"]
    T2 --> T2_FMT["📑 Carousel: Q&A Slide / Info Operasional"]

    ROOT --> B_WHAT["✨ APA FITUR UNIKNYA? (What)"]
    B_WHAT --> F1["Sneak Peek Suasana Bilik & Mesin Cetak"]
    F1 --> F1_FMT["🎬 Reels/TikTok: BTS Persiapan Instalasi Mesin"]
    B_WHAT --> F2["Katalog Frame & Pilihan Lighting"]
    F2 --> F2_FMT["📑 Carousel: Lookbook Template Frame Baru"]

    ROOT --> B_HOW["💰 BERAPA BIAYA & CARA PAKAI? (How)"]
    B_HOW --> H1["Harga Launching / Promo Perdana"]
    H1 --> H1_FMT["📑 Carousel: Hard Selling / Promo Announcement"]
    B_HOW --> H2["Simulasi Cara Foto & Durasi Waktu"]
    H2 --> H2_FMT["🎬 Reels/TikTok: Talking Head Edukasi Cepat"]
```
