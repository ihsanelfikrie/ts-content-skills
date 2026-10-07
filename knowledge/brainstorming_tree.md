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

## 📌 Studi Kasus 1: "Launching Photobox Baru Tegoer Sapa"

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

---

## 📌 Studi Kasus 2: "Kencan Hemat Akhir Bulan Mahasiswa Banjarbaru"

```mermaid
graph TD
    ROOT2["🎯 TOPIK BESAR: Kencan Hemat Akhir Bulan Mahasiswa"]

    ROOT2 --> C_BUDGET["💰 ANGGARAN & BIAYA (Budget)"]
    C_BUDGET --> B1["Simulasi Budget: Kopi + Foto Cetak < 50k"]
    B1 --> B1_FMT["🎬 Reels/TikTok: Mini Vlog 'Ngedate 40 Ribuan di Aime'"]
    C_BUDGET --> B2["Rincian Harga Tiap Cabang Tegoer Sapa"]
    B2 --> B2_FMT["📑 Carousel: Infografis 'Pilihan Photobox Mulai 25k'"]

    ROOT2 --> C_SPOT["📍 PILIHAN SPOT KENCAN (Vibe/Location)"]
    C_SPOT --> S1["Vibe Romantis Redup Ala Hotel 605"]
    S1 --> S1_FMT["🎬 Reels/TikTok: POV Ngedate Klasik di Room 605"]
    C_SPOT --> S2["Vibe Nostalgia Rumah Kayu Grandpa's House"]
    S2 --> S2_FMT["📑 Carousel: Lookbook Ide Pose Kencan Berdua"]

    ROOT2 --> C_FEAR["😰 HAPUS RASA CANGGUNG (Pain Point)"]
    C_FEAR --> F1_2["Drama Cowok Kaku vs Cewek Heboh"]
    F1_2 --> F1_2_FMT["🎬 Reels/TikTok: Skit Komedi 'Tipe Pacar Saat Photobox'"]
```

---

## 📌 Studi Kasus 3: "Solusi Mati Gaya di Photobox (Anti-Kaku)"

```mermaid
graph TD
    ROOT3["🎯 TOPIK BESAR: Solusi Mati Gaya di Photobox"]

    ROOT3 --> P_COUPLE["💑 KHUSUS PASANGAN (Couple)"]
    P_COUPLE --> CP1["Pose Interaksi Santai (Bukan Peace Sign)"]
    CP1 --> CP1_FMT["📑 Carousel: Lookbook 5 Pose Kencan Anti-Mati-Gaya"]

    ROOT3 --> P_SOLO["👤 SENDIRIAN / OOTD (Solo Mirror)"]
    P_SOLO --> SL1["Mirror Selfie Cermin Gelombang Hijau Nolima"]
    SL1 --> SL1_FMT["🎬 Reels/TikTok: Trend Transisi OOTD Aesthetic"]

    ROOT3 --> P_PROPS["🕶️ MAKSIMALKAN PROPERTI (Props)"]
    P_PROPS --> PR1["Piringan Hitam & Kacamata di Sirkem"]
    PR1 --> PR1_FMT["🎬 Reels/TikTok: POV Jadi Model Majalah Indie"]
    P_PROPS --> PR2["Katalog Properti di 5 Cabang Tegoer Sapa"]
    PR2 --> PR2_FMT["📑 Carousel: Checklist 'Properti Wajib Dicoba'"]
```

---

## 🚀 Alur Setelah Pohon Cabang Ditampilkan (Approval & Dual Brief)

1. **User Memilih Ranting**: Pengguna memilih cabang/ranting yang paling cocok dengan strategi saat itu (misal: *"Pilih Ranting P_COUPLE: Lookbook Pose Kencan"*).
2. **Validasi Persetujuan**: Pengguna menyatakan *"Sah"*, *"Bungkus"*, atau memberikan catatan revisi kecil.
3. **Output Ekspor Otomatis**: AI langsung menghasilkan 2 format brief kerja:
   - **Brief Tim Konten**: Lengkap dengan shotlist visual, instruksi grafis, hook 3-lapis, dan kata kunci SEO Banjarbaru.
   - **Brief KOL/Influencer**: Teks pesan WhatsApp ramah siap copy-paste langsung ke talent/kreator (detail lokasi kafe, skenario video, benefit ngopi/foto, dan 3 deliverables wajib: 1 Reels + 3 IG Stories).
   - **Tabel Ringkasan Ekspor**: Siap disalin ke Google Docs / Notion.
