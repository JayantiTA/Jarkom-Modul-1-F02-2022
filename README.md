# Jarkom Modul 1 F02 2022

### Anggota:

1. [Andymas Narendra Bagaskara](https://gitlab.com/zaibir123) (05111940000192)
2. [Jayanti Totti Andhina](https://gitlab.com/JayantiTA) (5025201037)
3. [Gaudhiwaa Hendrasto](https://gitlab.com/gaudhiwaa) (5025201066)

### 1. Sebutkan web server yang digunakan pada "monta.if.its.ac.id"!

Masukkan display filter `tcp contains "monta.if.its.ac.id"`

![image](images/nomor_1_1.jpg)

Kemudian klik kanan pada paket HTTP, pilih follow -> HTTP stream. Sehingga didapatkan jenis web server yang digunakan, yaitu **nginx/1.10.3**.

![image](images/nomor_1_2.jpg)

### 2. Ishaq sedang bingung mencari topik ta untuk semester ini , lalu ia datang ke website monta dan menemukan detail topik pada website “monta.if.its.ac.id” , judul TA apa yang dibuka oleh ishaq?

Langkah yang sama dengan nomor 1, kemudian ditemukan link Tugas Akhir yang sedang dibuka.

![image](images/nomor_2_1.jpg)

Dan ketika dibuka link tersebut, maka akan didapatkan judul Tugas Akhir: **Perancangan Sistem Pengendali Panas Otomatis pada Mesin Sangrai Kopi dengan Logika Fuzzy**.

![images](images/nomor_2_2.jpg)

### 3. Filter sehingga wireshark hanya menampilkan paket yang menuju port 80!

Masukkan display filter `tcp.dstport == 80 || udp.dstport == 80`, kemudian didapatkan semua paket yang menuju port 80.

![images](images/nomor_3.jpg)

### 4. Filter sehingga wireshark hanya mengambil paket yang berasal dari port 21!

Masukkan display filter `tcp.srcport == 21 || udp.srcport == 21`, kemudian didapatkan semua paket yang berasal dari port 21.

![images](images/nomor_4.jpg)