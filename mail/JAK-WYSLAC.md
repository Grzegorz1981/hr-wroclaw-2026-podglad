# Mail z zaproszeniem — jak wysłać

Plik: `zaproszenie.html`

## Zanim wyślesz pierwszy raz

Grafiki muszą leżeć na serwerze pod adresem **hrwroclaw.pl/mail/img/**.
Poczta nie widzi plików z dysku — w mailu są pełne adresy internetowe.

Wgraj przez FTP katalog `mail/` do głównego folderu strony.
To bezpieczne: dokłada nowy folder, niczego nie nadpisuje.

Sprawdzenie: otwórz w przeglądarce
`https://hrwroclaw.pl/mail/img/logo.png` — powinno pokazać logo.

## Wysyłka (kopiuj-wklej)

1. Otwórz `zaproszenie.html` w przeglądarce (dwuklik).
2. `Ctrl+A` (Mac: `Cmd+A`) — zaznacz wszystko.
3. `Ctrl+C` (Mac: `Cmd+C`) — skopiuj.
4. W Gmailu/Outlooku kliknij **Nowa wiadomość**.
5. Kliknij w treść i `Ctrl+V` (Mac: `Cmd+V`).
6. Wpisz temat, adresatów, wyślij.

**Zawsze wyślij najpierw do siebie** i sprawdź na komputerze i na telefonie.

## Adresatów wpisuj w UDW (BCC)

Przy wysyłce do wielu osób adresy wpisuj w pole **UDW**, nie „Do".
Inaczej każdy odbiorca zobaczy adresy pozostałych — to naruszenie RODO.

## Czego się spodziewać

- Gmail, Outlook w przeglądarce, Apple Mail — wygląda jak w podglądzie.
- Outlook na Windows — może pominąć zaokrąglenia rogów. Treść i przyciski działają.
- Tryb ciemny — logo siedzi na białym pasku, więc nie zniknie.

## Zmiana treści

Tekst edytuj bezpośrednio w `zaproszenie.html` (dowolny edytor tekstu).
Grafiki podmieniaj w `mail/img/`, zachowując nazwy plików — wtedy nic
nie trzeba poprawiać w kodzie.

**Nie przenoś stylów do osobnego bloku `<style>`** — Gmail wycina je przy
wklejaniu i mail rozsypie się w goły tekst. Wszystko musi zostać wpisane
przy znacznikach, tak jak jest teraz.

## Wysyłka masowa

Przy większej liście (powyżej ~100 adresów) lepiej użyć MailerLite albo Brevo —
wkleja się tam kod źródłowy zamiast wyglądu, dochodzą statystyki otwarć
i wymagany prawnie link do wypisania się.
