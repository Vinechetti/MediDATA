
# MediDATA 馃彞馃拤

### Programowanie obiektowe 2022/23 MMiAD - projekt zaliczeniowy.

Proste oprogramowanie s艂u偶膮ce do obs艂ugi bazy danych pacjent贸w dla o艣rodka zdrowia.

# U偶ycie
Przy pierwszym u偶yciu nale偶y uruchomi膰 plik setup.java, dzi臋ki czemu mo偶na skonfigurowa膰 konta pracownik贸w o艣rodka.

Dost臋pne s膮 trzy rodzaje kont:
* administrator - zarz膮dza kontami pracownik贸w
* lekarz - mo偶e edytowa膰 histori臋 chor贸b pacjenta, a tak偶e przyjmowane przez niego leki i inne informacje zwi膮zane z leczeniem
* piel臋gniarka - ma dost臋p do danych kontaktowych i adresowych pacjenta

Po skonfigurowaniu programu korzystamy z pliku login.java.

Dane logowania przechowywane s膮 w pliku acc, dane pacjent贸w - w pliku pacjenci.

Has艂a szyfrowane s膮 algorytmem SHA-256.

# Autorzy
* Mateusz Wi艣niewski - system logowania, uprawnie艅 i konfiguracji programu
* Aleksander Micha艂owski - system dodawania, usuwania oraz wyszukiwania pacjent贸w
* Oskar Kuchci艅ski - system edycji danych pacjent贸w
