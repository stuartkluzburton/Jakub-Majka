# stacja-paliw
UWAGA: katalog z rezultatami pracy oraz płytę należy opisać numerem, którym został podpisany arkusz, 
czyli numerem PESEL lub w przypadku jego braku numerem paszportu.
Wykonaj aplikację internetową portalu stacji paliw, wykorzystując pakiet XAMPP oraz edytor zaznaczający 
składnię.
Aby wykonać zadanie, należy zalogować się na konto Egzamin bez hasła. Na pulpicie znajduje się archiwum 
ZIP o nazwie pliki2.zip zabezpieczone hasłem: PaLiWo5&
Archiwum należy rozpakować.
Na pulpicie konta Egzamin należy utworzyć folder. Jako nazwy folderu należy użyć numeru zdającego, 
którym został podpisany arkusz. Rozpakowane pliki należy umieścić w tym folderze. Po skończonej pracy 
wszystkie wyniki należy zapisać w tym folderze.
Operacje na bazie danych
Do wykonania operacji na bazie należy wykorzystać tabelę samochody z polami: id (klucz główny), marka, 
model, rocznik, kolor, stan.
Obraz 1. Baza danych
Za pomocą narzędzia phpMyAdmin wykonaj operacje na bazie danych:
‒ Utwórz bazę danych o nazwie samochody
‒ Do bazy samochody zaimportuj tabele z pliku baza.sql z rozpakowanego archiwum
‒ Wykonaj zrzut ekranu po imporcie. Zrzut zapisz w formacie PNG i nazwij import. Nie kadruj zrzutu. 
Powinien on obejmować cały ekran monitora, z widocznym paskiem zadań. Na zrzucie powinny być 
widoczne elementy wskazujące na poprawnie wykonany import tabel
‒ Wykonaj zapytania SQL działające na bazie samochody. Zapytania zapisz w pliku kwerendy.txt.
Wykonaj zrzuty ekranu przedstawiające wyniki działania kwerend. Zrzuty zapisz w formacie JPEG 
i nadaj im nazwy kw1, kw2, kw3, kw4, kw5. Zrzuty powinny obejmować cały ekran monitora 
z widocznym paskiem zadań.
‒ Zapytanie 1: wybierające jedynie pola marka i rocznik z tabeli samochody dla samochodów koloru 
niebieskiego
‒ Zapytanie 2: zliczające ile jest samochodów marki Toyota lub Opel, których stan jest bardzo dobry
‒ Zapytanie 3: aktualizujące wartość pola stan na „dobry” w tabeli samochody dla samochodów
starszych niż 2004 rok
‒ Zapytanie 4: tworzące użytkownika jan na localhost z hasłem janKowalski1@
‒ Zapytanie 5: nadające użytkownikowi jan prawo jedynie do wybierania, wstawiania i aktualizacji 
danych w tabeli samochody
