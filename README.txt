#####################################
#### APLIKACJA REJESTR PRODUKTÓW ####
#####################################

Stworzyć aplikacje umożliwiająca zarządzającą tabelką produkty.
Aplikacja ma umożliwić wykonywanie podstawowych operacji CRUD na rekordach tabeli.
Aplikacja powinna działać w oparciu wzorca: Single-page application.

#Podstawowe wymagane funkcjonalności aplikacji:
- Tabela z lista produktów
- Formularz dodania/edycji produktu
- Usuwanie produktów

#Dodatkowe mile widziane funkcjonalności:
- Paginacja tabeli produktów
- Możliwość sortowania elementów tabeli po kolumnie
- Możliwość wyszukiwania elementów w tabeli,
- Formularz dodania/edycji umieszczony produktu w oknie modalnym  

#Krótki opis aplikacji:
W głównym widoku aplikacji powinna znajdować się tabela (GRID) z listą dostępnych produktów.
Następnie przy każdym produkcie musi być dostępna akcja z możliwością edycji i usunięcia produktu.
Nad tabelka powinien znajdować się button umożliwiający dodanie nowego produktu.


#Technologie użyte do realizacji zadania

Warstwa Klienta:
- HTML
- JavaScrip
- Framework AngularJS (obowiązkowy)
- Dowolne inne, dodatkowe narzędzia JS, CSS, moduły AngularJs

Warstwa Serwera:
- PHP 
- Dowolny Framework PHP (nieobowiązkowy, preferowany Yii, Yii2) 

DB
- Należy wykorzystać baze umieszcona w projkecie:
  Katalog server/db.
  Można korzystać z dowolnej bazy danych MySql, PgSql, SQLite lub cała obsługę zrobić na plikach JSON lub csv   
