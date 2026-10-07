# 📸 Tegoer Sapa Content Strategist — Claude Skill & Subagent

Repository resmi untuk instruksi, knowledge base, katalog konten, dan SOP subagent AI **"Tegoer Sapa Content Strategist"**. Dirancang khusus untuk memandu pembuatan konsep media sosial (Instagram Reels, TikTok, Carousel Feed) untuk seluruh cabang **Tegoer Sapa Photobooth** di area Banjarbaru.

---

## 🎯 Nilai Utama
1. **Memudahkan Tim Desainer & Kreator**: Output dirancang detail dan spesifik, bukan sekadar teks copywriting umum, melainkan instruksi syuting shot-by-shot dan panduan grafis siap eksekusi.
2. **Katalog Konten Terintegrasi**: Memastikan variasi format konten video (POV, Talking Head, BTS, Mini Vlog, Skit, Transisi) dan feed (Infografis, Meme, Lookbook, Q&A, Hard Selling) agar kalender konten tidak monoton.
3. **Berorientasi Masalah Nyata (Discovery First)**: Mengupas tuntas keresahan audiens (harga, durasi, privasi, rasa canggung/kaku) sebelum masuk ideasi.
4. **Alur Kerja Terstandarisasi (3-Phase SOP)**: Interaktif bertahap dan siap ekspor langsung ke tabel Google Docs / Notion.

---

## 📂 Struktur Direktori

```text
Tegoersapa content skills/
├── README.md                 # Dokumentasi lengkap repository & panduan integrasi
├── SKILL.md                  # Spesifikasi resmi Skill dengan YAML frontmatter
├── SYSTEM_PROMPT.md          # Prompt mentah siap copy-paste ke Claude Projects / Custom Instructions
├── CLAUDE.md                 # Petunjuk operasional Claude saat bekerja di repo ini
├── .gitignore                # Konfigurasi ignore file macOS / cache
├── knowledge/                # Basis pengetahuan & data pendukung
│   ├── dinur_content_framework.md # Framework Analisa Konten & Batching Ide (Bang Dinur)
│   ├── branches.md           # Detail spesifikasi 5 cabang & fitur khasnya
│   ├── viral_content_vault.md # Brankas Konten Viral (5 Serial Konten, Subkultur Estetika, Anti-Friksi)
│   ├── social_media_playbook.md # Playbook Social Media Specialist (Algoritma, SEO, Psikologi Viral)
│   ├── content_pillars.md    # 5 pilar konten & tujuan strategis (Reach/Saves/Conversion)
│   ├── hook_bank.md          # Bank kalimat hook 3 detik pemicu rasa penasaran
│   ├── brainstorming_tree.md # Framework pohon percabangan ide (Mermaid Tree)
│   ├── content_catalog.md    # Katalog format video pendek & carousel feed
│   ├── workflow_sop.md       # Panduan rinci SOP (Pohon Ide & SOP 3 Fase)
│   └── audience.md           # Profil persona UIN Antasari & Gen Z Banjarbaru
└── examples/
    └── simulasi_chat.md      # Contoh dialog lengkap dari Fase 1 sampai Fase 3
```

---

## ⚡ Perintah Cepat (Shortcuts)
- `/brainstorm [topik]` : Otomatis buatkan diagram pohon percabangan ide (Mermaid Tree).
- `/batching [topik]` : Susun bank ide mingguan dengan metode 5 funnel langkah Bang Dinur (*Niche ➔ Value ➔ Pillar ➔ Generic ➔ Specific*).
- `/bedah [nama cabang]` : Langsung masuk ke Fase 1 (Discovery) untuk cabang tersebut.
- `/hook [cabang/topik]` : Tampilkan 5 opsi hook 3 detik variatif dari Hook Bank.
- `/evaluasi [data/grafik/masalah]` : Bedah performa konten menggunakan kurva retensi Bang Dinur dan analisa "So What?".
- `/tukar` : Berikan variasi/alternatif format baru untuk Opsi A atau Opsi B di Fase 2.

---

## 🚀 Cara Menggunakan di Claude

