# System Rezerwacji Stolika w Restauracji "Smaki Świata"

## Specyfikacja Projektu Informatycznego

### 1. Wstęp

Projekt 'Smaki Świata' to kompleksowy system informatyczny umożliwiający klientom restauracji rezerwację stolików przez stronę internetową.  
Użytkownik może założyć konto, zalogować się, zarezerwować stolik na konkretny dzień i godzinę, a także przeglądać historię swoich rezerwacji.  
System został zaprojektowany z myślą o prostocie obsługi oraz dostępności na urządzeniach mobilnych.

### 2. Funkcjonalności

- Rejestracja nowego użytkownika z weryfikacją danych.
- Logowanie i wylogowanie użytkownika.
- Rezerwacja stolika (wybór daty, godziny, liczby osób i dostępnego stolika).
- Wyświetlanie dostępnych stolików na podstawie bazy danych.
- Historia rezerwacji (podział na nadchodzące i minione).
- Podgląd danych użytkownika (tylko do odczytu).
- Zakładki informacyjne: Kontakt oraz O nas.

### 3. Interfejs użytkownika

System posiada nowoczesny i intuicyjny interfejs, responsywny i wygodny zarówno na komputerach, jak i urządzeniach mobilnych.  
Główne ekrany:  
- Ekran logowania i rejestracji  
- Panel użytkownika (Moje dane)  
- Widok rezerwacji stolika  
- Historia rezerwacji  
- Strony informacyjne (Start, Kontakt, O nas)

### 4. Ograniczenia i Założenia

- System nie obsługuje płatności online.
- Obsługuje jeden lokal gastronomiczny.
- Przeznaczony do działania na przeglądarkach Chrome, Firefox, Safari.
- Liczba aktywnych użytkowników: około 1000 miesięcznie.
- Średnia liczba rezerwacji dziennie: 20–50.

### 5. Technologie

| Warstwa       | Technologia                  | Uzasadnienie                              |
|---------------|-----------------------------|------------------------------------------|
| Frontend      | Angular                     | Komponentowa architektura, wsparcie mobilne |
| Backend       | Spring Boot (Java)          | Szybki development REST API, bezpieczeństwo |
| Baza danych   | MySQL                       | Stabilność, wydajność zapytań SQL        |
| Stylowanie    | CSS3                        | Responsywny, nowoczesny interfejs        |
| Hosting       | XAMPP / Apache (lokalnie)   | Szybka konfiguracja środowiska testowego |

### 6. Opis techniczny aplikacji

- Moduł logowania i rejestracji z backendową walidacją.
- Komponenty rezerwacji i historii rezerwacji.
- REST API komunikujące frontend z backendem.
- Baza danych zarządzana przez MySQL, importowana przez phpMyAdmin.

---

## Autor projektu

**Mateusz Biernacki**  
Frontend developer (Angular), odpowiedzialny za główną architekturę interfejsu użytkownika oraz integrację z backendem.

---

## Współuczestnicy projektu grupowego na studiach

- **Filip Piskorz** – frontend developer (Angular), współtworzenie komponentów UI i stylowanie.
- **Bartek Krawiś** – backend developer (Java), implementacja logiki biznesowej i REST API.
- **Martyna Królikowska** – projektantka wizualna i autorka specyfikacji, opracowanie makiet graficznych i dokumentacji.

Projekt realizowany jako praca zespołowa w ramach przedmiotu informatycznego na studiach.

---

