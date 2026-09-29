# Omoda 9: prąd kontra benzyna

Kalkulator kosztu przejazdu i ładowania Omody 9 Super Hybrid (PHEV). Liczy osobno benzynę z baku i prąd z gniazdka, a potem podaje sumę, koszt na 100 km i porównanie z jazdą tylko na benzynie albo tylko na prądzie.

## Co zawiera

- zdjęcie auta z oznaczonymi podzespołami i wartościami dla wpisanego przejazdu
- poradnik, jak czytać komputer pokładowy (średnia z ostatnich 50 km, doliczanie prądu do litrów)
- przykład krok po kroku z edytowalnymi danymi
- kalkulator przejazdu z dwoma wariantami odczytu ekranu
- kalkulator ładowania (czas, koszt, zasięg)
- realne wartości z testów i tabela źródeł
- podpowiedzi przy każdym pojęciu

## Jak używać

Otwórz `index.html` w przeglądarce albo wejdź na stronę projektu na GitHub Pages. Strona działa bez instalacji i bez serwera. Potrzebny jest tylko internet do pobrania czcionek.

## Wzór

```
koszt = litry benzyny × cena Pb95 + kWh z gniazdka × cena prądu
kWh z baterii  = (% na starcie − % na końcu) / 100 × pojemność użyteczna
kWh z gniazdka = kWh z baterii / (1 − straty ładowania)
```

## Zastrzeżenie

Kalkulator ma charakter poglądowy. Wyniki zależą od wpisanych danych i przyjętych założeń. Dane pochodzą z materiałów importera (WLTP) oraz testów redakcji motoryzacyjnych, lista źródeł jest na stronie. Stan danych: wrzesień 2026.
