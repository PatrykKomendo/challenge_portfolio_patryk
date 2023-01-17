# Task 1

## Subtask 1
Wynik z testu: 9/10 punktów :smile:

## Subtask 3
### 🧑‍💻 Cześć! Mam na imię Patryk. 

Zdecydowałem się na wzięcie udziału w challeng'u **DareIT** dla testerów manualnych, ponieważ zależy mi na sprawdzeniu/poszerzeniu swoich umiejętności testerskich poprzez praktykę - o którą trudno na początku drogi testera, a jednocześnie jest tak ważna. Chcę wykorzystać szansę na stworzenie portfolio oraz poznanie nowych ludzi, którzy również zainteresowali się testowaniem oprogramowania/są testerami od lat. Lubię wyzwamnia, dlatego spróbuję sporstać wszystkim zadaniom w tym projekcie. Głęboko wierzę, że pomoże mi to w zdobyciu wymarzonej pracy i jednocześnie będzie dobrą zabawą. Jeżeli chodzi o moje zainteresowania to jestem fanem gier wideo 🕹️ , lubię także od czasu do czasu zagłębić się w świat astrofizyki. 🚀

## Subtask 4

 **1. Na czym polega ta aplikacja? Do czego służy?**
 
Futbol Kolektyw - platforma skautingowa to aplikacja umożliwiająca po zalogowaniu na przeglądanie dodanych w aplikacji graczy, umożliwia również ich dodawanie i edycję. Istnieje również możliwość dodawania i edycji meczów oraz raportów. Została również udostępniona opcja "Rozpoczij mecz", w której użytkownik jest w stanie wprowadzić konkretne akcje zawodnika wykonane w meczu i prześledzić je w widoku edycji meczu dla gracza. Aplikacja dostępna jest w dwóch językach - polskim oraz angielskim.

 **2. Jakie funkcjonalności znajdują się w aplikacji? Do czego służą. Czy są intuicyjne, czy może byś coś zmienił_a? (Nie bój się wyrażać opinię!)**
 
💡 Funkcjonalności jakie są dostępne to: 

Logowanie do aplikacji, które po wprowadzeniu właściwych danych użytkownika przekierowuje nas na stronę główną aplikacji oraz zmiana języka aplikacji (dostępny polski i angielski). Istnieje możliwość przypomnienia hasła. Po kliknięciu w przycisk logowania aplikacja przekierowuje użytkownika na stronę główną.

Z poziomu strony głównej mamy możliwość:

- sprawdzenia w sekcji "Aktywność" ostatnio stworzonego gracza, ostatnio zaktualizowanego gracza, ostatnio stworzony mecz, ostatnio zaktuallizowany mecz i ostatnio zaktualizowany raport.

- dodania nowego gracza za pomocą funkcji "DODAJ GRACZA" w sekcji "Linki pomocnicze" - **myślę, że te opcję można przenieść do lewego panelu, lub zmienić nazwę sekcji, ponieważ "Linki pomocnicze" kojarzą mi się bardziej z linkami do kontaktu z pomocą techniczną.**

- po lewej stronie znajduje się panel z funkcjami: przejścia do strony głównej ("Strona główna"), przekierowania do listy graczy ("Gracze"), zmiany języka ("English/Polski") oraz wylogowania z aplikacji ("Wyloguj") - **z tego panelu myślę, że warto przenieść opcję wylogowania w prawy górny róg widoku aplikacji - większość aplikacji posiada właśnie tam opcję wylogowania/dostępu do opcji konta, więc automatycznie użytkownik może tam szukać tego przycisku. Szkoda trochę, że nagłówek "Scouts panel" na niebieskim pasku w lewym górnym rogu nie jest zlinkowany ze stroną główną - bardzo długo klikałem w niego z nadzieją na to, że zostanę przekierowany właśnie na stronę główną 😆**

- w sekcji Scouts Panel" mamy link do kontaktu z zespołem deweloperskim ("DEV TEAM Contact").

