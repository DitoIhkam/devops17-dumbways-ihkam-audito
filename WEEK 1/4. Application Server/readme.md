## 1. Perbedaan Monolith dan Microservice

# A. Monolith
* Biasanya, arsitektur monolitik memiliki satu basis data tunggal yang digunakan oleh semua komponen aplikasi.
* Pemeliharaan, pengujian, dan penyebaran perubahan pada aplikasi monolitik dapat menjadi lebih kompleks karena setiap perubahan harus mempengaruhi dan diuji secara menyeluruh pada aplikasi keseluruhan.
* Skalabilitas aplikasi monolitik terbatas karena setiap komponen harus diperlakukan sebagai satu kesatuan dan dapat mengakibatkan overhead yang signifikan saat jumlah pengguna dan beban meningkat.

# B. Microservice
* Skalabilitas aplikasi microservice lebih fleksibel karena masing-masing layanan dapat ditingkatkan secara independen sesuai kebutuhan.
* Pemeliharaan, pengujian, dan penyebaran perubahan pada aplikasi microservice dapat lebih mudah dan cepat karena perubahan hanya mempengaruhi layanan yang terkait.
* Namun, pengelolaan dan pemantauan lingkungan distribusi dapat menjadi lebih kompleks dalam arsitektur microservice.

## 2. Deploy Aplikasi wayshub-frontend (NodeJS)

Dalam mendeploy aplikasi wayshub-frontend, disini saya akan mengacu pada website https://github.com/dumbwaysdev/wayshub-frontend. Berikut untuk langkah-langkah nya 

1. Buat folder direktori dengan menggunakan perintah mkdir (nama folder). Dalam contoh disini saya menggunakan perintah mkdir wayshub, untuk membuat folder yang bernama wayshub.
![alt text](https://github.com/DitoIhkam/devops17-dumbways-ihkam-audito/blob/main/WEEK%201/4.%20Application%20Server/1.png?raw=true)

2. Pindah ke dalam file direktori yang sudah kita buat dengan perintah cd (nama folder). Dalam hal ini saya menggunakan perintah cd wayshub.
![alt text](https://github.com/DitoIhkam/devops17-dumbways-ihkam-audito/blob/main/WEEK%201/4.%20Application%20Server/2.png?raw=true)

3. Duplikat repositori wayshub-frontend di github kedalam server kita dengan menggunakan perintah git clone (nama website). Dalam hal ini saya mengganakan perintah git clone https://github.com/dumbwaysdev/wayshub-frontend
![alt text](https://github.com/DitoIhkam/devops17-dumbways-ihkam-audito/blob/main/WEEK%201/4.%20Application%20Server/3.png?raw=true)

5. Kita perlu mengintall npm didalam folder ini, untuk memunculkan node modules yang kita perlukan untuk menjalankan wesbite node.js. caranya ketik perintah npm install. Berikut untuk prosesnya.
![alt text](https://github.com/DitoIhkam/devops17-dumbways-ihkam-audito/blob/main/WEEK%201/4.%20Application%20Server/4.png?raw=true)

6. Yang terakhir, kita jalankan repositorinya dengan cara ketik npm start. Setelah dijalankan, buka browser dan ketikan ip ubuntu server ke dalam browser. Maka akan muncul website wayshub-frontend yang sudah kita duplikat tadi.
![alt text](https://github.com/DitoIhkam/devops17-dumbways-ihkam-audito/blob/main/WEEK%201/4.%20Application%20Server/Screenshot%20(186).png?raw=true)
