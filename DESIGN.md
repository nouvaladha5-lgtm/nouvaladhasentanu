# Design Direction — Studio-Grade Typography & Swiss Technical Grid (DESIGN.md)

## 1. Filosofi & Konsep Tipografi
- **Standar:** Studio Desain Profesional (Editorial Swiss Technical Grid).
- **Pendekatan:** Sistem Tipografi Triad (*Triad Typography System*), memadukan sans-serif geometris, sans-serif humanis, dan monospace teknis.
- **Karakter:** Bebas dari kesan template AI generik; memiliki hierarki ketat, kerning rapat pada judul, keterbacaan proporsional pada paragraf, dan presisi tabular pada data teknis.

## 2. Sistem Triad Font (Google Fonts)
1. **Headings (H1, H2, H3, H4) & Brand Logo:**
   - **Font:** `Space Grotesk` (Weights: 400, 500, 700)
   - **Karakter:** Geometris modern, berbobot, tajam.
2. **Body Text / Paragraf:**
   - **Font:** `Plus Jakarta Sans` (Weights: 400, 500, 600)
   - **Karakter:** Ergonomis, bersih, sangat nyaman dibaca untuk teks panjang.
3. **Label Teknis, Nomor Indeks, Tag Stack & Tombol:**
   - **Font:** `JetBrains Mono` (Weights: 400, 500)
   - **Karakter:** Monospace presisi tinggi, tabular numerals, ketelitian blueprint.

## 3. Aturan Micro-Typography
- **Hero Title (H1):**
  - Ukuran: `font-size: clamp(2.75rem, 6vw, 4.75rem)`
  - Ketebalan: `font-weight: 600` (dipadukan dengan `font-normal` dan `font-bold` berkontras)
  - Jarak Huruf: `letter-spacing: -0.04em` (sangat rapat dan kokoh)
  - Tinggi Baris: `line-height: 1.05`
  - Kontras Visual: Kata kunci nama diberi aksen warna **#0052FF (Klein Blue)** dan kombinasi bobot font berbeda.
- **Section Headings (H2):**
  - Jarak Huruf: `letter-spacing: -0.03em`
  - Tinggi Baris: `line-height: 1.15`
- **Label Monospace & Badges:**
  - Ukuran: `11px` (atau `0.75rem`)
  - Gaya: `text-transform: uppercase`
  - Jarak Huruf: `letter-spacing: 0.12em` (renggang dan teratur)
- **Paragraf Body:**
  - Ukuran: `16px` (`1rem`)
  - Tinggi Baris: `line-height: 1.65`
  - Warna: `#475569` (Muted Cobalt)
  - Batasan Lebar: `max-width: 60ch` (panjang kolom editorial ideal agar mata tidak lelah)
- **Rendering Global:**
  - `-webkit-font-smoothing: antialiased`
  - `-moz-osx-font-smoothing: grayscale`
  - `font-variant-numeric: tabular-nums`
  - `text-rendering: optimizeLegibility`
