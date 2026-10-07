# 📸 Tegoer Sapa Content Strategist — Claude Skill & Subagent

Repository resmi untuk instruksi, knowledge base, dan SOP subagent AI **"Tegoer Sapa Content Strategist"**. Dirancang khusus untuk memandu pembuatan konten media sosial (Instagram Reels, TikTok, Carousel Feed) untuk seluruh cabang **Tegoer Sapa Photobooth** di area Banjarbaru.

---

## 🎯 Tujuan & Nilai Utama
1. **Memudahkan Tim Desainer & Kreator**: Output dirancang detail dan spesifik, bukan teks copywriting umum, melainkan panduan visual riil (shot-by-shot, elemen grafis, tipe vektor, palet warna).
2. **Berorientasi Masalah Nyata (Discovery First)**: Membedah keresahan terpendam audiens (harga, durasi, rasa canggung/kaku, privasi) sebelum membuat konten.
3. **Alur Kerja Terstandarisasi (3-Phase SOP)**: Menjamin proses ideasi yang rapi, interaktif, dan mudah diekspor ke tabel dokumen kerja (Google Docs / Notion).

---

## 📂 Struktur Direktori

```text
Tegoersapa content skills/
├── README.md               # Dokumentasi lengkap repository & panduan penggunaan
├── SKILL.md                # Spesifikasi standar Skill dengan YAML frontmatter
├── SYSTEM_PROMPT.md        # Prompt mentah siap copy-paste ke Claude Projects / Custom Instructions
├── CLAUDE.md               # Petunjuk operasional Claude saat bekerja di repo ini
├── .gitignore              # Konfigurasi ignore file macOS / cache
├── knowledge/              # Basis pengetahuan & data pendukung
│   ├── branches.md         # Detail spesifikasi 5 cabang & fitur khasnya
│   ├── audience.md         # Profil persona UIN Antasari & Gen Z Banjarbaru
│   └── workflow_sop.md     # Panduan rinci SOP 3 Fase (Discovery → A/B → Ekspor)
└── examples/
    └── simulasi_chat.md    # Contoh dialog lengkap dari Fase 1 sampai Fase 3
```

---

## 🚀 Cara Menggunakan di Claude

### Opsi 1: Claude.ai (Web / Pro / Team Projects)
1. Buka [Claude.ai](https://claude.ai) dan buat **Project** baru (misal: *"Tegoer Sapa Creative Lab"*).
2. Di bagian **Set Custom Instructions** (Project Instructions), buka file [`SYSTEM_PROMPT.md`](file:///Users/macbook/Tegoersapa%20content%20skills/SYSTEM_PROMPT.md) lalu salin seluruh isinya.
3. Di bagian **Project Knowledge**, Anda bisa mengunggah file-file di folder `knowledge/` (`branches.md`, `audience.md`, `workflow_sop.md`).
4. Mulai percakapan dengan menyebutkan nama cabang (misal: *"Hari ini kita mau bikin konten Hatara Coffee"*).

### Opsi 2: Claude Desktop / Claude Custom Instructions
1. Buka aplikasi Claude Desktop atau profil akun Claude.
2. Masuk ke **Settings** → **Custom Instructions**.
3. Tempelkan teks dari [`SYSTEM_PROMPT.md`](file:///Users/macbook/Tegoersapa%20content%20skills/SYSTEM_PROMPT.md).

### Opsi 3: Claude Code / Antigravity / Cursor IDE
1. Jadikan folder `Tegoersapa content skills` sebagai workspace Anda.
2. Asisten AI akan otomatis membaca petunjuk dari [`CLAUDE.md`](file:///Users/macbook/Tegoersapa%20content%20skills/CLAUDE.md) dan [`SKILL.md`](file:///Users/macbook/Tegoersapa%20content%20skills/SKILL.md).

---

## 🏢 Knowledge Base Ringkas: 5 Cabang Tegoer Sapa

| Cabang | Lokasi Mitra | Fitur Kunci & Keunikan | Frame & Suasana |
|---|---|---|---|
| **Grandpa's House** | Hatara Coffee | Fasad kayu vintage, jendela interaktif, QR antrean online, zoom/mirror kamera, filter vintage | Frame Ayam Jago / Tekstur Kayu |
| **Twin Photobox** | Nolima Coffee | Ruangan mini ganda, 2 kamera, cermin gelombang hijau (*wavy mirror*), retake per kamera (Rp35k / 5 mnt) | Cermin gelombang hijau |
| **Hotel Room 605** | Aime Coffee | Pintu kamar hotel 605, mirror selfie, gantungan tas, Lampu Normal & Spotlight, kamera kiri/kanan (Mulai Rp25k) | Frame Kalender unik |
| **Library Theme** | Warkop Sirkem | Rak buku perpustakaan klasik, piringan vinyl Arctic Monkeys & The 1975, convex mirror, kacamata retro | Frame "SOERAT KABAR" |
| **Kean Coffee** | Kean Coffee | All payment (QRIS / Cash), bola disko gantung, tirai marun & krem, Spotlight / Room Light, retake sepuasnya (Rp33k / 5 mnt) | Sparkling disco vibe |

---

## 🔄 SOP 3 Fase (Wajib Bertahap)

1. **Fase 1: Bedah Masalah (Discovery)**
   - Input: Nama cabang.
   - Output: 5-7 keraguan / keresahan audiens seputar cabang tersebut.
   - Penutup: *"Masalah nomor berapa yang mau kita jadikan materi konten hari ini?"*

2. **Fase 2: Ideasi A/B Testing**
   - Input: Nomor masalah yang dipilih.
   - Output: **Opsi A** (Video Reels/TikTok) dan **Opsi B** (Carousel Feed) lengkap instruksi visual.
   - Penutup: *"Ide ini sudah pas, atau ada yang perlu direvisi sebelum masuk draf final?"*

3. **Fase 3: Persiapan Ekspor (Draft Final)**
   - Input: Kata sepakat (*"Sah"*, *"Setuju"*, atau *"Bungkus"*).
   - Output: Tabel Markdown rapi berkolom (Tanggal, Cabang, Format Konten, Hook/Headline, Arahan Visual/Desain).
   - Penutup: *"Tabel sudah siap disalin ke Google Docs!"*

---

## 👥 Kontributor & Hak Cipta
Dikelola untuk tim kreatif & operasional **Tegoer Sapa Photobooth** — Banjarbaru, Kalimantan Selatan.
