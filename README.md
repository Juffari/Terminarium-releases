# Terminarium

Terminarium to desktopowa aplikacja dla Windows do planowania i prowadzenia terminarza pobytów. 
Projekt powstał z myślą o codziennej pracy na oddziale w ośrodku, lub w hotelu, gdzie liczy sie szybki podgląd obłożenia łóżek, wygodne zarządzanie pobytami i możliwie prosty obieg informacji.

Interfejs jest nastawiony na praktykę: pokazuje sale i łóżka w układzie kalendarzowym, pozwala sprawnie dodawać oraz edytować pobyty, a przy tym zachowuje lokalny charakter aplikacji desktopowej z automatycznymi aktualizacjami i kopiami zapasowymi.

## Nota uwag

TERMINARIUM JEST NAPISANE W 100% PRZEZ SZTUCZNĄ INTELIGENCJĘ ChatGPT Codex.
Nie ukrywam tego, nie przypisuję sobie wykonania tej aplikacji, szczerze przyznam - nie napisałem ani jednej linijki kodu, przez co absolutnie nie mogę uznać, że Terminarium jest moim dziełem. 
Mój natomiast jest pomysł, wszelkie wprowadzane zmiany, design, funkcje są z mojego pomysłu i wymyślenie aplikacji jak najbardziej przypisuję sobie. 

Korzystając z Terminarium weź pod uwagę, że jest to projekt amatorski, nie jestem programistą ani profesjonalistą, Terminarium zostało stworzone jako potrzeba dla placówek oraz jako projekt VibeCodingu.
Przed użyciem aplikacji zapoznaj się z tym tekstem, zastanów się czy chcesz go używać w profesjonalnych miejscach, gdyż korzystanie z Terminarium może wiązać się z wyciekiem wrażliwych danych. 
Nie zapewniam żadnej gwarancji bezpieczeństwa podczas korzystania z Terminarium.
Mimo tego chciałbym, aby projekt się rozrósł, zachęcam więc przede wszystkim do przetestowania.

Najwrażliwszą kwestią jest baza danych, która jest lokalna, znika bezpośrednie ryzyko włamania i przekierowania, zostają jedynie fizyczne opcje, lub całkowite przejęcie kontroli nad jednostką i zwyczajne skopiowanie plików db. 

## Najwazniejsze mozliwosci

- terminarz pobytów w widoku sal i łóżek.
- dodawanie, edycja, przenoszenie i zamiana pacjentów między łóżkami
- podgląd długosci pobytu, oznaczeń pacjenta i zabiegów
- kolorowanie nagłówków sal według aktualnego składu płci
- wyszukiwanie pacjentów i szybka nawigacja po harmonogramie
- podgląd wydruku z wyborem zakresu stron
- lokalne kopie zapasowe oraz przywracanie danych
- logowanie użytkowników i kontrola tworzenia kolejnych kont
- okno "Co nowego?" po aktualizacji
- automatyczne aktualizacje aplikacji w wydaniach Windows

## Dla kogo jest ten projekt

Terminarium jest tworzone jako narzędzie robocze, a nie pokazowa makieta. Najlepiej sprawdza się tam, gdzie potrzeba stałego podglądu zajętosci łóżek, planowania pobytów na wiele dni do przodu i szybkiego reagowania na zmiany bez przebijania się przez rozbudowane systemy.

## Stos technologiczny

- Electron
- Next.js
- React
- TypeScript
- better-sqlite3

## Uruchomienie lokalne

### Wymagania

- Node.js 22+
- npm
- Windows

### Tryb deweloperski

```bash
npm install
npm run dev
```

Polecenie uruchamia warstwę webową i okno desktopowe aplikacji.

### Build aplikacji webowej

```bash
npm run build:web
```

### Pakowanie aplikacji Windows

```bash
npm run dist:win
```

## Wydania

Repozytorium kodu zródłowego służy do rozwoju aplikacji, a publikowane wydania instalatora Windows trafiają do repozytorium GitHub Releases:

`Juffari/Terminarium-releases`

## Stan projektu

Projekt jest rozwijany aktywnie i iteracyjnie. Kolejne wersje skupiają sie na usprawnianiu codziennej pracy, porządkowaniu interfejsu oraz dopracowywaniu funkcji, które realnie przydają sie podczas planowania pobytów.

## Dalsze perspektywy

Terminarium będzie ciągle aktualizowane i dopracowywane, nowe aktualizacje wychodzą bez uprzedzenia, czasami kilka w ciągu dnia. 

Co planuję w dalszych aktualizacjach?:
- tworzenie własnego Terminarium
    - pojawi się możliwość dodawania i usuwania sal wraz z przypisanymi łóżkami - inaczej mówiąc kreowania swojej placówki, oddziału
- dodam możliwość ręcznego wpisywania zabiegów, lub całkowitego wyłączenia tego panelu
- będzie możliwe ręczne dostosowanie kolorystyki zarówno w dark jak i light mode dla:
    - pasków pobytu
    - akcentów tła
    - przycisków
    - wiodącego koloru aplikacji
- dodam możliwość zgłaszania błędów 
- pełen katalog aplikacji z opisem każdej funkcji, niuansów i czego tylko chciałby wiedzieć nowy użytkownik

## Autor

Michał "Mesję" Kozłowski

