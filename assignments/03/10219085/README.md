# assignment 03
Terdapat kode Python berikut ini yang akan digunakan.
```python
import html
char1 = html.unescape('&#x25FB;')
char2 = html.unescape('&#x25FC;')

NIM = '10298345'
for x in NIM:
  n = int(x, 10)
  s = ''
  for i in range(n):
    s += char
  print(n, ':', s, sep='')
```

## question 1
Ganti nilai variabel NIM dengan data Anda, jalankan kode yang diberikan, dan tampilkan hasilnya.

### anwser 1
Hasil kode di atas adalah
```
Traceback (most recent call last):
  File "HelloWorld.py", line 10, in <module>
    s += char
NameError: name 'char' is not defined
```

Tested at OneCompiler [3xr4deg23](https://onecompiler.com/python/3xr4deg23)

## question 2
Ganti nilai variabel NIM dengan data Anda, modifikasi kode yang diberikan di atas dengan `s += char1`, jalankan dan tampilkan hasilnya.

### anwser 2
Hasil modifikasi kode di atas adalah
```
Output:

1:◻
0:
2:◻◻
1:◻
9:◻◻◻◻◻◻◻◻◻
0:
8:◻◻◻◻◻◻◻◻
5:◻◻◻◻◻
```

Tested at OneCompiler [3xqx2v39n](https://onecompiler.com/python/3xqx2v39n)

## question 3
Ganti nilai variabel NIM dengan data Anda, modifikasi kode yang diberikan di atas dengan `s += char2`, jalankan dan tampilkan hasilnya.

### anwser 3
Hasil modifikasi kode di atas adalah
```
Output:

1:◼
0:
2:◼◼
1:◼
9:◼◼◼◼◼◼◼◼◼
0:
8:◼◼◼◼◼◼◼◼
5:◼◼◼◼◼
```

Tested at OneCompiler [3xqx32ehk](https://onecompiler.com/python/3xqx32ehk)

## question 4
Jelaskan dengan singkat hal yang dihasillkan oleh kode yang diberikan.

### answer 4
Kode di atas berfungsi untuk
+ html digunakan untuk mengelola suatu data
+ unescape digunakan pada string yang disandikan
+ Kode setelah penggunaan unescape adalah unicode character. Pada char1 yang terbentuk adalah kotak persegi putih dengan jumlah yang sesuai dengan angka pada NIM, sementara itu pada char2 yang muncul berwarna hitam
