Ulubione Przepisy Kulinarnych

Spis Treści

-Opis Projektu
-Funkcje
-Wymagania
-Instalacja
-Użytkowanie
-Struktura Kodu
-Przykładowe Dane Wejściowe
-Wkład


Opis Projektu
Ulubione Przepisy Kulinarnych to aplikacja internetowa umożliwiająca użytkownikom zarządzanie kolekcją ulubionych przepisów. Użytkownicy mogą dodawać nowe przepisy, edytować istniejące, komentować przepisy innych użytkowników oraz je oceniać. Projekt został stworzony przy użyciu JavaScript i innych technologii webowych, działając na lokalnym serwerze.

Funkcje
-Dodawanie Przepisów: Użytkownicy mogą dodawać nowe przepisy kulinarnych.
-Edytowanie Przepisów: Możliwość edytowania istniejących przepisów.
-Usuwanie Przepisów: Możliwość usuwania dodanych przepisów.
-Przeglądanie Przepisów: Możliwość przeglądania wszystkich dodanych przepisów.
-Komentowanie: Możliwość komentowania przepisów innych użytkowników.
-Ocenianie: Możliwość oceniania przepisów.
   Wymagania
-Do uruchomienia projektu potrzebne są:

Node.js
npm (Node Package Manager)
Instalacja
Sklonuj Repozytorium:

bash
Copy code
git clone https://github.com/justenes/Mvc-lab-project
cd favori-yemek-tarifleri
Zainstaluj Wymagane Pakiety:

Copy code
npm install express ejs

Uruchom Lokalny Serwer:

node app.js

Otwórz w Przeglądarce:
Po uruchomieniu lokalnego serwera, otwórz przeglądarkę i przejdź pod adres http://localhost:3000.

Użytkowanie
Dodawanie Nowego Przepisu:

Kliknij przycisk "Dodaj Nowy Przepis".
Wprowadź wymagane informacje (nazwa, składniki, sposób przygotowania itp.).
Kliknij przycisk "Zapisz".
Edytowanie Przepisu:

Wybierz przepis, który chcesz edytować.
Na stronie szczegółów przepisu kliknij przycisk "Edytuj".
Wprowadź potrzebne zmiany i kliknij "Zapisz".
Usuwanie Przepisu:

Wybierz przepis, który chcesz usunąć.
Na stronie szczegółów przepisu kliknij przycisk "Usuń".
Przeglądanie Przepisów:

Na stronie głównej możesz przeglądać wszystkie przepisy.
Kliknij na przepis, aby zobaczyć szczegóły.
Komentowanie i Ocenianie:

Na stronie szczegółów przepisu napisz komentarz w polu komentarzy i kliknij przycisk "Wyślij".
Aby ocenić przepis, wybierz odpowiednią ocenę w sekcji oceniania.
Struktura Kodu

recipesCont.js 
public/styles
views 
recipes
shared
app.js
data.js


