# Clustring Unsupervised Learning 

## Persiapan Data 
Dalam tahap ini,proyek dimulai dengan mengimpor data.Kemudian,melakukan eksplorasi data awal dengan menghapus missing value dan visualisasi persebaran data untuk memahami struktur dan formatnya sebelum melangkah ke langkah selanjutnya.
## Pencarian Parameter Terbaik 
Dalam tahap ini, akan dicari parameter terbaik untuk model KMeans Clustering Anda menggunakan dua metode:

- ### Silhouette Score:
  Silhouette score digunakan untuk mengukur seberapa dekat setiap titik dalam sebuah cluster dengan titik-titik dalam cluster yang sama dibandingkan dengan cluster yang lain. Semakin tinggi silhouette score, semakin baik.
- ### Elbow Method:
  Metode ini melibatkan penghitungan inersia (within-cluster sum of squares) untuk jumlah cluster yang berbeda. Ketika jumlah cluster meningkat, inersia cenderung turun. Pada titik di mana penurunan inersia mulai melambat (bentuk mirip "siku" pada grafik), itu adalah indikasi bahwa jumlah cluster tersebut adalah pilihan yang baik.
## Pemodelan 
Setelah menentukan jumlah cluster yang optimal menggunakan metode-metode di atas, proyek ke tahap pemodelan. Dalam proyek ini, digunakan algoritma KMeans Clustering untuk mengelompokkan data menjadi cluster-cluster berdasarkan pola-pola yang ada dalam data. Model ini akan membantu Anda memahami struktur internal dari data dan mengidentifikasi pola-pola yang mungkin sulit dilihat secara manual.

## Visualisasi Persebaran
Setelah model KMeans telah dilatih, langkah terakhir adalah memvisualisasikan hasil clustering dengan menggunakan teknik visualisasi scatter plots yang membedakan warna untuk setiap cluster. Ini akan membantu dalam memahami dengan lebih baik bagaimana data terbagi menjadi kelompok-kelompok berbeda berdasarkan karakteristiknya.
