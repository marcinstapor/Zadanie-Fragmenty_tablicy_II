# Fragmenty tablicy (II)
Dana jest tablica n liczb całkowitych. Napisz program, który wyświetli sumy jej fragmentów.
## Wejście
W pierwszym wierszu wejścia liczba całkowita n - ilość elementów tablicy (1 ≤ n ≤ 50).
W drugim wierszu wejścia n liczb całkowitych: t0, t1, ..., ti, ..., tn-1 (-10000 ≤ ti ≤ 10000).
W trzecim wierszu wejścia liczba całkowita z - ilość zapytań (1 ≤ z ≤ 20).
W kolejnych z wierszach liczby całkowite a i b - granice fragmentu do zsumowania (0 ≤ a ≤ b ≤ n-1).
Uwaga: w zadaniu przyjęto, że elementy tablicy numerujemy od zera.
## Wyjście
Odpowiedzi na kolejne zapytania. Każda odpowiedź osobnym wierszu zawierająca sumę fragmentu tablicy: ta+ ...+ tb.
## Przykład
### Wejście:
```
10
11 221 331 44 55 66 77 88 99 199
2
0 1
7 9
```
### Wyjście:
```
232
386
```
