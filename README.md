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

## Flow chart:

```mermaid
graph TD
A[Start]-->B(inisiasi bil1-integer bil2-integer bil3-integer)
B-->C(baca bil1)
C-->D(baca bil2)
D-->E(baca bil3)
E-->F(jika bil1>bil2 & bil1>bil3)
F-->|ya|G[cetak terbear bil pertama]
F-->|tidak|H[jika bil2>bil3 & bil2>bil1]
H-->|ya|I[cetak terbesar bil kedua]
H-->|tidak|J[cetak terbesar bil ketiga]
I-->K
J-->K
G-->K(selesei)
```
## Program
![github](https://github.com/dicgar95/labpy1/blob/master/program.png)

### Hasil program
![github](https://github.com/dicgar95/labpy1/blob/master/hasil.png)
