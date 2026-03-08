# DAC 2024 | Solar Energy Production Prediction with Machine Learning

Proyek ini dikembangkan dalam rangka mengikuti **Data Analysis Competition (DAC) 2024** yang diselenggarakan oleh **Institut Teknologi Sepuluh Nopember (ITS)**. Kompetisi ini menguji kemampuan peserta dalam menganalisis dataset dan membangun model prediksi menggunakan metode data science dan machine learning.

Tujuan dari proyek ini adalah untuk **memprediksi produksi energi surya** berdasarkan berbagai faktor lingkungan dan kondisi cuaca.

## Gambaran Proyek
Proses analisis dalam proyek ini meliputi beberapa tahapan utama:

1. **Pengumpulan Data**
   - Data cuaca
   - Data solar irradiance dari tahun 2014–2017
   - Dataset train dan test yang disediakan oleh kompetisi

2. **Data Preprocessing**
   - Menggabungkan data solar irradiance dari beberapa tahun
   - Membersihkan data
   - Menangani missing values menggunakan metode **K-Nearest Neighbor (KNN) Imputation**

3. **Exploratory Data Analysis (EDA)**
   - Analisis korelasi antar variabel
   - Visualisasi hubungan antara faktor lingkungan dengan produksi energi surya

4. **Pembangunan Model**
   - Model machine learning yang digunakan adalah **Random Forest Regression**
   - Pembagian data menggunakan metode **train-test split**

5. **Evaluasi Model**
   - Evaluasi performa model menggunakan **Root Mean Squared Error (RMSE)**
   - Analisis **feature importance** untuk mengetahui variabel yang paling berpengaruh terhadap prediksi

## Hasil Analisis
Hasil analisis menunjukkan bahwa beberapa faktor yang paling berpengaruh terhadap produksi energi surya antara lain:

- **Kelembaban (Humidity)**
- **Waktu dalam sehari**
- **Solar Zenith Angle**

Model **Random Forest Regression** yang dibangun mampu menghasilkan prediksi dengan nilai **RMSE sekitar 0.079**.

## Hasil Kompetisi
Proyek ini berhasil menempati **peringkat 52 dari 135 tim** pada leaderboard Kaggle.

Leaderboard kompetisi:  
https://www.kaggle.com/competitions/preliminary-round-dac-prs-2024/leaderboard

## Teknologi yang Digunakan
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
