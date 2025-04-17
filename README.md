Klasifikasi Merek Mobil Menggunakan Decision Tree
Proyek ini bertujuan untuk membangun model machine learning yang dapat mengklasifikasikan mobil ke dalam merek asalnya — seperti Amerika Serikat, Jepang, dan Eropa — berdasarkan beberapa fitur mobil dengan menggunakan *Decision Tree Classifier*.

Deskripsi Dataset 
Dataset yang digunakan adalah *cars.csv*, yang berisi berbagai spesifikasi mobil dan asal mereknya. Fitur-fitur utama meliputi:  
- Tenaga Kuda (Horsepower)  
- Isi Silinder (Cubic Inches)  
- Berat (Weight)  
- Tahun Model (Model Year)  
- Konsumsi Bahan Bakar (MPG - Miles per Gallon)  
- Akselerasi (Acceleration)  
- ...dan lainnya

Kolom target adalah:  
- Brand : Label kategorikal yang menunjukkan apakah mobil berasal dari Amerika Serikat, Jepang, atau Eropa.

Alur Proyek
1. Pra-pemrosesan Data
   Memilih fitur numerik untuk pelatihan model.

2. Pelatihan Model 
   Menggunakan *Decision Tree Classifier* dari pustaka scikit-learn.  
   Dataset dibagi menjadi data pelatihan (70%) dan data pengujian (30%).

3. Evaluasi
   Evaluasi dilakukan dengan menggunakan nilai akurasi.  
   Struktur decision tree divisualisasikan menggunakan `plot_tree()`.
