---
name: Bug report
about: Create a report to help us improve
title: ''
labels: bug, critical, login
assignees: Dupa12-star

---

Błąd logowania - komunikat 'Invalid credentials' przy poprawnych danych
Użytkownik z rolą 'nauczyciel' nie może się zalogować do systemu pomimo wprowadzenia
prawidłowego loginu i hasła. System wyświetla błąd 'Invalid credentials'.
[Szczegółowy opis tego, co się dzieje]
Kroki do reprodukcji:
1. Otwórz stronę logowania (https://a.schoolmanager.com/login)
2. Wpisz login: jan.kowalski@szkola.pl
3. Wpisz hasło: Test123!
4. Kliknij przycisk "Zaloguj"
Oczekiwany rezultat: Użytkownik zostaje zalogowany i przekierowany do panelu nauczyciela
Rzeczywisty rezultat: Wyświetla się komunikat "Invalid credentials" i użytkownik pozostaje na stronie
logowania
Środowisko:
Windows 11, Chrome 120, Wersja aplikacji: 2.3.1
Priorytet:
Krytyczny
