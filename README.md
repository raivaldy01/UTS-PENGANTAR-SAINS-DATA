# UTS-PENGANTAR-SAINS-DATA
13119756
MOCHAMAD RAIVALDY
3KA18

Hasil:<br>
5. Jelaskan setiap langkah run yang sudah anda buat!<br>
penjelasan setiap langkah ada didalam file notebook google colab (*.ipynb)<br>

<br>3. Hasil prediksi tanggal 29 September 2021<br>
![image](https://user-images.githubusercontent.com/104556171/171327237-32f4e8bc-4a6b-463c-9c7d-2df7fdfa76d9.png)<br>
data pada tanggal 29 ini akan menjadi masukkan dari model untuk memprediksi harga aktual nya pada tanggal 29 sebelumnya yaitu USD DOLLAR 2690.419922 lalu didapatkan hasil model yang tampaknya memiliki performa terbaik adalah model RBF SVR. Model ini memperkirakan nilai USD DOLLAR 2669.13451364 ketika harga sebenarnya adalah USD DOLLAR 2690.419922 , jadi hanya turun sekitar USD DOLLAR 21
<br>
<br>

4. Model terbaik untuk menentukan prediksi tanggal 29 September 2021<br>
seperti yang dapat dilihat bahwa dapat dikatakan untuk dilakukan prediksi saham yaitu dengan menggunakan kernel RBF pada SVR (Support Vector Regression) memiliki akurasi yang cukup akurat karena komparasi antara ketiga model dari RBF, Linear, Polinomial hasil visualisasi nya jauh signifikan <br>
![image](https://user-images.githubusercontent.com/104556171/171327508-64f651f1-cd36-4bfa-b7cf-c92308d78915.png)<br>
oleh karena itu model RBF saat divisualisasikan pada hampir setiap garis nya terdapat titik titik yang merepresentasikan keberadaan original data atau nilai ADJ_CLOSE_PRICE di tiap tanggal, namun tidak semua original data berada pada garis model RBF sehingga akurasinya tidak 100% sempurna <br>
<br>
