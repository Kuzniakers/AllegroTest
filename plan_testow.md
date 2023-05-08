# Plan testów dla Allegro.pl

**Wersja:** 1.0  
**Data:** 01.05.2023  
**Przygotował:** Kuźniak Konrad

## Wstęp

### 1. Cel testów

- Celem testowania strony Allegro.pl jest zapewnienie wysokiej jakości oprogramowania, sprawdzenie poprawności funkcjonowania wszystkich funkcji serwisu oraz wykrycie i naprawa błędów, które mogą wpłynąć na doświadczenie użytkowników.

### 2. Zakres testów

- Zakres testów obejmuje wszystkie istotne funkcje serwisu Allegro.pl, takie jak logowanie, rejestracja, wyszukiwanie, filtrowanie, dodawanie do koszyka, realizacja zamówień, zarządzanie kontem oraz interakcje między kupującymi i sprzedającymi.

## Zasoby

### 1. Personel

- QA Engineer: odpowiedzialny za przeprowadzenie testów, raportowanie błędów oraz za nadzorowanie procesu testowania i analizę wyników testów.

### 2. Narzędzia

- TestRail: do zarządzania przypadkami testowymi i raportowania wyników testów.
- JIRA: do zarządzania zgłoszeniami błędów i śledzenia postępów.
- JMeter: do testowania strony pod obciążeniem

### 3. Środowisko testowe

- Sprzęt: Komputer stacjonarny oraz smartfon
- Przeglądarka: Chrome (wersja 88) oraz Mozilla Firefox (wersja 95)
- System operacyjny: Windows 10 Home, 64-bitowy system operacyjny oraz Android 11

## Podejście

### 1. Strategia testowania

- Wykonanie testów manualnych i eksploracyjnych w celu sprawdzenia funkcjonalności, kompatybilności, wydajności, użyteczności, bezpieczeństwa oraz lokalizacji serwisu Allegro.pl.

### 2. Metodyki

- Wykorzystanie metodyki Agile oraz Scrum w celu szybkiego reagowania na zmiany oraz ciągłego doskonalenia jakości oprogramowania.

### 3. Poziomy testowania

- Testy jednostkowe: przeprowadzone przez programistów na poziomie kodu.
- Testy integracyjne: sprawdzenie współpracy między różnymi modułami serwisu.
- Testy systemowe: testowanie całego systemu pod kątem spełnienia wymagań.
- Testy akceptacyjne: sprawdzenie, czy system spełnia oczekiwania użytkowników końcowych.

### 4. Schemat wykonania testów

- Przygotowanie środowiska testowego i narzędzi.
- Przeprowadzenie testów zgodnie z przypadkami testowymi.
- Dokumentacja i raportowanie wyników testów w TestRail.
- Zgłaszanie ewentualnych błędów w JIRA.
- Weryfikacja naprawionych błędów i aktualizacja wyników testów.  
- Komunikacja z zespołem programistów w celu poprawy jakości oprogramowania.

### 5. Harmonogram
1. **Czas trwania testów**:  
   Estymowany czas trwania testów wynosi 4 tygodnie.
2. **Kamienie milowe**:  
   - Rozpoczęcie testów: 01.05.2023
   - Zakończenie testów: 29.05.2023
   - Przekazanie wyników testów: 31.05.2023

### 6. Przypadki testowe
1. **Testy funkcjonalne**:
   - Rejestracja, logowanie i wylogowanie.
   - Wyszukiwanie, filtrowanie i sortowanie produktów.
   - Dodawanie produktów do koszyka i realizacja zamówień.
   - Zarządzanie kontem użytkownika (dane, historie zamówień, obserwowane produkty).
   - Dodawanie, edycja i usuwanie aukcji przez sprzedawcę.
   - Komentowanie i ocenianie transakcji.

2. **Testy kompatybilności**:
   - Testowanie na różnych przeglądarkach i urządzeniach.
   - Testowanie na różnych systemach operacyjnych.

3. **Testy wydajności**:
   - Testowanie czasu ładowania strony i poszczególnych elementów.
   - Testowanie strony pod obciążeniem.

4. **Testy użyteczności**:
   - Sprawdzenie czytelności, dostępności i intuicyjności strony.

5. **Testy bezpieczeństwa**:
   - Testowanie zabezpieczeń danych użytkowników.

6. **Testy eksploracyjne**:
   - Niekierowane testowanie strony w celu znalezienia ewentualnych błędów.

### 7. Metryki i kryteria zakończenia testów
1. **Metryki**:
   - Liczba znalezionych błędów.
   - Czas odpowiedzi na zgłoszenie błędu.
   - Liczba naprawionych błędów.

2. **Kryteria zakończenia testów**:
   - Wszystkie zgłoszone błędy są naprawione lub zaakceptowane jako ograniczenia systemu.
   - Żadne nowe krytyczne błędy nie są zgłaszane przez co najmniej 5 dni roboczych.
   - Osiągnięcie zadowalających wyników dla wszystkich metryk.

### 8. Procedury zarządzania ryzykiem i problemami
Identyfikacja, analiza i reagowanie na ryzyka i problemy, które mogą wystąpić podczas procesu testowania, takie jak opóźnienia, zmiany w wymaganiach, brak dostępności zasobów czy nieprzewidziane problemy techniczne.

### 9. Zakończenie
- Ten plan testów stanowi ramy pracy dla testowania serwisu Allegro.pl. W trakcie testów może być konieczne dostosowanie planu w odpowiedzi na zmiany w wymaganiach lub napotkane problemy. Po zakończeniu testów, należy przekazać wyniki testów, rekomendacje oraz ewentualne wnioski do zespołu deweloperskiego, aby wspólnie pracować nad doskonaleniem jakości serwisu Allegro.pl.

