# Tugas Akhir Praktikum Pemos Kelompok 21
Tugas akhir ini dibuat untuk memenuhi syarat Tugas Akhir Praktikum Pemodelan Oseanografi Tahun 2022. Harapannya, repositori ini dapat memberikan manfaat untuk semua orang.
Dalam repositori ini terdapat landasan teori pada setiap persamaan yang digunakan, metode atau langkah-langkah pemodelan adveksi-difusi dan hidrodinamika dan penjelasan mengenai pemanfaatakn persamaan adveksi-difusi serta hidrodinamika dalam bidang Oseanografi. 

# Nama Kelompok
1. Ismi 'Alimatunnisa 26050120120034 Oseanografi A
2. Gigih Merin Pratiwi 26050120130065 Oseanografi A
3. Fipi Suyanti 26050120140121 Oseanografi B
4. Danindra Ravideevan Pradipta 26050120140157 Oseanografi B
5. Annisa Wizqi Abdul Wakhid
6. Asifa' Ainur Rokhimah 26050120130070 Oseanografi A
7. Nurul Annisa 26050120140078 Oseanografi B

# 1. Landasan Teori
**Difusi-Adveksi**

-DIFUSI-
Persamaan difusi merupakan representasi perpindahan suatu zat dalam pelarut dari bagian konsentrasi tinggi ke konsentrasi rendah tanpa dipengaruhi oleh kecepatan gerak fluida media.  

-ADVEKSI-
Persamaan adveksi merupakan persamaan gelombang linier orde satu dan termasuk dalam persamaan differensial hiperbolik yang menggambarkan mekanisme transportasi suatu zat cair dengan arah tertentu. 


**Hidrodinamika**

Hidrodinamika terdiri dari 2 suku kata. 
Hidro berarti "air" dan Dinamika yang berarti "benda bergerak/tenaga yang menggerakkan".
Hidrodinamika dapat didefinisikan sebagai salah satu cabang ilmu pengetahuan yang mempelajari gerak liquid atau gerak fluida cair khususnya gerak air.

-Model Hidrodinamika-
1. Model yang dibangun dari adanya proses-proses yang mempengaruhi pergerakan massa air
2. Hukum Konservasi massa/kontinuitas dan hukum momentum
3. Mensimulasikan elevasi muka air laut dan arus yang dipengaruhi oleh beberapa parameter

-Persamaan-

Persamaan dasarnya ada 2 yaitu momentum dan kontinuitas.

