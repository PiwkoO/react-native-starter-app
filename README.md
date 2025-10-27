# React Native: Field Notes

## Cel
Stwórz podstawową aplikację mobilną w **React Native (React)**, która wykorzystuje **natywną funkcję urządzenia** oraz **komunikuje się z API**. Aplikacja ma mieć **3–4 widoki**.


## Zakres i wymagania funkcjonalne
- **Natywna funkcja (min. 1):** wybierz i uzasadnij (np. aparat/kamera, lokalizacja GPS, wibracje/haptics, pliki/galeria).
- **API (min. 1 endpoint):** odczyt lub zapis danych (publiczne lub własne/mock).
- **Widoki (3–4):**
  1. **Lista notatek** (tytuł, data, miniaturka/znacznik lokalizacji).
  2. **Szczegóły notatki** (opis, zdjęcie/pozycja, akcje).
  3. **Dodaj/Edytuj** (formularz: tytuł, opis, dodaj zdjęcie **lub** pobierz lokalizację).
  4. *(Opcjonalnie)* **Ustawienia/O aplikacji** (akcenty dostępności, info o wersji).
- **Stan:** lokalny lub prosty store; brak trwałego storage wymagany, ale dopuszczalny.
- **Dostępność:** podstawowe etykiety i rozmiary celów dotyku (~44–48 px).

## Testowanie lokalne (w trakcie developmentu)
- Uruchom na **urządzeniu/emulatorze**.
- Pokaż: dodanie notatki, użycie **natywnej funkcji** (np. zrobienie zdjęcia lub pobranie GPS), wyświetlenie listy i szczegółów.
- Pokaż komunikację z **API** (np. pobranie listy lub zapis nowej notatki).
- Zweryfikuj: błędy/edge cases (brak uprawnień, brak internetu).

## Definition of Done (DoD)
- [ ] 3–4 kompletne widoki zgodne z opisem.
- [ ] Użyta co najmniej **1 natywna funkcja**.
- [ ] Integracja z **API** (co najmniej 1 żądanie).
- [ ] Czytelny UI + podstawowa dostępność.
- [ ] Aktualizacja `README.md` z opisem funkcji i sposobem testowania.
- [ ] Min. 3 logiczne commity.