Strona "Gracze" zawiera listę wszystkich utworzonych graczy z informacjami takimi jak: "Imię", "Nazwisko", "Wiek", "Pozycja", "Klub",  "Recenzja", "Mecze", "Raporty"(wyświetla się 10 graczy, można otwierać kolejne podstrony za pomocą przycisków "<  >"). Istnieje możliwość sortowania oraz filtrowania. **Tutaj dla mnie największym problemem jest poziomy suwak przewijania strony - jest on niestety słabo widoczny, zlewa się z tłem strony, a dodatkowo wygląda to nieestetycznie, gdy użytkownik przestaje widzieć większość informacji - wiąże się ten problem z polami prowadzania danych, o czym jezcze wspomnę. 😉**

Dodatkowe opcje dla listy graczy: pobranie listy w formacie CSV, wydrukowanie oraz wybranie wyświetlanych kolumn.

Po kliknięciu w danego zawodnika użytkownik powinien zostać przekierowany do widoku edycji gracza.

Na stronie edycji gracza użytkownik może uzupełniać i aktualizować informację o zawodniku. Jest przycisk zapisu oraz wyczyszczenia wprowadzonych zmian. **Tuaj jest kilka pozycji, które mogą być niezrozumiałe dla nowych użytkowników- pola edycji "Łączy nas piłka" i "90 minut" - jest dla mnie niezrozumiałe to, co tutaj powinien wpisywać użytkownik. Brakuje mi tutaj również przycisku "WSTECZ", który bez zapisania wprowadzonych zmian przekierowuje użytkownika do poprzedniej strony.**

W tym widoku (edycja gracza) na panelu po lewej stronie pojawiły się 2 dodatkowe sekcje: "Mecze oraz "Raporty".

Na stronie "Mecze" użytkownik widzi listę z takimi informacjami jak: Drużyna zawodnika, "Zdobyte gole", "Stracone gole", "Drużyna przeciwna", "Data", "Czas gry", "Recenzja", "Autor" oraz "Akcje". W sekcji "Akcje" mamy dostępne 3 opcje: "Edytuj", "Dodaj raport" oraz "Rozpocznij mecz".

Na stronie edycji meczu orpócz wprowadzania danych udostępniona została sekcja "Lista zdarzeń", która pozwala na śledzenie akcji wykonanych przez gracza w danym meczu.

Funkcja "Rozpocznij mecz" przekierowuje nas do strony z wirtualnym boiskiem. Nad boiskiem umieszczone są przyciski rozpoczęcia meczu (lub wznowienia), pauzy, zmiany połowy, anulowania wprowadzonych akcji jedna po drugiej, zapisu oraz chyba usunięcia - **przyciski nie są podpisane, nie do końca wiadomo od początku do czego służą**. Po najechaniu kursorem myszy na konkretny punkt na boisku i kliknięciu pojawiają się akcje możliwe do wykonania przez gracza. Po zapisaniu użytkownik widzi punkt, w którym dodał konkretną akcję. **musiałem chwilę się zastannowić zanim "odkryłem" na czym ta funkcja polega, myślę, że przydałby się jakiś tutorial dla nowych użytkowników.**

Użytkownik ma możliwość dodania meczu za pomocą przycisku "DODAJ MECZ" - na przekierowanej stronie znajduje się formularz do wypełnienia oraz przycisk "SUBMIT" i "CLEAR".

Na stronie "Raporty" użytkownik widzi listę raportów. W sekcji "Akcje" jest dostępna opcja "Edytuj" - która przekierowuje do strony edycji raportu. Użytkownik powinien widziec przycisk "DODAJ RAPORT".


 **3. Oceń interfejs aplikacji (wygląd) – czy Ci się podoba, czy nie?**

