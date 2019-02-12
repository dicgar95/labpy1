# Menentukan bilangan terbesar dari 3 bilangan
## Algoritma
1.  Mulai
2.  Inisiasi bil1,bil2,bil3 sebagai integer.
3.  Baca bil1.
4.  Baca bil2.
5.  Baca bil3.
6.  Jika bil1 > bil2 dan bil1 > bil3 maka kerjakan langkah 8, selain itu
7.  Jika bil2 > bil1 dan bil2 > bil3 maka kerjakan langkah 9, selain itu kerjakan langkah 10.
8.  Cetak “Bilangan Terbesar Bilangan Pertama”.
9.  Cetak “Bilangan Terbesar Bilangan Kedua”.
10.  Cetak “Bilangan Terbesar Bilangan Ketiga”.
11.  Selesai
## Program
![github](https://github.com/dicgar95/labpy1/blob/master/program.png)

### Hasil program
![github](https://github.com/dicgar95/labpy1/blob/master/hasil.png)

## Flow chart:

```mermaid
graph TD;
Start-->inisiasi bil1-integer bil2-integer bil3-integer;
inisiasi bil1-integer bil2-integer bil3-integer --> baca bil1;
baca bil1-->baca bil2;
baca bil2-->baca bil3;
baca bil3-->jika bil1>bil2 & bil1>bil3;
jika bil1>bil2 & bil1>bil3 -->|ya|cetak terbear bil pertama;
jika bil1>bil2 & bil1>bil3-->|tidak| jika bil2>bil3 & bil2>bil1;
jika bil2>bil3 & bil2>bil1-->|ya| cetak terbesar bil kedua;
jika bil2>bil3 & bil2>bil1-->|tidak|cetak terbesar bil ketiga;
cetak terbesar bil kedua-->selesei;
cetak terbesar bil ketiga-->selesei;
cetak terbear bil pertama-->selesei;
