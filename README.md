# Dashboard Kawasan Lapang Negeri Selangor

Dashboard statik untuk **GitHub Pages**. Semua logo PBT yang dimasukkan ialah fail yang dibekalkan dalam perbualan ini.

## Kandungan
- Peta Leaflet interaktif
- Data GeoJSON 2022, 2023, 2024 dan 2025
- 12 logo PBT Selangor
- Logo/elemen Warta
- Ikon medan: Tahun, PBT, Status Warta, Jenis/GTN3, Jumlah Kawasan, Keluasan dan Peta
- KPI, filter dan carta interaktif
- Popup polygon termasuk status/no. warta/tarikh warta jika tersedia

## Cara publish di GitHub Pages
1. Extract ZIP ini.
2. Buka repository GitHub anda.
3. Upload **semua kandungan folder** ini, bukan ZIP sahaja.
4. Pastikan `index.html`, `assets/` dan `data/` berada di root repository.
5. Pergi ke **Settings > Pages**.
6. Pilih **Deploy from a branch**.
7. Branch: `main`, folder: `/ (root)`.
8. Klik **Save**.
9. Tunggu beberapa minit sehingga pautan `https://<username>.github.io/<repository>/` tersedia.

## Nota data
- 2022: data kumulatif sehingga 2022.
- 2023–2025: data bagi tahun masing-masing.

## V4 – Tema Kemudahan Keselamatan
- Palet UI: #f8f3ed, #fffdfa, #fff8f0, #172236, #708094, #eadfd2, #e9782b, #c94d32, #f1a53a.
- Polygon kawasan lapang dibesarkan impak visualnya: hijau terang, opacity lebih tinggi dan outline lebih tebal.
- Status Warta menggunakan outline merah-jingga; status lain outline biru.
- Hover polygon menggunakan outline emas.


## Kumulatif rasmi 2022–2025
Dashboard kini menggunakan jadual Excel `TLA KUMULATIF` sebagai rujukan keluasan kumulatif rasmi mengikut PBT dan status Warta/Dalam Proses/Belum Warta. GeoJSON kekal digunakan untuk paparan spatial peta.

## Final boundary + cumulative configuration
- Sempadan Daerah Negeri Selangor: #4B5563, line + single dot, weight 1.05, opacity 0.56.
- Sempadan Pihak Berkuasa Tempatan Negeri Selangor: #6B7280, line + double dot, weight 0.85, opacity 0.46.
- Label menggunakan pusat polygon terbesar.
- Google Hybrid digunakan sebagai basemap.
- Fungsi kumulatif rasmi 2022–2025 daripada TLA KUMULATIF dikekalkan.

## Susunan halaman
- `Overview`: peta, GeoJSON dan analisis spatial/tahunan.
- `Analysis`: semua data **kumulatif rasmi 2022–2025** sahaja, termasuk KPI, trend, pecahan status dan jadual PBT.
- Kumulatif tidak lagi dipaparkan pada Overview.
