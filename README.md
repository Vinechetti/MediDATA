
# MediDATA 🏥💉

### Programowanie obiektowe 2022/23 MMiAD - projekt zaliczeniowy.

Proste oprogramowanie służące do obsługi bazy danych pacjentów dla ośrodka zdrowia.

# Użycie
Przy pierwszym użyciu należy uruchomić plik setup.java, dzięki czemu można skonfigurować konta pracowników ośrodka.

Dostępne są trzy rodzaje kont:
* administrator - zarządza kontami pracowników
* lekarz - może edytować historię chorób pacjenta, a także przyjmowane przez niego leki i inne informacje związane z leczeniem
* pielęgniarka - ma dostęp do danych kontaktowych i adresowych pacjenta

Po skonfigurowaniu programu korzystamy z pliku login.java.

Dane logowania przechowywane są w pliku acc, dane pacjentów - w pliku pacjenci.

Hasła szyfrowane są algorytmem SHA-256.

# Autorzy
* Mateusz Wiśniewski - system logowania, uprawnień i konfiguracji programu
* Aleksander Michałowski - system dodawania, usuwania oraz wyszukiwania pacjentów
* Oskar Kuchciński - system edycji danych pacjentów