Zmieniłbym tło na stronie logowania - na takie jakie jest w pozostałych elementach aplikacji. Myślę, że fajnie, gdyby na tej stronie było też jakieś logo aplikacji. Ogólnie poza rozmieszczeniem niektórych elementów design mi się podoba - jest minimalistyczny, ale za to czytelny. Na stronie "Rozpocznij mecz" jest bardzo dużo pustego miejsca - może warto dodać tam jakąś instrukcję działania tej funkcjonalności? 🤔 Design raportów nie do końca mi się podoba - brakuje tutaj tego prostego, minimalistycznego podejścia jak w pozostałych elementach aplikacji. 

 **4. Czy aplikacja jest intuicyjna? (Intuicyjna, czyli np. nie masz problemu ze zrozumieniem, co należy kliknąć, żeby wejść do formularza dodawania nowego zawodnika piłki nożnej do systemu).**
 
 Na większość tego pytania odpowiedziałem podczas odpowiadania na pytanie 2 - najwięcej problemów zdecydowanie sprawiła mi funkcja "Rozpocznij mecz".

 **5. Czy zauważasz jakieś błędy? Albo coś wydaje Ci się błędem? Zapisz swoje przemyślenia w pliku. Tutaj masz na to miejsce, czas i przestrzeń! 😉**
 
 **:bug: Błędy, które znalazłem (a przynajmniej to, co wydaje mi się błędem 🕵️):** 
 
 **1. Strona logowania**
 
 - wybierając język polski - jeżeli wpiszemy nieprawidłowe dane logowania pojawi się odpowiedni komunikat walidacyjny - ale nieprzetłumaczony na język polski, mimo iż wszystkie inne elementy są w języku polskim. Pojawiający się komunikat walidacyjny doprowadza do tego, że button "ZALOGUJ" oraz opcja wyboru języka zmieniają swoje położenie i są ucięte.

- tutaj też nasuwa się pytanie co z nazwą "Scouts panel" - czy jest to uznawane jako nazwa własna, czy też powinna być przetłumaczona.

- opcja "Przypomnij hasło" - nieprawidłowa weryfikacja adresu email - można zostawić pole puste/uzupełnić adresem o nieprawidłowym formacie i po kliknięciu button'a "WYŚlIJ" - pojawia się komunikat walidacyjny, że "Wysłano wiadomość na podany adres email". Zostaje zablokowany button "WYŚLIJ" (jeżeli użytkownik się pomyli i sam się zorientuje, bądź wejdzie na skrzynkę pocztową i nie otrzyma wiadomości zapewne będzie chciał ponowić próbę przypomnienia hasła - użytkownik musi najpierw wrócić do strony logowania). 

**2. Strona główna**

- na początek literówka, którą wyłapałem - "zaaktualizowany" zamiast "zaktualizowany" w sekcji "Aktywność"

- tutaj też podobnie jak na stronie logowania "Scout panel" nie został przetłumaczony, podobnie "DEV TEAM CONTACT".

- szkoda, że info "Ilość graczy", "Ilość meczy", "Ilość raportów", "Ilość akcji" nie są podlinkowane i po kliknięciu nie przekierowują użytkownika do odpowiedniej strony aplikacji (to bardziej improvement niż bug). 😉

- jeżeli użytkownik wprowadzi i nie zapisze zmian na stronie "Rozpocznij mecz" to na stronie głównej pojawia się dodatkowa sekcja "Niezapisany mecz". Pojawia się tam opcja "WRÓĆ DO RAPORTU" - podany link nie działa.

**3. Strona "Gracze"**

- brak możliwości sortowania po ilości rozgranych meczy oraz raportów - chyba, że takie jest założenie. 😄

- pola wprowadzania danych nie są ograniczone daną ilością znaków, przez co uzytkownik może wpisać dużą liczbę znaków i cały widok tabeli się "rozjeżdża".

- nazwy button'ów nie zostały spolszczone ("SUBMIT" oraz "CLEAR").

**Strona "Edycja gracza"**

- brak ograniczeń wprowadzania ilości znaków w polach do uzupełniania danych.

