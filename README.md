# GK MANAGER — starter PWA

## Co zawiera
- responsywny interfejs dark UI,
- moduły: Start, Budowy, Kalkulator, Ekipa, Więcej,
- lokalny zapis danych w przeglądarce (`localStorage`),
- manifest PWA i service worker dla podstawowego działania offline,
- eksport kopii lokalnych danych do JSON.

## Ważne ograniczenia wersji 0.1.0
To jest wersja startowa do wdrożenia i testów. Nie ma jeszcze kont użytkowników, synchronizacji między urządzeniami, współdzielenia danych ani trwałej bazy chmurowej. Kalkulator jest orientacyjny i nie zastępuje projektu ani dokumentacji systemowej.

## Publikacja przez GitHub + Vercel
1. Utwórz repozytorium GitHub i wgraj wszystkie pliki z tego folderu do głównego katalogu repozytorium.
2. Zaloguj się do Vercel przez GitHub.
3. Wybierz Add New → Project i zaimportuj repozytorium.
4. Dla tej statycznej aplikacji nie ustawiaj Framework Preset (Other), Build Command ani Output Directory. Wdróż projekt.
5. Otwórz przydzielony adres HTTPS w Safari na iPhonie.
6. Safari → Udostępnij → Dodaj do ekranu początkowego.

Pliki ikon `icon-192.png` i `icon-512.png` są wymagane przez manifest. Dodaj własne kwadratowe ikony PNG o tych nazwach przed publikacją. Jeśli ich nie ma, aplikacja nadal może otwierać się w Safari, ale instalacja PWA może mieć niepełną ikonę.
