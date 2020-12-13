# simple-rest-scrapper

Celem zadania jest stworzenie prostego scrappera danych z REST API. 

 1. Dane, które nasz scrapper ma pobrać to użytkownicy, ich albumy oraz zdjęcia. Testowe Api dostępne jest pod adresem: https://jsonplaceholder.typicode.com/guide.html (do pobierania albumów i zdjęć należy skorzystać z zagnieżdżonych urli jak np. https://jsonplaceholder.typicode.com/users/1/albums).
2. Wynikiem działania programu powinny być 3 pliki CSV users.csv,albums.csv oraz photos.csv oraz folder ze zdjęciami. Pliki CSV powinny posiadać kolumny odpowiadające atrybutom zwracanym z API. Dodatkowo plik photos.csv powinien posiadać kolumnę "file_path", która będzie ścieżką do lokalnie pobranego zdjęcia.
3. Aplikacja powinna pobierać dane wielowątkowo a konfiguracja liczby wątków powinna być dostępna z zewnętrznego pliku konfiguracyjnego.
4. Program powinien posiadać testy jednostkowe lub integracyjne, które będą mogły być uruchamiane bez połączenia do zewnętrznego API.
5. Aplikacja powinna być napisana w wersji Pythona >=3.7 oraz spełniać założenia dobrych praktyk pisania w tym języku
