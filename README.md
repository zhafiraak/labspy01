# labspy01

### Latihan1
#### Program dan Output
- Program sederhana dengan input 2 buah bilangan serta menentukan bilangan terbesar dari kedua bilangan
![Gambar1](screenshots/ss1.jpg)
![Gambar2](screenshots/ss2.jpg)

```bash
print("Program mencari bilangan terbesar") 

a = int(input("Masukan nilai a: "))
b = int(input("Masukan nilai b: "))

if a > b:
    print ("A yang terbesar")
elif b > a:
    print ("B yang terbesar")
```

### Latihan2
#### Program dan Output
- Program mengurutkan data berdasarkan input jumlah data, serta menentukan urutan dari data terkecil

![Gambar3](screenshots/ss3.jpg)
![Gambar4](screenshots/ss4.jpg)

```bash
print('Program mengurutkan data')

pertama = int(input("Bilangan pertama: "))
kedua = int(input("Bilangan kedua: "))
ketiga = int(input("Bilangan ketiga: "))

print(f'urutan: {pertama}, {kedua}, {ketiga}')
```


### Latihan3
#### Program dan Output

- Program perulangan bertingkat

![Gambar5](screenshots/ss5.jpg)
![Gambar6](screenshots/ss6.jpg)

```bash
#Program Perulangan

for i in range(0, 10):
  for j in range(10):
    print('%3d'%(i+j), end = ' ')
  print(' ')
```

### Latihan4
#### Program dan Output
- Tampilkan bilangan acak N yang lebih kecil dari 0.5
- Nilai N diisi pada saat runtime


![Gambar7](screenshots/ss7.jpg)
![Gambar8](screenshots/ss8.jpg)
```bash
from random import random
n = int(input("Masukan Nilai N: "))
for i in range(n):
    while 1:
        n = random()
        if n < 0.5:
            break
    print(n)
```

## Terima kasih
