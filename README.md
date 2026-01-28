Analisis Big Data Kualitas Udara Global (AQI) 🌍
Repository ini berisi dokumentasi dan source code untuk Ujian Akhir Semester (UAS) Mata Kuliah Big Data & Predictive Analytics Lanjut di Universitas AMIKOM Yogyakarta.

Proyek ini mengimplementasikan pipeline Big Data lengkap menggunakan Apache Spark (PySpark) untuk menganalisis dataset Global Urban Air Quality.

👥 Anggota Kelompok
Muhammad Nurhaqie Windyarto (23.11.5758)
Davin Jonathan Sitindaon (23.11.5759)
Rendy Wijaya (23.11.5790)
Ridho Nugroho (23.11.5799)
Akmal Harizulhaq (23.11.5783)
🚀 Fitur & Implementasi
Sesuai ketentuan soal, proyek ini mencakup:

Ingestion: Simulasi penyimpanan data menggunakan struktur HDFS.
Batch Processing: Implementasi MapReduce menggunakan RDD untuk agregasi data.
EDA: Visualisasi distribusi AQI dan tren polusi per kota.
Preprocessing: Cleaning data dan manipulasi menggunakan Spark SQL.
Machine Learning: Komparasi model Linear Regression dan Random Forest Regressor untuk memprediksi nilai AQI.
📂 Struktur File
UAS_BIG_DATA_LANJUT.ipynb : File utama notebook (Source Code + Penjelasan).
global_air_quality_dataset.csv : Dataset yang digunakan.
📊 Hasil Evaluasi
Model dievaluasi menggunakan RMSE dan R2 Score. Catatan analisis mengenai hasil prediksi tersedia lengkap di dalam file notebook.
