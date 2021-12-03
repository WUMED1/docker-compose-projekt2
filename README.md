# Projekt zaliczeniowy 
W repozytorium macie Państwo pliki końcowe projektu napisanego w php służącego do zapisywania się na newslettera poprzez adres email i administracyjnego przeglądania subskrybentów. Struktura plików jak i wszystkie skrypty umieszczone są w pliku skompresowanym programem 7-zip 
Jak zbudowany jest serwis oparty na localhost z apache2, mysql i phpmyadmin pokazane jest w tym linku https://www.youtube.com/watch?v=6fn55yrdwkk

Proszę napisać i umieścić w swoim repozytorium docker-compose.yml który stworzy nam 3 mikrousługi 
  1. apache2 na bazie opensuse. - usługa ta będzie realizować wyświetlanie skryptów i umieszczanie nowych rekordów w bazie mysql 
  2. baza danych mysql jako osobna mikrousługa oferująca bazę danych subskrybentów
  3. phpmyadmin do zarządzania bazą mysql
  
Repozytorium Państwa powinno zawierać zarówno docker-compose.yml jak również całą strukturę plików potrzebnych do uruchomienia serwisu zapisywania się do newslettera
