# TIPE-DATA-VARIABLE-DAN-OPERATOR
Nama: MUHAMMAD FATHIR NURCHOLIS

Kelas: TI.24.A4

NIM: 312410287

Matkul: Bahasa Pemrograman

# LATIHAN1
![Screenshot 2024-10-15 143542](https://github.com/user-attachments/assets/618c6e38-97cb-46e1-a4e1-53ac91538752)

```python
#penggunaan end
print('A', end='')
print('B', end='')
print('C', end='')
print()
print('X')
print('Y')
print('z')

#penggunaan separator
w, x, y, z = 10, 15, 20, 25
print(w, x, y, z)
print(w, x, y, z, sep=',')
print(w, x, y, z, sep='')
print(w, x, y, z, sep=':')
print(w, x, y, z, sep='.....')
````

Penggunaan END Penggunaan end digunakan untuk menambahkan karakter yang dicetak di akhir baris. secara default penggunaan end adalah untuk ganti baris.

```python
print('A', end='')
print('B', end='')
print('C', end='')
```
Penggunaan print () digunakan untuk mencetak output, seperti syntax dibawah ini :
```python
print()
```
Syntax dibawah ini digunakan untuk menampilkan output berupa string
```python
print('X')
print('Y')
print('z')
```
Hasil dari source code tersebut seperti gambar dibawah ini :

![Screenshot 2024-10-15 133640](https://github.com/user-attachments/assets/ef44fa5f-a2ef-4dbc-a91d-1ffb53a372d8)

Penggunaan separator
Pendeklarasian beberapa variable beserta nilainya
```python
w,x,y,z=10,15,20,25
```
Menampilkan hasil dari variable tiap-tiap variable
```python
print(w,x,y,z)
```
Menampilkan hasil dari tiap-tiap variable dengan menggunakan pemirsah : (koma)
```python
print(w,x,y,z,sep=",")
```
Menampilkan hasil dari tiap-tiap variable dengan menggunakan pemirsah

```python
print(w,x,y,z,sep="")
```
Menampilkan hasil dari tiap-tiap variable dengan menggunakan pemirsah : (titik dua)
```python
print(w,x,y,z,sep=":")
```
Menampilkan hasil dari tiap-tiap variable dengan menggunakan pemirsah -----
```python
print(w,x,y,z,sep="-----")
```
hasil dari syntax / source code diatas adalah seperti berikut ini :

![Screenshot 2024-10-15 133703](https://github.com/user-attachments/assets/089dc55e-ba8e-4930-b2ee-ee42241bff68)

## LATIHAN 2

![Screenshot 2024-10-15 135657](https://github.com/user-attachments/assets/16cbeee1-5ed0-4192-8417-364c47dec8cc)

```python
a=int(input("masukkan nilai a:"))
b=int(input("masukkan nilai b:"))
print("variable a=",a)
print("variable b=",b)
print("hasil penggabungan {1}&{0}=%d".format(a,b) %(a+b))

#konversi nilai variable
a=int(a)
b=int(b)
print("hasil pejumlahan {1}+{0}=%d".format(a,b) %(a+b))
print("hasil pembagian {1}/{0}=%d".format(a,b) %(a/b))
```
Kita akan coba lagi untuk run file tersebut, maka akan muncul seperti gambar dibawah ini :

![Screenshot 2024-10-15 140328](https://github.com/user-attachments/assets/f33bc0bc-afad-4da8-b7cb-7baa5a9ece4d)

String Format
String formatting atau pemformatan string memungkinan kita menyuntikkan item kedalam string dari pada kita mencoba menggabungkan string menggunakan koma atau string concatenation.
Penggunaan source code yang di berikan oleh dosen seperti berikut :

![Screenshot 2024-10-15 140431](https://github.com/user-attachments/assets/ab9de958-0e2e-4c6b-8854-515217a8fdca)

```python
#string format 1
print(0, 10**0)
print(1, 10**1)
print(2, 10**2)
print(3, 10**3)
print(4, 10**4)
print(5, 10**5)
print(6, 10**5)
print(8, 10**8)
print(9, 10**9)
print(10, 10**10)

#string format 2
print('{0:>3} {1:>16}'.format(0, 10**0))
print('{0:>3} {1:>16}'.format(1, 10**1))
print('{0:>3} {1:>16}'.format(2, 10**2))
print('{0:>3} {1:>16}'.format(3, 10**3))
print('{0:>3} {1:>16}'.format(4, 10**4))
print('{0:>3} {1:>16}'.format(5, 10**5))
print('{0:>3} {1:>16}'.format(6, 10**6))
print('{0:>3} {1:>16}'.format(7, 10**7))
print('{0:>3} {1:>16}'.format(8, 10**8))
print('{0:>3} {1:>16}'.format(9, 10**9))
print('{0:>3} {1:>16}'.format(10, 10**10))
```
String Format 1
Pada syntax / source code strring format satu akan menampilkan output berupa 2 outputan.
Yang pertama (sebelah kiri) akan menampilkan angka urut dari angka 0 hingga 10, sedangkan untuk sebelah kanan akan menampilkan Operasi Aritmatika Pangkat.
Dengan ketentuan sebagai berikut, Operasi pangkat dengan angka kiri sebagai pokok (Rumus : ** [bintang dua] )
Hasil dari syntax tersebut adalah 10 pangkat 0, hingga 10 pangkat 10, dengan output sebagai berikut :

![Screenshot 2024-10-15 140328 (1)](https://github.com/user-attachments/assets/b415ca9d-00e1-42c0-a846-74bd2f0e45d0)


2 * String Format 2*
Pada syntax atau source code string format dua akan menampilkan output berupa 2 output'an juga (seperti String Format 1, yaitu kanan dan kiri )
Dengan ketentuan sebagai berikut :

secara Default, .format() menggunakan rata kiri, angka ke kanan. kita dapat menggunakan opsi opsional <,^, atau > untuk mengatur perataan kiri, tengah, atau kanan. Contoh lain dalam penggunaan .format() sebagai berikut :

![Screenshot 2024-10-15 141036](https://github.com/user-attachments/assets/5399a82d-2ead-4f0a-8e17-1d88e84c0029)

Untuk hasil dari String Format 2 adalah :

## Tugas Latihan
![Screenshot 2024-10-15 141347](https://github.com/user-attachments/assets/d63bee4a-8df3-45c2-8b6e-2b89604a9c90)

# Flowchart Bilangan terbesar dari 3 buah bilangan
![Screenshot 2024-10-15 142113](https://github.com/user-attachments/assets/9ea65194-c8e2-429c-9467-239bd76cedad)

# Program bilangan terbesar dari 3 buah yg di inputkan
![Gambar WhatsApp 2024-10-17 pukul 00 34 59_95aec777](https://github.com/user-attachments/assets/1fe259a9-f0db-4bf9-9a9f-55381f773917)

Hasil output

![Screenshot 2024-10-17 222816](https://github.com/user-attachments/assets/bfcdd8e1-a718-4741-8388-0c0f6f9e56a4)

# Flowchart Bilangan terbesar dari N bilangan
![Gambar WhatsApp 2024-10-17 pukul 12 53 34_cd402e92](https://github.com/user-attachments/assets/bd6df8ad-0733-4d22-a152-4d345b0f494f)

# Program bilangan terbesar N 
![Screenshot 2024-10-17 223514](https://github.com/user-attachments/assets/124c1aeb-8836-44ed-80f8-d882efe94902)

Hasil output
![Screenshot 2024-10-17 223553](https://github.com/user-attachments/assets/d681e4c7-0cc9-488d-b38c-c9bed67ca054)
