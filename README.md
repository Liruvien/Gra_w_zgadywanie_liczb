# Gra w zgadywanie liczb

## Opis

Prosta gra konsolowa w zgadywanie liczb, w której komputer losuje liczbę z zakresu 1–100, a użytkownik stara się ją odgadnąć, wprowadzając swoje typy z klawiatury. Gra udziela wskazówek dotyczących wartości podanych przez gracza aż do momentu, gdy poprawna liczba zostanie wprowadzona.

## Zasady gry

1. Komputer losuje liczbę z zakresu 1–100.
2. Użytkownik jest proszony o odgadnięcie liczby z komunikatem: 'Guess the number: ' 
3. Jeśli użytkownik wprowadzi coś, co nie jest liczbą, gra wyświetli komunikat: 'It's not a number', a następnie ponownie poprosi o wprowadzenie liczby.
4. Jeżeli podana liczba jest mniejsza niż wylosowana przez komputer, gra wyświetla komunikat: 'Too small!'
5. Jeżeli podana liczba jest większa niż wylosowana przez komputer, gra wyświetla komunikat: 'Too big!'
6. Jeśli podana liczba jest równa liczbie wylosowanej przez komputer, gra wyświetla komunikat: 'You Win!' i kończy swoje działanie.

## Jak uruchomić grę

1. Upewnij się, że masz zainstalowanego Python 3.
2. Pobierz repozytorium - Gra_w_zgadywanie_liczb
3. W terminalu przejdź do lokalizacji pliku i uruchom grę poleceniem:
python3 app.py
