# Task 1
## Subtask 1
Tylko 8 :disappointed: 
## Subtask 3
Zdecydowałam się na udział w tym challengu, ponieważ chcę wejść do branży IT. Chcę przede wszystkim znaleźć w tym miejscu dodatkową dawkę motywacji i wsparcia (girl power :muscle:).  
Przez ostatnie trzy lata zajmowałam się w domu dzieckiem, więc ono stało się moim centrum wszechświata, ale po satelitach, w postaci głosu mojego zajawionego swoją pracą męża programisty, krążyły tematy devowe. No i jestem.
~~Przypadek?~~ 😉
## Subtask 4
1. Aplikacja służy do dodawania i edycji zawodników piłki nożnej oraz tworzenia raportów z odbytych meczów, w celu śledzenia statystyk zawodników i weryfikacji ich osiągnięć. 
2. Aplikacja pozwala użytkownikowi:
- zalogować się oraz wylogować,
- dodać nowego zawodnika (m.in. dane personalne, klubu), 
-  edytować już dodanego zawodnika,
-  edytować widok listy zawodników modyfikując wyświetlane kolumny,
-  sortować listę z graczami w różnych wariantach,
-  wydrukować listę zawodników wraz z potrzebnymi danymi,
-  przefiltrować dane w celu szybszego odnalezienia szukanego rekordu,
-  dodać nowy mecz, wyświetlić oraz edytować istniejący,
-  dodać nowy raport, wyświetlić oraz edytować istniejący,
-  wyszukać interesujących nas danych z pomocą okna wyszukiwania (search),
-  zmienić język aplikacji na angielski,
-  skontaktować się z działem IT,
-  przypomnieć hasło do aplikacji z wykorzystaniem odpowiedniego formularza;
3. Interfejs jest dość prosty, ale dla mnie przez to nie wygląda profesjonalnie. Część "buttonów" jest w języku polskim, ale są i te w języku angielskim- od razu rzuca mi się to w oczy i odrzuca. Osobiście uważam, że nad tą aplikacją należałoby jeszcze sporo popracować. 
4.  Większość aplikacji jest intuicyjna, ale np. interfejs nie oferuje wszystkich funkcjonalności na stronie głównej- brak zakładek "MECZE" i "RAPORTY". Nie ma możliwości przejścia do nich ze strony głównej- trzeba wejść w graczy, później kliknąć na wybranego i dopiero wówczas jesteśmy w stanie przeglądać zakładki mecze i raporty. Zabiera to dużo czasu, jeśli ktoś chce szybko przejrzeć np. ostatnie raporty. Jest to nieintuicyjne. 
5. Znalazłam sporo błędów, oczywiście polegam tylko na swojej intuicji, oto one:
- **DODAWANIE NOWEGO GRACZA**:
- jest możliwość zapisania gracza, wpisując w polu imię i nazwisko cyfry i znaki specjalne (intuicyjnie oczekujemy liter),
-  udało się dodać gracza urodzonego w bieżącym roku- brak ograniczeń co do wieku zapisywanych zawodników,
- przy podaniu błędnego formatu maila, nie udaje się zapisać gracza, ale nie podświetla się nam okienko z mailem na czerwono- aplikacja nie odsyła nas gdzie zrobiliśmy błąd, po prostu nie możemy zapisać, ale nie wiemy dlaczego,
- w przypadku gdy pole oznaczone gwiazdką zostawimy puste- podświetla się ono na czerwono i pojawia się informacja o uzupełnieniu wymaganego pola (co jest ok), ale nie przesuwa się w to miejsce samoistnie kursor- musimy przescrollować się ręcznie i odnaleźć to pole,
- można dodać nr telefonu składający się nawet z jednej cyfry (intuicyjnie powinna być minimalna liczba znaków i maksymalna),
- można zapisać wagę, wzrost z ujemnymi wartościami lub bardzo wysokimi (znów brak ograniczeń), 
- w polach dot. dodania linków do portali społecznościowych zawodników- istnieje możliwość zapisu z wykorzystaniem jakiejkolwiek strony, a nie mającej w swoim url strony z nazwą konkretnego portalu: tj. facebook, 90 minut, łączy nas piłka, youtube, lub z wykorzystaniem zwykłego tekstu, a nie linku,
- przyciski SUMBIT i CLEAR są w języku angielskim, a reszta informacji w języku polskim,
- **EDYCJA GRACZA**:
- w polu edycji gracza przycisk CLEAR nie działa jak należy- moim zdaniem dane powinny zostać wymazane, usunięte z wszystkich pól, a tak się nie dzieje,
- istnieje możliwość wpisania w polu pozycja gracza, imię, nazwisko - liczb, co w mojej intuicji powinno być ograniczone do liter,
- **ZAKŁADKA GRACZE**:
- po najechaniu kursorem na danego zawodnika, podświetla się rekord, ale nie ma kursora, wskazującego, że można w niego kliknąć,
- kolumny mecze i raporty nie dają sie posortować,
- po użyciu funkcji sortowania zawodników i odświeżenia strony, widok aplikacji nie wraca do widoku podstawowego- takiego, jaki był przed sortowaniem,
- **MECZE I RAPORTY**:
- dodanie meczu- jest możliwe ręczne wpisanie drużyny zawodnika, moim zdaniem te dane powinny się same zaciągać z systemu, w innym razie można wpisać randomową nazwę drużyny,
- nie jest oznaczone gwiazdką WOJEWóDZTWO, a okazuje się że te dane jest wymagane do stworzenia raportu i ostatecznie i tak musimy je wypełnić (strata czasu),
- widok raportu wymaga przesuwania w prawo i lewo, strona się nie mieści, co jest irytujące,
- lista raportów i meczów zawodnika i ich widok na urządzeniach mobilnych się rozjeżdża,
- przycisk służący zapisaniu raportu (SAVE) jest w języku angielskim, reszta informacji po polsku,
- **PRZYPOMINANIE HASŁA**
- przy wprowadzeniu w formularzu przypominania hasła adresu email z błędnym formatem maila- formularz przechodzi dalej (brak wyświetlanego błędu),
- **INNE**:
- niska wydajność strony apki,
- część funkcjonalności aplikacji jest nieresponsywna;

# TASK 2
## Subtask 3
Po co piszemy przypadki testowe? 
Przypadki testowe pomagają nam w uporządkowaniu pracy testera i w ogóle projektu- każdy ma wówczas wgląd do napsianych przypadków testowych- jest to klarowne, pozwala zaoszczędzić czas i zorganizować pracę "załogi" testerskiej. Pisanie negatywych i pozytywnych przypadków testowych pozwala także na szybsze ujawnienie błędów np. w wymaganiach- już na wstępie możemy sprawdzić ewentualne niedociągnięcia. Posiadanie solidnej bazy przypadków testowych pozwala na większe pokrycie aplikacji testami. 
 
