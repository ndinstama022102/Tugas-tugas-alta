# 21 Fundamental Performance Test
# Resume

## Performance Test
### Apa itu Performance Test?
- Teknik non functional testing untuk menentukan parameter sistem dalam hal responsif dan stabilitas dibawah berbagai beban (load) kerja,
- Performance testing mengukur kualitas atribut dari sistem seperti stabilitas, ketahanan (reliability), dan penggunaan sumber daya.

### Apa yang diukur dari Performance Test?
- Performa suatu aplikasi sampai suatu batas tertentu.
- Bukan merupakan functional-test
- Bisa dalam berbagai macam bentuk untuk memahami realibity, stabilty dan availability pada environment-nya.
  Contoh :
1. Mengamati response time ketika menjalankan request dalam jumlah yang sangat banayk.
2. Melihat suatu sistem berinteraksi dengan jumlah data yang cukup besar.

### Mengapa Performance Test Jarang Dilakukan?

Pada umumnya performance testing cukup mahal untuk diaplikasikan dan dijalankan, namun dapat dijadikan tolak ukur apakah sistem tersebut dapat mengakomodasi traffic yang ada.
Hal ini disebabkan karena pengetesannya memerlukan persiapan yang dimana beberapa kasus harus membuat environment terpisah dari production agar tidak tercampurnya data test dengan data production.
Environment ini ada juga yang membuatnya di server cloud yang biayanya bisa lebih besar dari environment production.

### Apa yang perlu diperhatikan dari performance test?

Dalam melakukan performance test biasanya yang menjadi perhatian adalah throughput dan response data-nya. 

### Contoh kasus performance test

Sebuah sistem baru yang akan di launch ke production, namun sebelum masuk ke production perlu dilakukan performance test untuk mengetahui throughput dan response time dari sistem tersebut.
Untuk informasi endpoint yang akan di test adalah :
1. /login
2. /beli-pulsa
3. /cek-out

### Contoh kasus performance Test
Langkah yang harus dilakukan :
1. Membuat test plan
2. Membuat script test
3. Melakukan performance test
4. Menganalisa hasil performance test

### Membuat Test plan
kenali yang dibutuhkan :
- Endpoint yang akan ditest :
1. /login
2. /beli_pulsa
3. /cek_out

- Kebutuhan masing - masing endpoint :
1. Username dan password untuk endpoint/login 
2. Produk, denom dan nomor untuk pengetesan untuk endpoint /beli_pulsa
3. Metode pembayaran yang dipilih untuk endpoint/cek_out

### Menentukan Metode Tets
- Pilih berdasarkan kondisi sistem, apakah belum pernah dites atau sudah.
  * Selalu awali dengan load test untuk tahu kondisi awal sistem.
- Pilih berdasarkan situasi yang akan dihadapi.

### Smoke Testing
Dilakukan untuk verity script yang sudah dibuat, apakah sistem tersebut dapat handle minimal load, tanpa masalah sama sekali. Biasanya hanya 1-2 VUs.

### Load Testing
Load Testing adalah pengujian yang paling sederhana yang paling sederhana yang dilakukan untuk memahami perilaku sistem dalam keadaan beban tertentu.
Hasil darimload test digunakan untuk mengukur kepentingan bisnis saat transaksi yang kritis dengan memonitor dampak terhadap database, application server atau pendukung lainnya.
Sederhananya load testing menentukan kelakuan sistem pada saat kondisi normal dan puncak. Idealnya, kita mengetahui jumlah traffic yang ada di prod sebagai nilai di load test.

### Stress Testing
Metode ini untuk dilakukan untuk mengamati kemampuan dan kestabilan sistem pada saat kondisi eksrem.
Dilakukan bertahap menuju load normal, puncak, dan melebihinya, lalu turun untuk melihat proses recovery.

### Spike Testing
Seperti stress test, namun kenaikan langsung menuju melebihi puncak dilakukan dalam waktu singkat. Jika stress test memberikan waktu untuk scale-out, disini tidak.
Salah satu contoh adalah pada saat flash sale di suatu e-commerce, yang dimana banyaknya kunjungan pengguna yang langsung memuncak saat mengakses halaman flash sale. 

### Soak Testing 
Untuk mengetahui reliabilty ketika dalam tekanan di bawah puncak dalam jangka panjang (>=1 jam). Dapat mengetahui apakah terdapat bug pada race condition, memory leaks, db connection dsb.
