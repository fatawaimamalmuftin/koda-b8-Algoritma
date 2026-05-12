# ALGORITMA

## DESKRIPTIF case: mengecek kata palidrome

1. start
2. buat penampung (Kata)
3. eja kata tiap huruf dari akhir ke awal masukan di penampung (s)
4. kalo s sama dengan kata brarti palidrome
5. kalo tidak sama brati tidak palingdrome
6. end

## Flowchart case: mengecek kata palindrome

```mermaid
flowchart TD

mulai@{ shape: circle, label: "Start"}
huruf@{ shape: lean-r, label: "kata"}
huruf2@{ shape: lean-r, label: "{kata}"}
i@{ shape: diamond, label: "s == kata"}
s@{ shape: lean-r, label: "'Palingdrome'"}
s2@{ shape: lean-r, label: "'Bukan Palingdrome'"}
selesai@{ shape: doublecircle, label: "End"}

mulai-->huruf-->i
i--loop-->huruf2-->
i--false-->s2-->selesai
i--true-->s-->selesai
```

## PSeudo-Code case: mengecek kata palindrome

```memaid
pseudo

DECLARE kata : STRING
DECLARE s : INTEGER

INPUT kata

FOR s <- 10 TO 1
    kata <- s
NEXT s
IF s == kata THEN
    OUTPUT "Palindrome"
ELSE
    OUTPUT "Bukan Palindrome"
ENDIF

```
