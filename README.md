# Dokumentasi Project (cara install/cara setup/endpoin/screenshot)

UAS Manajemen Basis Data C

Anggota kelompok 8 :
1. Indah Sri Lestari (1207050048)
2. M. Afian Anwar (1207050065)
3. M. Alwy Sholehudin (1207050066)


Penjelasan aplikasi :

Membuat aplikasi Android untuk melakukan CRUD  pada tabel students di SQLite dimana terdapat 3 field
yaitu id, nim, dan nama.

cara setup :
1. Membuat project baru  bernama MyStudents dengan tipe Empty Activity
2. Membuat package baru dengan nama model, kemudian membuat class di Java dengan nama Students.java
3. Pada class Student perlu implement  ke Serializable agar saat update data, object  student dapat dikirim memlalui intent ke activity UpdateActivity
4. Membuat package baru dengan nama db dan buat class baru dengan nama DbHelper.java
5. class DbHelper.java merupakan class untuk pengolahan database DDL (Data Definition Language). Proses DDL terdapat pada methode onCreate dan onUpgrade.
![image](https://user-images.githubusercontent.com/96606602/208974939-c056d852-366c-4e51-9907-5f0054149164.png)
6. Insert data ke database (INSERT)
![image](https://user-images.githubusercontent.com/96606602/208974989-098c396f-aa60-45af-a8a5-1f8ef6a4dd29.png)
pada insert data, dilakukan validasi notNull terlebih dahulu untuk EditText nim dan nama. Jika validasi terpenuhi maka proses
insert akan dilakukan dengan menggunakan object dari class DbHelper pada method addUserDetail()
7. Menampilkan data (GET)
![image](https://user-images.githubusercontent.com/96606602/208975064-08b13b05-ade1-40ea-bd9b-835c5eb00b3e.png)
8. delete data (DELETE)
![image](https://user-images.githubusercontent.com/96606602/208975188-f93f1bb7-5654-4da9-9c57-8211ffc1330d.png)
9. update data (UPDATE)
![image](https://user-images.githubusercontent.com/96606602/208975259-d15db5dc-a0cb-4848-a2f8-c115ce0ed271.png)
10. Tampilan aplikasi
![image](https://user-images.githubusercontent.com/96606602/208975572-5b1e98b5-371c-4bdc-9247-190333c20630.png)



