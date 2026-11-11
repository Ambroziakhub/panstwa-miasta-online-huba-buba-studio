# Polityka Prywatności Aplikacji "Państwa Miasta"

**Ostatnia aktualizacja:** 11 listopada 2026 r.  
**Wersja:** 1.0  
**Identyfikator aplikacji (Package Name):** `com.panstwamiastahuba.game`  

---

## 1. Wstęp i Administrator Danych

Szanujemy Twoją prywatność i dbamy o ochronę Twoich danych osobowych. Niniejsza Polityka Prywatności wyjaśnia zasady zbierania, przetwarzania, przechowywania i ochrony danych w związku z korzystaniem z mobilnej aplikacji **Państwa Miasta** (zwanej dalej „Aplikacją”).

Administratorem Twoich danych osobowych jest:
- **Wydawca / Administrator:** Hubert Ambroziak (osoba prywatna)
- **Kontakt e-mail:** [ambroziak.hub@gmail.com](mailto:ambroziak.hub@gmail.com)

Aplikacja została stworzona w technologii Flutter i jest udostępniana w sklepie Google Play Store.

---

## 2. Jakie dane zbieramy i w jakim celu?

Gromadzimy wyłącznie dane niezbędne do prawidłowego funkcjonowania Aplikacji, w tym obsługi trybu wieloosobowego, profilu gracza, znajomych, czatu oraz moderacji i bezpieczeństwa.

### A. Konta Użytkowników i Autoryzacja
- **Rejestracja i logowanie:** Aplikacja wykorzystuje usługę **Firebase Authentication** pozwalającą na logowanie za pomocą konta Google (Google Sign-In).
- **Zbierane dane:** unikalny identyfikator użytkownika Firebase (UID), adres e-mail, podstawowe dane profilowe przekazane z konta Google (np. nazwa profilowa, zdjęcie profilowe).
- **Cel:** utworzenie i obsługa konta gracza, identyfikacja w grze oraz zabezpieczenie dostępu do profilu.

### B. Dane Rozgrywki, Profilu i Znajomych
- **Przetwarzane dane:** pseudonim gracza (nickname), statystyki wyników, osiągnięcia, historia rozegranych gier, lista znajomych.
- **Przechowywanie:** dane te są przechowywane w bazie danych **Firebase Realtime Database**.
- **Cel:** zapewnienie funkcjonalności rozgrywki sieciowej w czasie rzeczywistym, generowanie tablicy wyników oraz umożliwienie interakcji między znajomymi.

### C. Wiadomości Czatu i Moderacja Treści (UGC)
- **Przetwarzane dane:** treść wiadomości wysyłanych na czacie w trakcie rozgrywki, znaczniki czasu (timestamp), identyfikatory nadawców.
- **System zgłoszeń (`moderationReports`):** w celu zapewnienia bezpiecznego środowiska, Aplikacja umożliwia zgłaszanie nieodpowiednich zachowań lub treści. Zgłoszenia zawierają identyfikator osoby zgłaszającej, identyfikator zgłaszanego użytkownika oraz treść/powód zgłoszenia.
- **Cel:** realizacja usługi czatu sieciowego oraz ochrona graczy przed mową nienawiści, spamem i treściami niedozwolonymi (moderacja bezpieczeństwa).

### D. Dane Techniczne i Sieciowe
- **Przetwarzane dane:** podstawowe parametry techniczne (adres IP, tokeny sesji/urządzenia, stan połączenia sieciowego).
- **Uprawnienia aplikacji:** Aplikacja wymaga podstawowego uprawnienia dostępu do sieci Internet (`android.permission.INTERNET`). Wszystkie inne uprawnienia (np. powiadomienia) wykorzystywane są wyłącznie w standardowym zakresie silnika Flutter i pakietów Firebase.
- **Brak śledzenia i reklam:** Aplikacja **nie używa** reklamowych identyfikatorów śledzących (np. GAID / Google Advertising ID) ani zewnętrznych sieci reklamowych (brak Google AdMob).

---

## 3. Zewnętrzni Dostawcy Usług (SDK)

W celu zapewnienia niezawodności i infrastruktury sieciowej Aplikacja korzysta z usług Google Firebase dostarczanych przez **Google Ireland Limited / Google LLC**:

