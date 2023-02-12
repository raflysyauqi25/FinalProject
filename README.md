# FinalProject- stage1

Insight yang telah didapatkan dari EDA sebagai berikut:
88% data merupakan user dengan risk flag 0
Data didominasi oleh user dengan martial status single, no car ownership, rented house ownership, dan user dengan current job years 3-5 tahun
Presentase user yang berhasil membayar loan relative kecil untuk semua data kategorik (rata-rata kurang dari 20%)
Distribusi income, age, dan experience uniform
Distribusi data numerik untuk data dengan risk flag 1 hampir sama
Perbandingan data kategorik dengan risk flag 0 dan dengan risk flag 1 hampir sama

Dari data yang diperoleh cukup sulit untuk menentukan alasan user gagal melakukan pembayaran, karena sebagian besar distribusi datanya uniform. sehingga kami berhipotesa bahwa alasan user gagal melakukan pembayaran yaitu total loan nya. Untuk mengatasi permasalahan tersebut dan mengurangi default rate dan revenue loss, kami merekomendasikan untuk melakukan segmentasi customer, dimana customer akan dibagi ke dalam beberapa tier berdasarkan data customer, dan jumlah pinjamannya berdasarkan tier customernya.
