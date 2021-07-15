# Kalendarz Arkadiowy

Autor: Monolith

# Instalacja

Pobrać pliki *.xml, a następnie przeciągnąć je do okienka Mudleta lub zainstalować przez Package Manager.
Przed instalacją nowych należy skasować stare.
Do działania kalendarza nie są wymagane żadne dodatkowe skrypty.

## Użytkowanie

Skrypt wyswietli predykcje pelni/nowiu/swiat etc.

W Imperium:
* ```/kal``` - wyswietlenie obliczen najblizszej pelni, swiat etc.

W Ishtar:
* ```/kal``` - jesli nie byl zdefiniowany wariant wyswietli wyliczenia wg wariantu "co 30 dni" jako wariantu domyslnego
* ```/kal 0``` - wyswietli warianty aktualnego miesiaca (zeruje wariant) (dane archiwalne)
* ```/kal xx``` - xx to wariant , ktory ma byc uzyty do obliczen (1 do 5) (dane archiwalne)
* ```lua wyswietl_warianty_ishtar(xx)``` - xx to numer miesiaca, wyswietla zadany miesiac i jego warianty niezaleznie od domeny/aktualnego miesiaca (dane archiwalne)
