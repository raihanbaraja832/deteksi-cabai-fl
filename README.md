# Deteksi Hama & Penyakit Cabai (Federated Learning)

Halaman uji coba model global hasil simulasi Federated Learning (FedAvg) untuk proyek ASDA IPB
"Sistem Deteksi Hama dan Penyakit Tanaman Cabai Menggunakan Federated Learning Berbasis Mobile".

- **Kamera Langsung**: deteksi real-time dari kamera HP/laptop (inferensi di browser, onnxruntime-web).
- **Unggah Foto**: prediksi dari satu citra.
- **Hasil Simulasi**: muat `per_ronde.csv`, `perbandingan.csv`, `fairness.csv` hasil `fl_cabai.py`.

Model dimuat dari `model_cabai.js` (dibuat oleh `ekspor_web.py`). Ganti file ini untuk memperbarui model.
Tidak ada citra yang dikirim ke server; semua proses terjadi di perangkat pengguna.
