# 🛒 E-Commerce Customer Segmentation (RFM Analysis)

## 📌 Deskripsi Proyek
<img width="1739" height="903" alt="ecommerce-rfm-segmentation" src="https://github.com/user-attachments/assets/2136caa5-f6a1-4a2e-85b1-59e9f1310fea" />

Proyek ini mengimplementasikan teknik RFM (Recency, Frequency, Monetary) untuk menganalisis perilaku pelanggan *e-commerce*. Tujuannya adalah mengidentifikasi segmen pelanggan bernilai tinggi dan memberikan rekomendasi strategis untuk meningkatkan retensi.

## 🛠️ Tech Stack
* **Data Processing:** Python (Pandas) di VS Code
* **Data Visualization:** Microsoft Power BI
* **Dataset:** Olist Brazilian E-Commerce Public Dataset

## 📊 Insight Utama & Rekomendasi Bisnis
Berdasarkan visualisasi Power BI, ditemukan dua *insight* kritis:
1. **Dominasi Churn (71%):** Sebagian besar pelanggan masuk ke segmen *Lost/Churned* (tidak bertransaksi > 6 bulan). 
2. **Potensi Pendapatan Tertidur:** Segmen *Churn* tersebut secara historis menyumbang total pendapatan terbesar ($16.5 Juta).
* **Rekomendasi:** Perusahaan perlu memprioritaskan kampanye *re-engagement* atau retargeting agresif (seperti promo eksklusif "Welcome Back") untuk segmen ini dibandingkan hanya fokus pada akuisisi pelanggan baru.

## 🚀 Cara Mereproduksi
1. Ekstrak data Olist ke folder `data/`.
2. Jalankan notebook `01_RFM_Analysis.ipynb` untuk preprocessing.
3. Buka file Power BI menggunakan `rfm_data_clean.csv`.