Momentum ![image](https://user-images.githubusercontent.com/105961293/169863703-342881ad-3abd-46ac-b324-37177da4dec2.png)

Kontinuitas ![image](https://user-images.githubusercontent.com/105961293/169863772-e096e76a-1859-4e7f-a20a-08a0b9821dc3.png)

Dimana dibantu dengan persamaan pembangun

![image](https://user-images.githubusercontent.com/105961293/169864444-a72d892e-1201-46e6-9d3d-883dc7ed3159.png) & ![image](https://user-images.githubusercontent.com/105961293/169864497-8bf89895-1de6-47f1-baf9-e48e43b81212.png)


# 2. Metode 


**Modul 2**
Adveksi-Difusi 2D

1. Buka laman jupyter notebook, kemudian pilih new pyhton 3 untuk membuat script
![image](https://user-images.githubusercontent.com/105660616/169575203-41673726-0802-48cd-9562-83cce2747e62.png)
2. Setelah itu lakukan *import library python matploblib, **numpy, dan **sys*
![image](https://user-images.githubusercontent.com/105741300/169255244-e1b50ab2-a52c-4322-adc2-274199f832f8.png)
3. Langkah selanjutnya masukan parameter persebaran polutan yang akan digunakan
![image](https://user-images.githubusercontent.com/105741300/169245860-8eb49961-1fac-436a-ad41-66c719b79c5b.png)
4. Kemudian dibuat script perhitungan untuk mengetahui persebaran polutan
![image](https://user-images.githubusercontent.com/105741300/169246416-32b33897-5f23-4d2d-aab0-a8839ec3b67e.png)
5. Setelah itu membuat script untuk pembuatan _grid_ dari persebaran polutan
![image](https://user-images.githubusercontent.com/105741300/169247085-4979a547-7888-408f-8e68-e516ba98ca78.png)
6. Selanjutnya melakukan iterasi sampai semua syarat batas terpenuhi
![image](https://user-images.githubusercontent.com/105741300/169248728-7d6f022d-eda6-43a5-9ad1-4bd6acef288d.png)
7. Langkah berikutnya membuat script untuk output gambar penyebaran polutan 
![image](https://user-images.githubusercontent.com/105741300/169250267-e66e1089-cf64-47c8-9a0f-e1eceac3c16f.png)
8. Langkah terakhir klik _running script_ yang terdapat pada menu
![image](https://user-images.githubusercontent.com/105741300/169250673-f9439955-97ad-45bf-bed9-78e5f07a7892.png)


**Modul 3**
HIDRODINAMIKA 1 DIMENSI
1. Pembuatan script dan pemodelan dapat dilakukan menggunakan aplikasi _Visual Studio Code_ atau _Jupyter Notebook_ (dibuka melalui _Anaconda Prompt (miniconda 3)_).
2. Setelah itu lakukan *import library python matploblib, **numpy as np*
3. Parameter-parameter analisis disesuaikan dengan ketentuan penugasan.
4. Script ditulis. Script modul 3 Hidrodinamika 1 Dimensi dapat dituliskan sebagai berikut:
5. Import dan parameter-parameter serta persamaan-persamaan diinput.

![image](https://user-images.githubusercontent.com/92222622/169678228-23cb4aee-5d13-429b-8100-06f95954d045.png)

6. Diskretisasi persamaan dengan metode FTCS dan CTCS.

![image](https://user-images.githubusercontent.com/92222622/169678251-3d6cae8d-0ba8-488f-adf9-f9d24b3b74f3.png)

7. Script untuk menghasilkan grafik diketik.

![image](https://user-images.githubusercontent.com/92222622/169678261-e88baf82-7338-41d2-84af-7162820c5872.png)

8. Ikon "Run" diklik dan akan menghasilkan output gambar.

![image](https://user-images.githubusercontent.com/105741300/169250673-f9439955-97ad-45bf-bed9-78e5f07a7892.png)
![WhatsApp Image 2022-05-22 at 23 25 24](https://user-images.githubusercontent.com/106017099/169705614-3aab6684-5654-438f-a8a8-6e6520e9fc82.jpeg)


9. Lalu akan didapat hasil pemodelan berupa empat buah grafik yang menunjukan hubungan perubahan elevasi muka air laut dan perubahan kecepatan arus. 


**Modul 4**
HIDRODINAMIKA 2 DIMENSI
1.	Membuka Anaconda prompt (Miniconda 3)
2.	Meng-install mandatory library seperti Matplotlib dan Siphon
3.	Membuka jupyter notebook di website browser
4.	Membuat script coding dengan stasiun ID sesuai dengan ketentuan pada spreadsheet
     
![1](https://user-images.githubusercontent.com/92528305/169967207-b62e6731-7e65-40fa-91ca-dd852c776a4d.jpeg)

![2](https://user-images.githubusercontent.com/92528305/169967557-1f45f8b8-5e97-4640-8f71-e504084f36d6.jpeg)
     
5.	Meng-klik ikon run

![5 1](https://user-images.githubusercontent.com/92528305/169970941-b783dc39-0240-4299-a3f2-011ceaf26269.jpeg)

7.	Membuka website NDBC-NOAA dengan link https://www.ndbc.noaa.gov/obs.shtml
8.	Mencari lokasi stasiunnya sesuai ketentuan stasiun ID di kolom pencarian
9.	Mengidentifikasi dan menganalisis lokasi buoy yang digunakan dan satisun pengamantan yang didapatkan 


# 3. Hasil Pemodelan
**Modul 2** 
Hasil yang didapat dari modul 2 Adveksi-Difusi 2D yakni timestamp persebaran polutan dari t=0 hingga ke jangka waktu yang ditentukan pada tetha atau arah tertentu. Berikut adalah contoh hasil modul 2 dari beberapa timestamp pada tetha=43.
**Running Timestamp 1 dari 208**
![1](https://user-images.githubusercontent.com/92222622/170141214-7b68e682-b8ca-454f-b4b1-d35640c64319.jpg)

**Running Timestamp 104 dari 208**
![104](https://user-images.githubusercontent.com/92222622/170141508-18aac2b2-f689-465d-92f8-8230f8ed09ee.jpg)

**Running Timestamp 208 dari 208**
![208](https://user-images.githubusercontent.com/92222622/170141553-f150d3b9-d1af-4299-95ed-fcf0906f8562.jpg)

Jika timestamp yang diinginkan adalah 208, maka akan ada 208 hasil script, oleh karena itu kami hanya mencantumkan 3 contoh *running script* modul 2.

**Modul 3**
Praktikum pemodelan oseanografi modul 3 kali ini menghasilkan beberapa grafik yang mana salah satunya adalah grafik perubahan kecepatan arus dalam grid tertentu di sepanjang waktu. Menurut Triatmodjo (1999), berdasarkan kedalaman relatif, yaitu perbandingan kedalaman air dan panjang gelombang.
# 
**Grafik 1**

![image](https://user-images.githubusercontent.com/92222622/169678484-2fa0fd7a-4a0e-49f7-81b6-35cc98315f17.png)

**Grafik 2**

![image](https://user-images.githubusercontent.com/92222622/169678512-462cc805-8c1b-4795-b6b5-ca16d1e012a4.png)

**Grafik 3**

![image](https://user-images.githubusercontent.com/92222622/169678533-9366f10e-f741-409a-a668-a20a0d4dffd4.png)

**Grafik 4**

![image](https://user-images.githubusercontent.com/92222622/169678549-fe19ab00-1ccc-4f1e-95f4-647119a0a477.png)


**Modul 4**
Praktikum pemodelan oseanografi modul 4 kali ini menghasilkan beberapa grafik berupa data gelombang, gambar bouy pada statiun 46002, dan combined plot of Wind Speed, Gust, and Air Pressure.
#
**Grafik 1**

![4](https://user-images.githubusercontent.com/92528305/169968603-b346b135-36c1-48a7-b5c1-f9dc4b9acfd4.jpeg)

**Gambar 1**

![5](https://user-images.githubusercontent.com/92528305/169968655-b6aa61a5-76ff-4aea-b39e-1fbf18d39c64.jpg)

**Grafik 2**

![6](https://user-images.githubusercontent.com/92528305/169968782-54886a39-f8f1-46d1-bc73-e3856ef4c76e.png)


# 4. Pemanfaatan Persamaan Adveksi-Difusi dan Hidrodinamika di Bidang Oseanografi

Berbagai fenomena hidro-oseanografi dapat disimulasikan dengan model matematis dengan memperhatikan kondisi parameternya, seperti angin, arus laut, gelombang dan lain-lain. Fenomena aliran san transpor merupakan gejala yang penting untuk dikaji karena mempunyai pengaruh terhadap beberapa studi rekayasa. 
Fenomena-fenomena tersebut teradi dalam berbagai macam situasi fisik, seperti transfer panas, proses pemisahan zat kimia, aliran fluida dalam media berpori, penyebaran kontaminan dalam cairan dan transpor partikel kecil berupa polutan, garam, sedimen di perairan dangkal.
Persamaan Adveksi-Difusi dan Hidrodinamika digunakan dalam berbagai bidang, utamanya adalah dalam bidang Oseanografi. Persamaan yang akan digunakan terlebih dahulu dilakukan diskritisasi. 

Manfaat dari persamaan adveksi-difusi adalah:
1. Pemodelan persebaran polutan di laut
2. Pemodelan _oil spill_ atau tumpahan minyak di laut
3. Pemodelan persebaran bahan kimia pada luasan dan kedalaman tertentu
4. Pemodelan persebaran material sedimen dalam perairan

Manfaat dari persamaan hidrodinamika adalah:
1. Pemodelan gelombang yang ditimbulkan oleh angin laut
2. Pemodelan dinamika pantai
