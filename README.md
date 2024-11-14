# Tugas PBO Pertemuan 13
## Membuat Frame Login dengan Persistence

1. Membuat tabel baru pada database UTS PBO dengan nama tabel yaitu pw, yang nantinya akan dibuatkan frame login pada program di Netbeans. Berikut adalah query untuk membuat tabel barunya :

![Screenshot 2024-11-13 123437](https://github.com/user-attachments/assets/3f479ebf-442b-4565-9c3c-6bcdb3b9e062)

2. Selanjutnya, kita isi tabel tersebut untuk percobaan terlebih dahulu seperti dibawah ini.

![Screenshot 2024-11-13 123456](https://github.com/user-attachments/assets/ae151f58-0f6f-4a31-b7c6-732cba99052f)

3. Kemudian, Membuat persistence unit dengan cara, klik kanan package → new → Entity Classes from Database untuk menyambungkan dengan tabel pw.

![Screenshot 2024-11-13 123549](https://github.com/user-attachments/assets/0a191319-1e79-4380-a54c-067634aeb99a)

4. Kemudian memilih koneksi databasenya

![Screenshot 2024-11-13 123605](https://github.com/user-attachments/assets/b27cc26e-9c9a-42fd-9db6-d426a7a9b9fb)

5. Memindahkan ke kanan pada tabel yang dibutuhkan

![Screenshot 2024-11-13 123630](https://github.com/user-attachments/assets/94b9a29c-bb5f-4737-9f74-b28abff2ad64)
![Screenshot 2024-11-13 123647](https://github.com/user-attachments/assets/e766d3ba-8b2a-4a37-9132-74e9dc5e4a77)

6. Kemudian, klik Next

![Screenshot 2024-11-13 123659](https://github.com/user-attachments/assets/5ef4044e-81cf-47a1-b1b5-92c13492319a)

7. Lalu, klik Finish

![Screenshot 2024-11-13 123708](https://github.com/user-attachments/assets/2e7f3527-8f85-4e78-a996-9658aabb7791)

8. Maka, akan muncul tampilan dari project yang sebelumnya telah dibuat dengan penambahan pw.java dengan otomatis.

![Screenshot 2024-11-13 151358](https://github.com/user-attachments/assets/ac0ca344-0ff1-4827-a8d1-595139585d3e)

9. Nah, sekarang kita membuat frame dengan cara klik kanan packages → New → Jframe Form.

![Screenshot 2024-11-13 151709](https://github.com/user-attachments/assets/959f2a2e-49b4-4cea-a85c-7202b11934cb)

10. Berikut adalah desain GUI dari frame login : 

![Screenshot 2024-11-13 151455](https://github.com/user-attachments/assets/3c12e94e-d6b5-426e-a74c-7a6200e0e2a0)

11. Berikut adalah source code dari frame login tersebut :

![Screenshot 2024-11-13 151638](https://github.com/user-attachments/assets/92c78079-c30a-459e-aeba-467d56fd8612)

12. Selanjutnya, membuat frame bagian create an account. Frame ini digunakan ketika seseorang belum mempunyai akun, maka dia harus membuat akun terlebih dahulu agar bisa masuk dalam login.
Berikut adalah desain GUI dalam frame create an account : 

![Screenshot 2024-11-13 152239](https://github.com/user-attachments/assets/9679a1f1-5a56-4bd8-9a6d-b13b46c7c267)

13. Berikut adalah source code dari frame tersebut : 

![Screenshot 2024-11-13 152330](https://github.com/user-attachments/assets/113faddf-3870-4d13-8f36-1ce915f3124e)

14. Lalu, yang terakhir adalah membuat frame Update. Frame ini digunakan ketika seseorang lupa dari password yang sebelumnya telah dia buat, dengan melewati proses username terlebih dahulu, kemudian update password.
Berikut adalah desain GUI dari frame Update tersebut : 

![Screenshot 2024-11-13 152620](https://github.com/user-attachments/assets/2be564ac-cc07-4b76-8ea0-16b2c0bbdd8a)

15. Berikut adalah source code dari frame Update Password :

![Screenshot 2024-11-13 152803](https://github.com/user-attachments/assets/346e35a8-2dbc-42a7-9d18-cc741ba25036)
![Screenshot 2024-11-13 152827](https://github.com/user-attachments/assets/8df3c633-f7a7-4184-9685-5d753da95cf8)

16. Sekarang, kita coba simulasikan dari beberapa frame yang telah dibuat berikut : 
-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
a. Memasukkan username dan password yang sebelumnya telah dibuat di Database di awal tadi.

![Screenshot 2024-11-13 153108](https://github.com/user-attachments/assets/d75354d6-2225-49b2-9190-055303b167a9)

b. Ketika kita lupa password, maka kita masukkan username terlebih dahulu untuk dicari dalam database.

![Screenshot 2024-11-13 153340](https://github.com/user-attachments/assets/8ca06aee-87e6-429f-9c60-8720f476326e)

c. Ketika sudah ketemu maka kita diarahkan untuk memasukkan password baru untuk mengupdate data yang sebelumnya kita lupa, lalu klik Update.

![Screenshot 2024-11-13 153610](https://github.com/user-attachments/assets/fa484d8d-4ff9-4689-80ad-304918bbd722)

d. Sekarang, kita coba masukkan password yang baru saja kita Update tadi dan akhirnya sukses masuk ke dalam frame Mata Kuliah.

![Screenshot 2024-11-13 153731](https://github.com/user-attachments/assets/42dd83e4-8232-45c2-a3b5-854d889b8c59)

e. Lalu, sekarang kita belum punya akun maka kita harus klik “create an account” pada frame login terlebih dahulu agar username dan password bisa masuk dalam database.

![Screenshot 2024-11-13 153931](https://github.com/user-attachments/assets/383bc212-ba12-4083-9424-df6eeca0b84a)

f. Maka, akan muncul pop up seperti dibawah ini : 

![Screenshot 2024-11-13 154115](https://github.com/user-attachments/assets/2c7bde1b-87ca-4c7b-83c6-9c8f0ab62149)

g. Sekarang, kita coba masuk dengan username yang baru saja dibuat tadi.

![Screenshot 2024-11-13 154348](https://github.com/user-attachments/assets/467f9515-4b96-4c5f-97bf-1961a4114417)

h. Nah, akhirnya bisa masuk dalam frame Mata Kuliah untuk melakukan CRUD pada data Mata Kuliah tersebut.

![Screenshot 2024-11-13 154254](https://github.com/user-attachments/assets/73d5cd5c-a16d-4977-9553-35d7062513ce)

## Sekian pemaparan langkah-langkah dalam tugas PBO pertemuan 13 ini, semoga bermanfaat dan selamat mencoba

