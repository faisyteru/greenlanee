# GreenLane

Prototipe dashboard B2B untuk memilih, memantau, dan mengevaluasi mitra feeder trucking (first/last mile) berdasarkan total cost-to-serve, emisi karbon, dan keandalan pengiriman. Dibuat untuk BMC/BPC ITB Insight 2026.

> Prototipe demo. Seluruh data mitra dan angka prediksi adalah data dummy.

## Fitur

- **Dashboard**: KPI, filter koridor, peringkat mitra teratas, grafik cost-to-serve, peringatan, rekomendasi tindakan
- **Partner Scorecard**: tabel mitra dengan sortir dan filter, drawer detail (radar chart, tren 6 bulan)
- **Ranking (AHP-TOPSIS)**: bobot kriteria dapat diubah, ranking dihitung ulang langsung di browser, rincian kontribusi, jejak keputusan
- **Simulasi What-If**: ubah kenaikan BBM, volume dialihkan, mitra tujuan, armada, dan moda
- **Prediksi Risiko**: heatmap koridor x musim dan kartu mitra berisiko

## Menjalankan

Tanpa build. Buka `index.html` di browser, atau jalankan server lokal:

```bash
python3 -m http.server 8000
```

Lalu buka http://localhost:8000

## Deploy ke GitHub Pages

1. Push repo ini ke GitHub
2. Buka **Settings > Pages**, pilih **Source: GitHub Actions**
3. Workflow di `.github/workflows/pages.yml` akan men-deploy setiap push ke `main`

## Teknologi

HTML, CSS, dan JavaScript murni dalam satu file. Font Plus Jakarta Sans dari Google Fonts.

## Struktur

```
.
├── index.html
├── README.md
├── LICENSE
├── .gitignore
└── .github/workflows/pages.yml
```

## Lisensi

MIT
