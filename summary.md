# 14 Pengenalan RESTful API
# Resume

## API & REST API
- API adalah "Application Programming Interface"
- API memungkinkan komunikasi dan pertukaran data antara 2 atau lebih software/sistem yang terpisah.

## API Workflow
- Client -> Waiter -> Chef 

## REST API 
- REST - "Representational State Transfer"
- HTTP Method
   Resource
   Get
   Put
   Post
   Delete
- Rest API Component
   Method - URL (Base URL + Path)
   Header - Body

## Practice Time 
- Lest Practice using
   Install
   Start tetsing using

## REST API Inputs
- Get
- post
- put
- delete

## Approach of API Testing
- mengerti fungsi dari API
- dapat mengaplikasikan teknik testing
- input parameter untuk API perlu direncanakan dan ditemukan sebelumnya
- jalannya test Case dan bandingkan antara hasil yang diharapkan dengan hasil yang didapat kan. 

## what's API Testing
- API Test sangat berbeda dengan GUI
- Mengirim request dan mendapatkan responsenya
- memverifikasi response yang benar dan error' handling.

## Kind Of API Testing
- Functionality
- load Test
- security

## Difference between API Test & unit test
Unit test
- dilakukan oleh developer
- fungsi terpisah
- developer bisa mengakses source code
- hanya dasar functionality yang di test
- scopenya terbatas
- biasanya dilakukan sebelum build.

## Test Cases for API Testing
- mendapatkan balikan (response) yang sesuai dengan input
- apakah memberikan balikan atau tidak.
- apakah mengganggu fitur yang lain atau tidak
- update struktur data
- memodifikasi data yang ada

## Best Practices of API Testing
- kelompokkan Test Case kedalam beberapa kategori
- beri judul yang sesuai pada setiap test
- harus berhati-hati ketika melakukan Test yang berhubungan dengan menghapus sesuatu
- ketika membuat test Case harus dipikirkan juga segala kombinasi input pada API

## Types of output of an API
- bisa berbentuk apa saja, tapi pada umumnya JSON atau XML
- status balikan (response) apakah passed atau fail
- memanggil fungsi API Lain

## common Types of test in API Testing
- memverifikasi apakah kita mendapatkan respon dari API
- memeverifikasi apakah hasil input/request sudah sesuai atau belum
- memverifikasi apakah data yang kita input / update sudah benar benar berubah atau bertambah
- memverifikasi waktu response yang diberikan

## Types of bugs that API Testing detects
- gagal melakukan error handling pada keadaan tertentu
- kesulitan untuk tersambung dan mendapatkan respon API
- Isu keamanan
- perfomance issues
- error atau worning yang tidak tepat
- struktur dari data respon tidak benar (JSON & XML)

## Advantages of Testing API
- Efisien waktu
- bahasa yang independen
- mengurangi biaya tetsing
- mengurangi resiko

## challenges of API Testing
- kombinasi parameter
- tidak ada GUI
