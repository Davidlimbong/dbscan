# Algoritma Clustering DBSCAN
___

**Instruksi**
  pada Kuis kali ini data yang digunakan adalah data `nasa_fire.csv`. Data tersebut memiliki 25937 observasi dan 3 kolom. Anda dapat sebelum melakukan proses cluster anda dapat melakukan eksplorasi data terlebih dahulu menggukan fungsi `str()` atau `glimpse()`. Berikut deskripsi dari kolom pada data `nasa_fire.csv` :
  
  - `latitude` : Titik latitude terjadinya kebakaran
  - `longitude` : Titik longitude terjadinya kebakaran
  - `confidence` : Tingat kepercayaan suatu kebakaran terjadi. selang nilai pada confidence dari 0 hingga 100.
  
___

## Konsep Dasar DBSAN

1. Dibawah ini mana pernyataan yang salah terkait DBSCAN?
  - [ ] DBSCAN menggunakan metode density-based.
  - [ ] dalam DBSCAN terdapat centroid yang menunjukkan pusat cluster.
  - [ ] DBSCAN sensitif terhadap perubahan nilai parameter.

2.  Apa yang terjadi pada hasil clustering bila nilai Eps dalam proses clustering diperluas dan nilai minPts tetap?
  - [ ] Jumlah cluster yang terbentuk semakin sedikit karena radius cakupan cluster lebih luas.
  - [ ] Data noise yang dihasilkan semakin banyak.
  - [ ] Jumlah cluster yang terbentuk tetap namun data noise semakin banyak.

3. Pernyataan yang tepat terkait optimasi nilai eps dibawah ini yaitu?
  - [ ] Nilai K dapat ditentukan oleh fungsi KNNdistplot dengan memasukkan nilai eps sebagai input.
  - [ ] Nilai eps optimum berada pada "knee" yang terbentuk pada plot KNNdisplot.
  - [ ] KNNdistplot dapat memberikan nilai eps optimum secara langsung.
  
# DBSCAN pada Spatial Data

4. Dengan menggunakan minPts = 100 berapa nilai Eps yang optimum menurut teknik "knee" plot ?
  - [ ] 0.8
  - [ ] 1.2
  - [ ] 2.5
  - [ ] 3.8

5. Dengan menggunakan minPts = 100 dan Eps yang optimal berapa banyak cluster dan data noise yang dihasilkan ?
 - [ ] 6 Cluster dengan 448 data noise
 - [ ] 3 cluster dengan 33 data noise
 - [ ] 14 Cluster dengan 924 data noise
 
6. Apabila anda hanya menggunakan data `nasa_fire` dengan confidence diatas 80 dan dalam proses clustering menggunakan minpts = 10 serta eps = 0.8 maka pernyataan yang tepat adalah ?
  - [ ] Terdapat 250 data noise
  - [ ] Cluster yang dihasilkan sebanyak 36 cluster
  - [ ] cluster 15 merupakan cluster dengan anggota cluster terbanyak