### Opsi 1: Claude.ai (Web / Pro / Team Projects)
1. Buka [Claude.ai](https://claude.ai) dan buat **Project** baru (misal: *"Tegoer Sapa Creative Lab"*).
2. Di bagian **Set Custom Instructions** (Project Instructions), buka file [`SYSTEM_PROMPT.md`](file:///Users/macbook/Tegoersapa%20content%20skills/SYSTEM_PROMPT.md) lalu salin seluruh isinya.
3. Di bagian **Project Knowledge**, Anda bisa mengunggah file-file dari folder `knowledge/` (`branches.md`, `viral_content_vault.md`, `social_media_playbook.md`, `content_pillars.md`, `hook_bank.md`, `brainstorming_tree.md`, `content_catalog.md`, `audience.md`, `workflow_sop.md`).
4. Mulai percakapan dengan menyebutkan nama cabang (misal: *"Hari ini kita mau bikin konten Hatara Coffee"*).

### Opsi 2: Claude Desktop / Claude Custom Instructions
1. Buka aplikasi Claude Desktop atau profil akun Claude.
2. Masuk ke **Settings** → **Custom Instructions**.
3. Tempelkan teks dari [`SYSTEM_PROMPT.md`](file:///Users/macbook/Tegoersapa%20content%20skills/SYSTEM_PROMPT.md).

### Opsi 3: Claude Code / Antigravity / Cursor IDE
1. Buka folder `Tegoersapa content skills` sebagai active workspace Anda.
2. Asisten AI akan otomatis mematuhi aturan kerja di [`CLAUDE.md`](file:///Users/macbook/Tegoersapa%20content%20skills/CLAUDE.md) dan [`SKILL.md`](file:///Users/macbook/Tegoersapa%20content%20skills/SKILL.md).

---

## 💡 Katalog Tipe Konten (Fase 2)

| Format | Kategori | Penjelasan Ringkas & Contoh |
|---|---|---|
| **Video Pendek** | **POV** | Pengalaman langsung orang pertama (*"POV nemu hidden gem photobox"*). |
| | **Talking Head** | Edukasi kilat bicara ke kamera membedah fitur/tips pose. |
| | **BTS** | Keseruan di balik bilik & proses mesin cetak foto. |
| | **Mini Vlog** | Cerita nongkrong di kafe mitra ditutup sesi foto. |
| | **Skit / Sketsa** | Komedi singkat seputar kecanggungan pose/rebutan frame. |
| | **Trend Transisi** | Transisi mulus diiringi hentakan audio viral. |
| **Carousel Feed** | **Infografis** | Panduan visual bertahap / checklist tips lighting & pose. |
| | **Meme / Humor** | Validasi keresahan audiens lewat humor pop-culture. |
| | **Lookbook Pose** | Grid referensi foto asli pengunjung (bareng doi/bestie). |
| | **Q&A Slide** | FAQ cara bayar, durasi waktu, dan nomor antrean. |
| | **Hard Selling** | Tampilan harga menonjol (Rp25k / Rp35k) & promo frame baru. |

---

## 🔄 SOP 3 Fase (Wajib Bertahap)

1. **Fase 1: Bedah Masalah (Discovery)**
   - Input: Nama cabang.
   - Output: 5-7 keraguan / keresahan audiens seputar cabang tersebut.
   - Penutup: *"Masalah nomor berapa yang mau kita jadikan materi konten hari ini?"*

2. **Fase 2: Ideasi A/B Testing**
   - Input: Nomor masalah yang dipilih.
   - Output: Memilih tipe dari Katalog Konten:
     - **Opsi A (Video Reels/TikTok)**: Sebutkan `[Tipe Video yang dipilih dari katalog]`, Hook, Alur Adegan Visual, Ide Audio.
     - **Opsi B (Carousel Feed)**: Sebutkan `[Tipe Feed yang dipilih dari katalog]`, Headline Slide 1, Struktur Copywriting per slide, Arahan Elemen Visual.
   - Penutup: *"Ide ini sudah pas, atau ada yang perlu direvisi sebelum masuk draf final?"*

3. **Fase 3: Persiapan Ekspor (Draft Final)**
   - Input: Kata sepakat (*"Sah"*, *"Setuju"*, atau *"Bungkus"*).
   - Output: Tabel Markdown rapi berkolom (Tanggal, Cabang, Format Konten, Hook/Headline, Arahan Visual/Desain).
   - Penutup: *"Tabel sudah siap disalin ke Google Docs!"*

---

## 🏢 5 Cabang & Fitur Tegoer Sapa Photobooth

1. **Grandpa's House (Hatara Coffee — Jl. Kembang Bakung No. 12)**: Fasad rumah kayu vintage, jendela kayu (krepyak) interaktif (bisa buka-tutup untuk pose luar-dalam), QR antrean online (santai ngopi tanpa antre berdiri), layar sentuh zoom in/out & mirror, filter Original/Vintage, frame mangkok ayam jago & tekstur kayu klasik.
2. **Twin Photobox (Nolima Coffee)**: Twin photobox pertama di Banjarbaru, tirai merah & properti cermin gelombang hijau (*green wavy mirror*), 2 ruangan mini bersebelahan dengan 2 kamera terpisah (Rp35.000 / 5 mnt, countdown 10 detik/take), retake spesifik pada take terakhir (bebas pilih ulang kamera kiri atau kanan).
3. **Hotel Room Concept (Aime Coffee)**: Fasad pintu kamar hotel klasik nomor 605, interior penuh cermin untuk mirror selfie, rak tas khusus, harga mulai Rp25.000, lampu Normal (santai) vs Spotlight (tegas/studio), opsi angle kamera kiri/kanan, frame kalender unik.
4. **Library Theme (Warkop Sirkem)**: Estetika perpustakaan klasik / dark academia, rak buku ensiklopedia & majalah fashion (Vogue, Dior), piringan hitam (Arctic Monkeys, The 1975), camcorder lawas, kacamata hitam, convex mirror, tirai damask, tombol fisik Cut & Mirror On/Off, lampu sorot teater, frame koran tempo dulu ("SOERAT KABAR" / "TODAY IN HISTORY").
5. **Kean Coffee Branch (Kean Coffee)**: Tirai marun & krem geser, bola disko gantung (*sparkling disco ball*), convex mirror, sistem pembayaran All Payment (QRIS di monitor atau cash di kasir), Rp33.000 / 5 menit, **retake sepuasnya** selama 5 menit, mode Spotlight & Room Light, filter Original/Polaroid/Sepia/Grayscale.
