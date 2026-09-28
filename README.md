# Console Playnite Experience — instrukcja
Pobierz: https://drive.google.com/file/d/17CDAewDzO92k7ZRdmplQj3Qyi3ENX2w5/view?usp=sharing

## 1. Instalacja

Console Playnite Experience instaluje się domyślnie do:

```text
C:\PlayniteConsoleExperience
```

### Instalacja

1. Uruchom `Install-ConsolePlaynite.cmd`.
2. Zaakceptuj uprawnienia administratora.
3. Poczekaj na zakończenie instalacji.
4. Na pulpicie zostaną utworzone skróty do Playnite Desktop i Playnite Fullscreen.

> RTSS (RivaTuner Statistics Server) nie jest dołączony do paczki i należy zainstalować go osobno.

---

## 2. Pierwsze uruchomienie

Po instalacji uruchom:

```text
Playnite Desktop
```

Desktop Mode służy przede wszystkim do konfiguracji programu, bibliotek, dodatków i gier.

Po zakończeniu konfiguracji możesz korzystać z:

```text
Playnite Fullscreen
```

Fullscreen Mode jest przeznaczony do obsługi kontrolerem i grania.

---

## 3. Biblioteki gier

Zestaw zawiera integracje dla:

- Steam
- Epic Games Store
- GOG
- EA app
- Ubisoft Connect
- Xbox / Microsoft
- Amazon Games

Nie musisz konfigurować wszystkich bibliotek. Dodaj tylko te platformy, z których korzystasz.

### Konfiguracja biblioteki

W Playnite przejdź do:

```text
Menu → Add-ons → Browse / Installed → Libraries
```

Skonfiguruj wybraną usługę i zaloguj się na własne konto.

Po zakończeniu wykonaj:

```text
Menu → Update Game Library
```

Powtórz tę czynność dla wszystkich używanych platform.

> Każdy użytkownik musi użyć własnych kont. Paczka nie zawiera danych logowania ani prywatnej biblioteki gier.

---

## 4. Motywy

### Desktop Mode — Daze

Głównym motywem Desktop Mode jest:

```text
Daze
```

Wybór motywu:

```text
Settings → Appearance → General → Theme → Daze
```

### Fullscreen Mode — Toggle

Głównym motywem konsolowym jest:

```text
Toggle
```

Wybór motywu:

```text
Settings → Visuals → Fullscreen Theme → Toggle
```

Toggle jest przeznaczony przede wszystkim do obsługi kontrolerem.

---

## 5. Zainstalowane dodatki

### Extra Metadata Loader

Dostarcza dodatkowe materiały i metadane gier, między innymi logotypy i filmy.

### Extra Metadata Fullscreen Mode Helper

Umożliwia wykorzystanie dodatkowych metadanych w Fullscreen Mode.

### ThemeExtras

Dostarcza dodatkowe funkcje wykorzystywane przez motywy.

### Theme Options

Dodaje dodatkowe opcje konfiguracji obsługujących go motywów.

### DuplicateHider

Pomaga ukrywać powtarzające się gry po połączeniu wielu bibliotek.

### GameActivity

Śledzi aktywność związaną z grami i może współpracować z innymi dodatkami.

### HowLongToBeat

Dodaje informacje o przewidywanym czasie ukończenia gry, między innymi:

- Main Story
- Main + Extra
- Completionist
- Solo
- Co-op
- VS

### SuccessStory

Obsługuje osiągnięcia i trofea.

### SuccessStory Fullscreen Helper

Integruje informacje z SuccessStory z Fullscreen Mode.

### Playnite Achievements

Dodatkowa obsługa osiągnięć w Playnite.

### Ludusavi

Służy do wykonywania kopii zapasowych zapisów gier.

### GG.deals

Dodaje informacje związane z ofertami i cenami gier.

### Playnite Overlay

Zapewnia funkcje nakładki podczas grania.

### Now Playing

Wyświetla informacje dotyczące aktualnie uruchomionej gry.

### Mo Data

Dodatek pomocniczy wykorzystywany przez inne rozszerzenia.

### Tryb FPS

Własny dodatek projektu służący do wyboru limitu FPS i współpracy z RTSS.

---

## 6. Tryb FPS

Tryb FPS pozwala ustawić limit:

```text
30 FPS
40 FPS
60 FPS
120 FPS
OFF
```

W Fullscreen wybierz:

```text
Gra → Tryb FPS
```

### Sterowanie

```text
↑ / ↓ → wybór trybu
A     → zatwierdzenie
B     → anulowanie
```

### Działanie