1. **Firebase Authentication** – obsługa bezpiecznego logowania przez Google. [Polityka prywatności Google Firebase](https://firebase.google.com/support/privacy)
2. **Firebase Realtime Database** – przechowywanie i synchronizacja danych gry, czatu i moderacji w czasie rzeczywistym.

Dostawca infrastruktury działa jako podmiot przetwarzający dane na zlecenie Administratora i stosuje odpowiednie środki bezpieczeństwa technicznego i organizacyjnego.

---

## 4. Podstawy Prawne Przetwarzania Danych (RODO / GDPR)

Dane osobowe są przetwarzane zgodnie z rozporządzeniem RODO na następujących podstawach:
- **Art. 6 ust. 1 lit. b RODO** – przetwarzanie jest niezbędne do wykonania umowy o świadczenie usługi gry mobilnej i obsługi konta użytkownika.
- **Art. 6 ust. 1 lit. f RODO** – prawnie uzasadniony interes Administratora polegający na zapewnieniu bezpieczeństwa graczy, zapobieganiu oszustwom i moderacji treści na czacie.

---

## 5. Bezpieczeństwo i Przechowywanie Danych

- **Bezpieczeństwo:** Transmisja danych pomiędzy Aplikacją a serwerami Firebase jest szyfrowana przy użyciu protokołu SSL/TLS (HTTPS).
- **Okres przechowywania:** Dane związane z kontem i rozgrywką są przechowywane przez okres aktywności konta użytkownika lub do momentu zgłoszenia żądania usunięcia konta.

---

## 6. Procedura Usuwania Konta i Danych (Wymóg Google Play)

Każdy użytkownik ma prawo w dowolnym momencie zażądać usunięcia swojego konta oraz wszystkich powiązanych danych osobowych i profilowych.

### Jak złożyć żądanie usunięcia danych?

1. **Z poziomu Aplikacji:**
   Przejdź do zakładki *Ustawienia / Profil gracza* w Aplikacji i wybierz opcję **„Usuń konto”**.
2. **Droga e-mailowa (Dedykowana ścieżka kontaktowa):**
   Wyślij wiadomość e-mail na adres: **[ambroziak.hub@gmail.com](mailto:ambroziak.hub@gmail.com)**
   - **Tytuł wiadomości:** `Żądanie usunięcia konta - Państwa Miasta`
   - **Treść wiadomości:** Podaj adres e-mail powiązany z kontem Google używanym w grze lub unikalny identyfikator gracza.

### Co zostanie usunięte?
Po zweryfikowaniu zgłoszenia trwale i nieodwracalnie usuwamy:
- Konto w usłudze Firebase Authentication.
- Profil gracza, pseudonim oraz zdjęcie profilowe.
- Statystyki gier, punkty i wpisy na tablicy wyników w Firebase Realtime Database.
- Historię znajomych i czatu.

*Czas realizacji zgłoszenia e-mailowego wynosi do 14 dni.*

---

## 7. Prawa Użytkownika

Zgodnie z przepisami RODO przysługują Ci następujące prawa:
- Prawo dostępu do swoich danych oraz otrzymania ich kopii.
- Prawo do sprostowania (poprawiania) danych.
- Prawo do usunięcia danych („prawo do bycia zapomnianym”).
- Prawo do ograniczenia przetwarzania lub wniesienia sprzeciwu.
- Prawo do wniesienia skargi do organu nadzorczego – **Prezesa Urzędu Ochrony Danych Osobowych (PUODO)** w Polsce.

---

## 8. Prywatność Dzieci

Aplikacja ma charakter ogólnodostępnej gry towarzyskiej. Nie zbieramy świadomie danych osobowych od dzieci poniżej 13 roku życia bez zgody rodziców lub opiekunów prawnych. Jeśli rodzic lub opiekun stwierdzi, że dziecko przekazało nam dane osobowe, prosimy o kontakt pod adresem [ambroziak.hub@gmail.com](mailto:ambroziak.hub@gmail.com) w celu ich niezwłocznego usunięcia.

---

## 9. Zmiany w Polityce Prywatności

Zastrzegamy sobie prawo do aktualizacji niniejszej Polityki Prywatności w przypadku zmian w funkcjonowaniu Aplikacji, wymogów prawnych lub zasad sklepu Google Play. Aktualna wersja dokumentu będzie zawsze publikowana pod adresemURL polityki prywatności.

---

## 10. Kontakt

W przypadku jakichkolwiek pytań, wątpliwości lub zgłoszeń dotyczących prywatności, prosimy o kontakt:

**Hubert Ambroziak**  
E-mail: [ambroziak.hub@gmail.com](mailto:ambroziak.hub@gmail.com)  
Identyfikator aplikacji: `com.panstwamiastahuba.game`
