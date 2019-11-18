# labspy3.3
Latihan1
https://github.com/aditya-sultan/labspy3.3/blob/master/gambar%20tugas.PNG

n=int(input("Masukan Nilai N: "))           ## Memperkenalkan variable n sebagai intger, kemudian menginputkan nilainya

from random import random                   ## Mengimport fungsi random
a=random()                                  ## Memperkenalkan variable a sebagai random

jumlah=n+1                                  ## Jumlah = vaeiable n + 1
start=1                                     ## Dimulai dari angka 1
stop=jumlah                                 ## Berhenti ketika variable jumlah sudah sesuai
step=1                                      ## Step angka 1

for i in range(start,stop,step):             ## Perulangan 1 dengan nilai awal varible start, nilai akhir variable stop dan step variable step
    print("data ke : ",i,"=",(a))           ## Mencetak hasil
print("/nDone")

Dalam Latihan1 ini, apabila kita memasukan angka pada nilai N, maka akan muncul barisan angka sesuai dengan angka yang kita masukan.
seperti misalakan kita masukan angka 19, maka akan muncul sembilan belas baris angka. Lihat:

C:\Users\USER\PycharmProjects\Latihan\venv\Scripts\python.exe C:/Users/USER/PycharmProjects/Latihan/venv/Lib/site-packages/pip-19.0.3-py3.7.egg/pip/Program1.py

Masukan Nilai N: 19
data ke :  1 = 0.5885031262708726
data ke :  2 = 0.5885031262708726
data ke :  3 = 0.5885031262708726
data ke :  4 = 0.5885031262708726
data ke :  5 = 0.5885031262708726
data ke :  6 = 0.5885031262708726
data ke :  7 = 0.5885031262708726
data ke :  8 = 0.5885031262708726
data ke :  9 = 0.5885031262708726
data ke :  10 = 0.5885031262708726
data ke :  11 = 0.5885031262708726
data ke :  12 = 0.5885031262708726
data ke :  13 = 0.5885031262708726
data ke :  14 = 0.5885031262708726
data ke :  15 = 0.5885031262708726
data ke :  16 = 0.5885031262708726
data ke :  17 = 0.5885031262708726
data ke :  18 = 0.5885031262708726
data ke :  19 = 0.5885031262708726
/nDone

Process finished with exit code 0





Latihan2
https://github.com/aditya-sultan/labspy3.3/blob/master/gambar%20tugas%202.PNG

x = int()                                ## Memeperkenalkan variable x sebagai integer, kemudian menginputkan nilainya
y = 0                                    ## Memeperkenalkan variable y dengan nilai 0
while x >= 0:                            ## Looping WHILE apabila nilai x tidak sama dengan 0
   x = int(input("Masukan Bilangan: "))  ## Program yang akan di looping
   if x > y:                             ## If kondisi apabila nilai x lebih beesqr dari nilai y
    y = int (x)                          ## Nilai y sama dengan nilai x
   if x== 0:                             ## If kondisi apabila nilai x sama dengan 0
     break                               ## Fungsi yang menghentikan operasi dibawanya jika suatu kondisi yang ditentukan telah tercapai
print("\nAngka Terbesar adalah ",y)      ## Mencetak bilangan terbesar


Nah pada latihan kedua ini, apabila kita masukan bilangan berapapun dan diakhiri dengan angka 0, maka akan muncul bilangan terbesar seperti:

C:\Users\USER\PycharmProjects\Latihan\venv\Scripts\python.exe C:/Users/USER/PycharmProjects/Latihan/venv/Lib/site-packages/pip-19.0.3-py3.7.egg/pip/Program1.py

Masukan Bilangan: 7
Masukan Bilangan: 9
Masukan Bilangan: 2
Masukan Bilangan: 1
Masukan Bilangan: 8
Masukan Bilangan: 10
Masukan Bilangan: 0

Angka Terbesar adalah  10

Process finished with exit code 0


Program 1
https://github.com/aditya-sultan/labspy3.3/blob/master/gambar%20tugas%203.PNG

kita lanjut di Program 1. seperti yang dilihat dibawah ini


modal = 100000000                                   ## NIlai modal
laba = 0                                            ## NIlai laba 0
untung = 0                                          ## Nilai untung 0
for i in range(1,9,1):                              ## Perulangan i dengan nilai awal 1, nilai akhir 9 dan step 1
    if(i<3):                                        ## Kondisi apabila belum bulan ke-3 laba masih )%
        laba = 0
        untung = untung + laba
    elif(i<5):                                      ## Kondisi apabila belum memasuki bulan ke-5, Mendapat laba sebesar 1%
        laba + modal*1/100
        untung = untung + laba
    elif(i<8):                                      ## Kondisi apabila belum memasuki bulan ke-8, Mendapat laba sebesar %5
        laba = modal*2/100
        untung = untung + laba
    else:                                           ## Pada bulan ke-8 menurun 2%, sehingga laba bulan ke-8 sebesar 3%
        laba = modal*2/100
        untung = untung + laba
        print("Laba Bulan ke-",i," Sebesar", laba)  ## Mencetak laba perbulan
        print("\nTotal Laba adalah: ",untung)       ## Menghitung total laba selama 8 bulan

dalam Program 1 ini kita akan menghitung laba. Mulai dari laba bulan ke-8 sampai total. dan apabibila kita Run maka:

C:\Users\USER\PycharmProjects\Latihan\venv\Scripts\python.exe C:/Users/USER/PycharmProjects/Latihan/venv/Lib/site-packages/pip-19.0.3-py3.7.egg/pip/Program1.py

Laba Bulan ke- 8  Sebesar 2000000.0

Total Laba adalah:  8000000.0

Process finished with exit code 0
