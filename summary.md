# 12 Iterable Data Structure
# Resume

- Iterable
  Iterable diperkenalkan untuk dapat digunakan pada loop foreach. Kelas yang mengimplementasikan antarmuka Iterable dapat diulangi.
  
- Iterator
  Iterator adalah Kelas yang mengelola iterasi di atas iterable. Iya mempertahankan A keadaan di mana kita berada dalam iterasi saat ini, dan tahu apa elemen berikutnya dan bagaimana mendapatkannya.
  
- Collections
Setiap kelompok objek individu yang direpresentasikan sebagai satu unit dikenal sebagai Koleksi objek. 

- List 
  1. Antarmuka daftar menyediakan cara untuk menyimpan koleksi yang dipesan.
  2. Ini adalah antarmuka anak dari koleksi.
  3. Ini adalah kumpulan objek yang dipesan di mana nilai duplikat dapat disimpan.
  4. Karena daftar mempertahankan urutan penyisipan, ini memungkinkan akses posisional dan penyisipan elemen.

- AbstractCollection
  Itu digunakan untuk mengimplementasikan koleksi yang tidak dapat dimodifikasi, di mana seseorang hanya perlu memperluas kelas abstraksi ini dan hanya mengimplementasikan iterator dan metode ukuran.

- AbstractList
  Kelas ini menyediakan implementasi kerangka antarmuka daftar untuk meminimalkan upaya yang diperlukan untuk mengimplementasikan antarmuka ini yang didukung oleh penyimpanan data akses acak (seperti array). Untuk Data akses sekuensial (seperti daftar tertaut), daftar sekuensial abstrak), daftar sekuensial astract harus digunakan dalam preferensi untuk kelas ini.

- ArrayList
 Ini memberi kita array dinamis di java. Meskipun, mungkin lebih lambat dari array standar tetapi dapat membantu dalam program di mana hilangnya manipulasi dalam array diperlukan. 

- AbstractSequantialList
   Ini digunakan untuk mengimplementasikan daftar yang tidak dapat dimodifikasi, di mana seseorang hanya perlu memperluas kelas daftar abstrak ini dan hanya mengimplementasikan metode get () dan ukuran ().   

- LinkedList
 1. Daftar tertaut terdiri dari node di mana setiap node berisi data dan referensi ke node berikutnya dalam daftar.
 2. Tidak seperti array, data tidak disimpan dalam satu tempat yang berdekatan.
 3. Sebaliknya, ini terdiri dari beberapa blok memori di alamat yang berbeda.

- Stack
1. Kelas tumpukan mewakili tumpukan objek terakhir - masuk - pertama - keluar (Lifo).
2. Ini memperluas vektor kelas dengan lima operasi yang memungkinkan vektor diperlakukan sebagai tumpukan. 

- Hash Set
1. Hashset menyimpan elemen dengan menggunakan mekanisme yang disebut hashing
2. Hashset hanya berisi elemen unik.

- EnumSet
1. Itu hanya dapat berisi nilai enum dan semua nilai harus dimiliki oleh enum yang sama.
2. Itu tidak memungkinkan untuk menambahkan nilai nol, melemparkan pengecualian pointer nol dalam upaya untuk melakukannya.


- SortedSet
Satu set lebih lanjut memberikan pemesanan total pada elemen-elemennya.  
Unsur-unsur diurutkan baik dengan menggunakan pengurutan alami atau dengan menggunakan pembanding Semua elemen yang dimasukkan ke dalam set yang diurutkan harus mengimplementasikan antarmuka yang sebanding.

- Queue
1. Que dapat didefinisikan sebagai daftar terurut yang memungkinkan operasi penyisipan dilakukan di satu ujung yang disebut BELAKANG dan operasi hapus dilakukan di ujung lainnya.


- Deque 
Deque adalah Koleksi linier yang mendukung penyisipan dan penghapusan elemen dari kedua ujungnya. Nama deque adalah singkatan dari double-ended queue.
