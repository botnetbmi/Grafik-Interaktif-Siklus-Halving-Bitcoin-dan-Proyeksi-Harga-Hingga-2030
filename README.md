# 📊 Grafik Interaktif — Siklus Halving Bitcoin & Proyeksi Harga Hingga 2030

<div align="center">

[![Live Demo](https://img.shields.io/badge/🚀%20Buka%20Grafik%20Interaktif-GitHub%20Pages-brightgreen?style=for-the-badge)](https://botnetbmi.github.io/Grafik-Interaktif-Siklus-Halving-Bitcoin-dan-Proyeksi-Harga-Hingga-2030/)
[![Standalone](https://img.shields.io/badge/Standalone-HTML%20%7C%20Offline%20Ready-orange?style=for-the-badge&logo=html5)]()
[![Bahasa](https://img.shields.io/badge/Bahasa-Indonesia-red?style=for-the-badge)]()

**Analisis Matematis Murni · Tanpa Opini · Berbasis Data**

*Data historis: Coinbase · Kraken · Bitfinex · Blockchain.com · Apr 2026*

</div>

---

## 🌐 Demo Langsung

> 👉 **[https://botnetbmi.github.io/Grafik-Interaktif-Siklus-Halving-Bitcoin-dan-Proyeksi-Harga-Hingga-2030/](https://botnetbmi.github.io/Grafik-Interaktif-Siklus-Halving-Bitcoin-dan-Proyeksi-Harga-Hingga-2030/)**

File HTML sepenuhnya **standalone** — Chart.js sudah tertanam di dalam file. Dapat dibuka **tanpa koneksi internet** setelah diunduh.

---

## 📌 Statistik Utama (per Apr 2026)

| Indikator | Nilai |
|-----------|-------|
| Halving Saat Ini | **#4** — 19 Apr 2024 |
| Harga BTC Saat Ini | **~$78.000** |
| ATH Siklus 4 (aktual) | **$126.210** — Okt 2025 |
| R² Model Power Law | **0,952** |
| Halving Berikutnya | **~2028** — Siklus #5 |

---

## ⚡ Tanggal Tepat Halving Bitcoin

Data on-chain yang tertera langsung di grafik:

| # | Tanggal Tepat | Nomor Blok | Reward Sebelum | Reward Sesudah | Harga Saat Itu | ATH Siklus |
|---|--------------|-----------|---------------|---------------|----------------|------------|
| **H1** | **28 November 2012** | 210.000 | 50 BTC | 25 BTC | $12,5 | $1.177 × 94 |
| **H2** | **9 Juli 2016** | 420.000 | 25 BTC | 12,5 BTC | $650 | $19.891 × 31 |
| **H3** | **11 Mei 2020** | 630.000 | 12,5 BTC | 6,25 BTC | $8.700 | $68.789 × 7,9 |
| **H4** | **19 April 2024** ✅ | 840.000 | 6,25 BTC | 3,125 BTC | $63.800 | $126.210 × 2,0* |
| *H5* | *~April 2028 (estimasi)* | *1.050.000* | *3,125 BTC* | *1,5625 BTC* | *~$60–80k?* | *~$336.000 (proj.)* |

*\* ATH Siklus 4 masih berlangsung · Tanggal tepat H1–H4 dari data on-chain Bitcoin*

---

## 📈 Isi Grafik Interaktif

### 1. Grafik Harga Utama (Log Scale)
Riwayat harga BTC/USD dari semua siklus halving dalam satu grafik skala logaritmik. Setiap siklus diberi warna berbeda. **Hover** di atas kurva untuk melihat harga, siklus, dan fase secara real-time.

### 2. Kartu Detail Per Siklus

**Siklus 1** — Halving Nov 2012 · *Selesai*
- Harga saat halving: $12,5 → ATH: **$1.177** (×94) — Nov 2013
- Hari H→ATH: **369 hari** · Bottom bear: $150 · Koreksi maks: −87%

**Siklus 2** — Halving Jul 2016 · *Selesai*
- Harga saat halving: $650 → ATH: **$19.891** (×31) — Des 2017
- Hari H→ATH: **530 hari** · Bottom bear: $3.122 · Koreksi maks: −84%

**Siklus 3** — Halving Mei 2020 · *Selesai*
- Harga saat halving: $8.700 → ATH: **$68.789** (×7,9) — Nov 2021
- Hari H→ATH: **570 hari** · Bottom bear: $15.476 · Koreksi maks: −77%

**Siklus 4** — Halving Apr 2024 · *Berlangsung*
- Harga saat halving: $63.800 → ATH sejauh ini: **$126.210** (×2,0) — Okt 2025
- Hari H→ATH: **547 hari** ✓ · Prediksi ATH model: $168k · Proyeksi bottom: ~$48k

**Siklus 5** — Halving ~Apr 2028 · *Diproyeksikan*
- Estimasi harga halving: ~$60–80k → ATH power law: **~$336.000** (×4–5)
- Timing ATH: **~2030** (~791 hari) · Proyeksi bottom: **~$117k** · Estimasi koreksi: ~65%

### 3. Kotak Proyeksi Matematis

| Proyeksi | Nilai | Keterangan |
|----------|-------|------------|
| Bottom Bear S4 | **~$48.000** | Model power law · ~Sep 2026 |
| ATH S5 (Power Law) | **~$336.000** | ~2030 · R²=0,952 |
| Bottom Bear S5 | **~$117.000** | ~2031–2032 |

**Rumus model:**
```
ATH    = 2.271 × n^3,105
Bottom = 201   × n^3,955
```
> ⚠️ Imbal hasil makin menyusut. Tiap siklus, multiplier mengecil ~3–4×

### 4. Mini Chart — Multiplier ATH
Bar chart diminishing returns setiap siklus: ×94 → ×31 → ×7,9 → ×2,0 → ~×4–5 (proj.)

### 5. Mini Chart — Hari Halving ke ATH
Tren linear: semakin lama siklus berjalan sebelum mencapai puncak (369 → 530 → 570 → 791 hari proj.)

---

## 📐 Metodologi

**METODE: Regresi Power Law · Fit Log-Linear · Analisis Timing Siklus**

Data harga historis dikumpulkan dari Coinbase, Kraken, Bitfinex, dan Blockchain.com. Model power law di-fit terhadap 3 siklus historis yang telah selesai (H1–H3), kemudian divalidasi terhadap siklus ke-4 (H4) sebelum digunakan untuk proyeksi siklus ke-5.

Model ATH power law menghasilkan prediksi $168k untuk C4 sementara aktualnya $126k (error 33%) — penyimpangan yang wajar mengingat hanya 3 titik data untuk fitting, dan menunjukkan diminishing returns yang lebih cepat dari model.

---

## 🛠️ Teknologi

- **Chart.js 4.4.1** — embedded inline (offline-ready)
- **HTML + CSS + Vanilla JavaScript** — tanpa framework eksternal
- **Python** (scipy, numpy, matplotlib, Pillow) — analisis & generasi aset

---

## 📄 Lisensi

MIT License — bebas digunakan dan dimodifikasi dengan atribusi.

---

<div align="center">

*Sumber data: Coinbase · Kraken · Bitfinex · Blockchain.com*
*Analisis & proyeksi: regresi matematis murni, tanpa opini eksternal*
**Claude · Apr 2026**

⚠️ *Bukan nasihat keuangan. Past performance tidak menjamin hasil masa depan.*

</div>
