## Penerapan Teori Graf Isomorpis

### 1. Bidang Biometrik (Ekstraksi Fitur Pada Wajah dan Telapak Tangan)
Pada [1] penerapan teori graf isomorpis digunakan untuk mendapatkan fitur baru yang didapatkan dari 2 graf yang isomorpis. Penulis [1] menyebut fitur tersebut dengan istilah *fusion of keypoints*. Tahap pertama dilakukan ekstrasi fitur pada wajah dan telapat tangan menggunakan metode *Scale Invariant Feature Transform* (SIFT) untuk mendapatkan titik-titik fitur (*keypoints*). Kemudaian dari titik-titik tersebut dilakukan pengelompokan (*clustering*). Dari titik-titik fitur yang didapatkan dari proses ekstraksi fitur dan *clustering*, akan dibuat grafnya. Pada setiap graf dari fitur wajah dan telapak tangan akan dicari graf yang isomorpis. Untuk mendapatkan *fusion of keypoint* dilakukan dengan 2 metode *fusion* yaitu *sum rule* dan *concatenation rule*.

### 2. Proses secara umum
1) Akuisisi data gambar wajah dan telapak tangan
2) Menemukan keypoints menggunakan SIFT
3) Eliminasi keypoint-keypoint yang terlalu dekat menggunakan k-medoid cluster
4) Hasilkan isomorphic graph  (3.2,3.3)

### Refrensi

[1] [D. Kisku, P. Gupta and J. Sing, "Feature Level Fusion of Face and Palmprint Biometrics by Isomorphic Graph-Based Improved K-Medoids Partitioning", in Advances in Computer Science and Information Technology, 1st ed., T. Kim and H. Adeli, Ed. Springer Berlin Heidelberg, 2010, pp. 70-81.](https://drive.google.com/open?id=0B_30ewZCzNUMdmNrM1Y3NXoyeDg)
