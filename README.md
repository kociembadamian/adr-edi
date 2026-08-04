<p align="center">
  <a href="https://app.kocie.mba" target="_blank">
    <img src="https://github.com/user-attachments/assets/b1072984-633a-470d-b950-b8cadb91df37" width="800" height="450" alt="ADR apka - app.kocie.mba">
  </a>
</p>

<p align="center">
  <b>Uruchom aplikację: <a href="https://edi.kocie.mba">edi.kocie.mba</a></b><br>
  <sub><i>Aplikacja automatycznie rozpozna Twoje urządzenie (iOS, Android, Windows) i dopasuje odpowiednią wersję lub opcję instalacji PWA.</i></sub>
</p>
# repo adr-edi
EDI ADR - cyfrowa automatyzacja dokumentów przewozowych. Niezależne repozytorium dla ceniących prywatność i urządzeń bez Google Play Services. Udostępnione pliki .apk to te same, bezpieczne i podpisane cyfrowo wersje, co w Google Play. Pobierz je bezpośrednio lub dodaj do Obtainium, by mieć auto-aktualizacje.

# Informacje o aplikacji:
[ADR EDI](https://edi.kocie.mba) to profesjonalne oprogramowanie klasy utility, dedykowane do cyfrowej automatyzacji procesów wystawiania dokumentacji przewozowej oraz zarządzania danymi zgodnie z wymogami Umowy ADR. Aplikacja przekształca złożone restrykcje działu 5.4 ADR w intuicyjny proces workflow, eliminując ryzyko błędów formalnych oraz dotkliwych sankcji administracyjnych wynikających z nieprawidłowego opisu towarów niebezpiecznych. 

Logika aplikacji została oparta na cyfrowej normalizacji przepisów Umowy ADR oraz Ustawie o przewozie towarów niebezpiecznych.

# Najważniejsze funkcje:
- Inteligentny generator dokumentów przewozowych
    System automatyzuje tworzenie prawidłowej nazwy przewozowej poprzez integrację z bazą danych API. Aplikacja samodzielnie implementuje logikę wymaganych dopisków i modyfikatorów, w tym: oznaczenie odpadów (5.4.1.1.3), obsługę próżnych nieoczyszczonych opakowań i cystern (5.4.1.1.6), a także automatyczne wykrywanie towarów zagrażających środowisku, stabilizowanych czy przewożonych w podwyższonej temperaturze.

- Moduł raportowania rocznego i detekcja towarów niebezpiecznych dużego ryzyka (HCDG)
    Zaawansowane narzędzie analityczne agregujące dane przewozowe w cyklu rocznym. System automatycznie klasyfikuje towary według klas i jednostek miary (masa/objętość) oraz implementuje algorytm identyfikacji towarów dużego ryzyka, zgodnie z tabelą 1.10.3.1.2 ADR. Moduł rozpoznaje progi ilościowe w zależności od sposobu przewozu (sztuki przesyłki, luzem, cysterna), dostarczając gotowe dane do sprawozdania rocznego.

- Zintegrowany kalkulator 1.1.3.6
    Automatyczne wyliczanie punktów ADR dla każdej pozycji dokumentu. System mapuje towary do kategorii transportowych (0-4) i stosuje odpowiednie mnożniki, weryfikując dopuszczalność przewozu na wyłączeniu ilościowym w czasie rzeczywistym.

- Relacyjna baza odbiorców i nadawców
    Moduł zarządzania kontrahentami pozwalający na błyskawiczną personalizację dokumentów. Baza danych pozwala na przechowywanie pełnych danych teleadresowych, skracając proces wystawiania dokumentu do minimum.

- Architektura PWA i lokalne bezpieczeństwo danych
    Aplikacja wykorzystuje standardy Progressive Web App, co umożliwia pracę w trybie offline oraz błyskawiczny dostęp do archiwalnych dokumentów bez konieczności stałego połączenia z siecią. Wszystkie dane wrażliwe (klienci, historia przewozów) przechowywane są bezpiecznie w pamięci lokalnej urządzenia użytkownika.

# Dla kogo jest ta aplikacja?
- Doradcy ds. bezpieczeństwa przewozu towarów niebezpiecznych (DGSA)
- Nadawcy i załadowcy towarów niebezpiecznych
- Firmy transportowe i przewoźnicy
- Spedytorzy i specjaliści ds. logistyki
- Kierowcy zawodowi

# Jak zainstalować i aktualizować?
Masz do wyboru dwie ścieżki instalacji:

# Opcja 1: Obtainium (zalecane ze względu na automatyczne aktualizacje)
Jeśli chcesz, aby aplikacja aktualizowała się sama w tle, bez konieczności używania Google Play:
1. Zainstaluj darmową aplikację OBTAINIUM.
2. Wklej w niej link do tego repozytorium: https://github.com/kociembadamian/adr-edi/ 
3. Kliknij "Add" (Dodaj). Od teraz Twoje urządzenie automatycznie wykryje nowe wersje i zaproponuje aktualizację.

# Opcja 2: bezpośrednie pobranie APK
1. Przejdź do zakładki [Releases](../../releases/latest) po prawej stronie.
2. Rozwiń sekcję ASSETS.
3. Pobierz plik `app-release-signed.apk` i zainstaluj go na urządzeniu.

# Informacja prawna / zrzeczenie się odpowiedzialności
Aplikacja nie jest oficjalnym produktem rządowym i nie reprezentuje żadnego organu państwowego. Dane i obliczenia w niej zawarte mają charakter pomocniczy i informacyjny. Nie zwalniają one użytkownika z obowiązku znajomości przepisów Umowy ADR oraz konsultacji z certyfikowanym doradcą ds. bezpieczeństwa. Twórcy aplikacji nie ponoszą odpowiedzialności za błędy interpretacyjne, szkody lub kary wynikające z użytkowania oprogramowania. Oficjalne przepisy ADR dostępne są na stronie UNECE.

# Przydatne linki
- Regulamin aplikacji: [pl.kocie.mba/regulamin.html](https://pl.kocie.mba/regulamin.html)
- Polityka prywatności (RODO): [pl.kocie.mba/rodo.html](https://pl.kocie.mba/rodo.html)
- Polityka Cookies: [pl.kocie.mba/cookies.html](https://pl.kocie.mba/cookies.html)
  
- Wersja Google Play: [Google Play](https://play.google.com/store/apps/details?id=mba.kocie.edi.twa)

# ©️ Licencja i prawa autorskie

Wszelkie prawa zastrzeżone (All Rights Reserved). Aplikacja udostępniana jest w tym repozytorium wyłącznie w celu pobrania i osobistej instalacji. Kopiowanie, modyfikowanie, dekompilacja (inżynieria wsteczna) oraz redystrybucja aplikacji w zmodyfikowanej formie lub pod inną nazwą są surowo zabronione.