Tryb FPS komunikuje się z RTSS za pomocą RTSSBridge:

```text
Playnite
↓
Tryb FPS
↓
RTSSBridge
↓
RTSS
↓
profil gry
```

Przykładowa konfiguracja:

```text
Cyberpunk2077.exe → 120 FPS
ForzaHorizon6.exe → 60 FPS
SilentHill.exe    → 40 FPS
```

Limit jest przypisywany do profilu konkretnej gry.

---

## 7. RTSS

Do działania Tryb FPS potrzebny jest:

```text
RivaTuner Statistics Server (RTSS)
```

RTSS należy zainstalować osobno.

Zalecana lokalizacja:

```text
C:\Program Files (x86)\RivaTuner Statistics Server
```

Projekt zawiera `RTSSBridge.exe`, który odpowiada za komunikację między Playnite i RTSS.

Instalator tworzy zadanie:

```text
TrybFPS RTSS Bridge
```

z wysokimi uprawnieniami systemowymi, aby bridge mógł prawidłowo komunikować się z RTSS.

---

## 8. Ludusavi — kopie zapisów

Ludusavi służy do wykonywania kopii zapasowych save'ów.

W zestawie przewidziana jest obsługa backupu po zakończeniu gry.

Po instalacji sprawdź lokalizację kopii zapasowych i ustaw ją zgodnie z własnymi potrzebami.

---

## 9. Osiągnięcia

Za osiągnięcia odpowiadają:

- SuccessStory
- Playnite Achievements
- SuccessStory Fullscreen Helper

W zależności od platformy może być wymagana dodatkowa autoryzacja.

Po poprawnej konfiguracji informacje o osiągnięciach są dostępne w szczegółach gry.

---

## 10. HowLongToBeat

HowLongToBeat może wyświetlać przewidywany czas ukończenia gry:

```text
Main Story
Main + Extra
Completionist
Solo
Co-op
VS
```

Informacje są dostępne w szczegółach gry, jeżeli dane są dostępne dla danego tytułu.

---

## 11. Kontroler

Fullscreen Mode jest przygotowany do obsługi kontrolerem.

Zalecany jest kontroler Xbox/XInput.

Podstawowa obsługa:

```text
A → wybór / uruchomienie
B → powrót
↑ / ↓ → poruszanie się
```

Po podłączeniu kontrolera uruchom:

```text
Playnite Fullscreen
```

---

## 12. Desktop Mode i Fullscreen Mode

### Desktop Mode

Używaj do:

- konfiguracji Playnite,
- logowania do bibliotek,
- instalowania i konfiguracji dodatków,
- aktualizacji biblioteki,
- zarządzania grami.

### Fullscreen Mode

Używaj do:

- przeglądania biblioteki,
- wybierania gier,
- uruchamiania gier,
- obsługi kontrolerem,
- korzystania z motywu Toggle,
- korzystania z Tryb FPS.

---

## 13. Zalecana kolejność konfiguracji

1. Zainstaluj Console Playnite Experience.
2. Zainstaluj RTSS.
3. Uruchom Playnite Desktop.
4. Skonfiguruj potrzebne biblioteki.
5. Zaloguj się do własnych kont.
6. Wykonaj `Update Game Library`.
7. Sprawdź okładki i metadane.
8. Sprawdź motyw Daze.
9. Uruchom Playnite Fullscreen.
10. Sprawdź motyw Toggle.
11. Podłącz kontroler.
12. Sprawdź osiągnięcia.
13. Sprawdź HowLongToBeat.
14. Sprawdź działanie Ludusavi.
15. Sprawdź Tryb FPS.
16. Uruchom grę i sprawdź limit FPS w RTSS.

---

## 14. Najważniejsze informacje

- Gry nie są częścią projektu.
- Launchery nie są częścią projektu.
- RTSS należy zainstalować osobno.
- Każdy użytkownik korzysta z własnych kont.
- Nie należy udostępniać zapisanych sesji, danych logowania ani prywatnej biblioteki Playnite.
- Po dodaniu nowych gier wykonaj `Update Game Library`.
- Nie ma potrzeby konfigurowania bibliotek, z których nie korzystasz.

---

## 15. Efekt końcowy

Po konfiguracji komputer działa według schematu:

```text
Windows 11
↓
Playnite
↓
Toggle Fullscreen
↓
Jedna biblioteka gier
↓
Steam / Epic / GOG / EA / Ubisoft / Xbox / Amazon
↓
Kontroler
↓
Gra
↓
Tryb FPS → RTSS
```

**Console Playnite Experience — jeden konsolowy interfejs dla gier z wielu platform.**
