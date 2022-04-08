# 17 Behavior Driven Development (BDD)
## Summary

# BDD 
BDD tidak hanya membantu Anda mengembangkan perangkat lunak dengan benar, tetapi juga memastikan Anda mengembangkan perangkat lunak yang benar.

## BDD Format
- user story
- As a (x) i want (y) so that (z)
- scenario 
- given, when, then

## Gherkin BDD Language
- Meta : Fitur pencarian untuk pengguna 
Fitur ini sangat penting karena akan memungkinkan pengguna untuk menyaring produk.
- Narrative : sebagai pengguna
Saya ingin mencari tanpa kesalahan ejaan, untuk nama produk yang ada dalam inventaris. Jadi semua produk dengan nama smilar harus ditampilkan.
- Scenario :  Search laptop
Pengguna yang diberikan ada di halaman utama www.myshopingsite.com
Saat pengguna mencari laptop. Kemudian halaman pencarian harus diperbarui dengan daftar laptop. 

## cucumber
### BDD with cucumber
- write story
- map stetps to Java
- configure stories
- run stories
- view reports
