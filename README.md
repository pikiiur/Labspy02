# Pertemuan ke-7

## Tugas Praktikum Modul 2

### Latihan Praktikum Modul 2

Buat program sederhana dengan input tiga buah bilangan, dari ketiga bilangan
tersebut tampilkan bilangan terbesarnya. Gunakan statement if.s

```python
a = int(input("Masukan bilangan ke-1 :"))
b = int(input("Masukan bilangan ke-2 :"))
c = int(input("Masukan bilangan ke-3 :"))

max = a

if b > max:
   max = b

if c > max:
   max = c

print()
print("Nilai terbesar :", max)
``` 