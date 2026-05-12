# Algoritma type penulisan : Deskriptif

## Case: Membuat algoritma menentukan bilangan ganjil atau genap

1. mulai
2. membuat penampung dengan nama Angka
3. menentukan bilangan genap dengan membagi penampung(Angka) modulus 2 kalo habis brarti itu bilangan genap
4. menentukan bilangan ganjil dengan membagi penampung(Angka) modulus 2 kalo sisa brarti itu bilangan ganjil
5. masukan ke penampung hasil
6. selesai

### Flowchart

```mermaid
flowchart TD

mulai@{shape: circle, label: "Start"}
angka@{ shape: lean-r, label: "angka" }
modulus@{ shape: diamond, label: "angka % 2 == 0" }
selesai@{shape: doublecircle, label: "end"}

mulai-->
angka-->
modulus--ganjil-->selesai
modulus--genap-->selesai
```

```pseudo

DECLARE angka: INTEGER

INPUT angka

IF angka % 2 == 0 THEN
    OUTPUT "genap"
ELSE
    OUTPUT "ganjil"
ENDIF

```