- brak/niewłaściwa walidacja: możliwość wpisywania różnych typów znaków w polu "Telefon", brak weryfikacji poprawności adresu e-mail, wpisywanie cyfr/znaków specjalnych w polach "Imię", "Nazwisko". W polach "Waga" oraz wzrost" możliwość podawania ujemnych wartości, zera, górna granica również nie została ustalona. Pola takie jak "Poziom rozgrywek", "Główna pozycja", "Pozycja alternatywna" powinny być polami typu select - podobnie jak jest to w przypadku pola "Dominująca noga" (mamy w piłce nożnej z góry ustalone poziomy rozgrywek, pozycje etc, a tutaj użytkownik jest w stanie wpisać co tylko przyjdzie mu do głowy 😅). Opcja "DODAJ JĘZYK" - podobnie uważam, że pole typu select byłoby lepszym wyborem. Część walidacji pozornie działa (pola required potrzebują jakiejkolwiek wartości, ale wystarczy wprowadzenie spacji).

- możliwość edycji i "stworzenia" dwóch (lub więcej) identycznych graczy - jedynie ID będzie inne (musi być unikalne). 

- nazwy województw piszemy małą literą (pole "Województwo").

**4. Zakładka "Mecze"**

- brak możliwości sortowania wg kategorii, rownież brak filtrowania (improvement 😉) - tutaj też nie ma opcji pobrania pliku i drukowaia - nie wiadomo, czy to błąd, ale skoro zostało to zaimplementowane dla zakładki "Gracze" to może warto udostępnić takie rozwiązanie również tutaj? Podobnie jest w zakładkach "Mecze" oraz "Raporty".

**Funkcja DODAJ MECZ**

- tutaj również część walidacji pozornie działa (pola required potrzebują jakiejkolwiek wartości, ale wystarczy wprowadzenie spacji). W polu "Data" możemy wybrać taką datę jak 01.01.0001 lub 01.01.9999. Użytkownik może podać ujemny czas gry lub ogromne wartości (mecz piłki nożnej trwa 90 minut + ewentualne dogrywki). Numery na koszulkach też nie posiadają wartości ujemnych. 

- nie wszystko zostało przetłumaczone na język polski - "Web match" oraz "Gerneral". Podobnie button'y "SUBMIT" oraz "CLEAR".

**Funkcja "Dodaj raport"**

- przycisk "CLEAR" jest tutaj niepotrzebny, ponieważ nie pełni żadnej funkcji (pola "ID gracza" oraz "ID meczu" są zablokowane).

**Funkcja "Rozpocznij mecz"**

- możliwość wprowadzenia większej liczby w sekcji "Połowa" niż 2 😅. Czas również jest nieograniczony, więc gracz mógł wykonać akcję np w 9999 minucie.

- możliwość wprowadzania akcji tylko przy włączonym czasie - gracz mógł np. podać, po 2 sekundach odzyskać piłkę i strzelić - a dłużej zajmie użytkownikowi wprowadzenie pierwszego podania. 

- możliwość wprowadzania i wykonywania takich akcji przez gracza jak np. strzał z rzutu karnego poza linią boiska.

- nie działa przycisk z ikoną śmietnika - nie wiem, czy powinno służyć anulacji wprowadzonych zmian, czy usunięciu meczu, ale po kliknięciu wydaje się, że nie ma żadnej reakcji.

- "Zle przyjecie" zamiast "Złe przyjęcie" w akcji "Strata". "Przejecie podania" zmiast "Przejęcie podania" w akcji "Odbiór".

**Strona "Raporty"**

- przycisk "DODAJ RAPORT" przekierowuje do zakładki "Mecze".

**Strona Edycji raportu dla gracza**

- link do meczu prowadzi do strony z komunikatem 404- page not found. Błąd można zaobserwować równiez w Devtoolsach w zakładce "Network". 

- tutaj również nie wszystkie elementy zostały spolszczone.

- nieograniczone pola tekstowe.
