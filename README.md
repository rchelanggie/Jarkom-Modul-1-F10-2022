# Laporan Resmi Modul 1 F10 2022

Kelompok F10 <br/>
Luthfiyyah hanifah A	  5025201090 <br/>
Rachel Anggieuli AP	  5025201263 <br/>
Cholid Junoto	        5025201038 <br/>

### Soal 1
#### Sebutkan web server yang digunakan pada "monta.if.its.ac.id"!
Filter

    'http.request and http.host eq "monta.if.its.ac.id"'
![](images/1.png)

##### Server : ngix/1.10.3
![](images/1_2.png)

### Soal 2
#### Ishaq sedang bingung mencari topik ta untuk semester ini , lalu ia datang ke website monta dan menemukan detail topik pada website “monta.if.its.ac.id” , judul TA apa yang dibuka oleh ishaq ?
Filter

    http
![](images/2.png)

###### Eksport http object dan pilih http
![](images/2_2.png)
###### Save ke dalam komputer kita
![](images/2_3.png)
######  Kasih nama dengan type html
![](images/2_4.png)
###### Lalu kita buka di browser kita akan muncul di browser kita
![](images/2_5.png)

Didapatkan judul TA Ishaq adalah Evaluasi untuk kerja User Space Filesystem (FUSE)

### Soal 3
#### Filter sehingga wireshark hanya menampilkan paket yang menuju port 80!
Filter

    tcp.dstport == 80
![](images/3.png)

### Soal 4
#### Filter sehingga wireshark hanya mengambil paket yang berasal dari port 21!
Filter 

    tcp.srcport == 21
![](images/4.png)
