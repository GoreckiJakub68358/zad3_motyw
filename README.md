# CV – Jakub Górecki (Zadanie 3)

> **Zadanie 3:** Drugi motyw kolorystyczny (CSS)  
> **Przedmiot:** Projektowanie multimedialnych stron internetowych  
> **Uczelnia:** Akademia Finansów i Biznesu Vistula

## 🔗 Linki

- 📁 Repozytorium: [https://github.com/GoreckiJakub68358/zad3_motyw](https://github.com/GoreckiJakub68358/zad3_motyw)
- 🌐 GitHub Pages: [https://goreckijakub68358.github.io/zad3_motyw](https://goreckijakub68358.github.io/zad3_motyw)

## 📋 Opis projektu

Głównym celem tego zadania jest pokazanie, że ta sama struktura HTML 
może prezentować się zupełnie inaczej w zależności od podłączonego 
arkusza stylów CSS. 

Projekt zawiera dwa niezależne motywy: **Czerwony** (domyślny) oraz **Zielony**.

## ✅ Wymagania techniczne (Zadanie 3)

- [x] **Niezmienność HTML:** Plik `index.html` posiada identyczną strukturę i treść jak w poprzednim zadaniu.
- [x] **Dwa arkusze stylów:** W katalogu znajdują się pliki `red.css` oraz `green.css`.
- [x] **Domyślny motyw:** Plik HTML domyślnie podłącza czerwony motyw (`red.css`).
- [x] **Wyraźne różnice wizualne:** Motywy różnią się nie tylko kolorystyką, ale także typografią, kształtem elementów i efektami (cienie, obramowania).

## 📂 Struktura katalogu `zad3_motyw`

- `index.html` – struktura CV (domyślnie ładuje `red.css`).
- `red.css` – motyw czerwony.
- `green.css` – motyw zielony.
- `moje-zdjecie.jpg` – plik graficzny profilowy.

## 🎨 Porównanie motywów

| Cecha | Motyw Czerwony (`red.css`) | Motyw Zielony (`green.css`) |
| :--- | :--- | :--- |
| **Kolor główny** | `#c0392b` (Crimson Red) | `#2e8b57` (SeaGreen) |
| **Typografia** | Segoe UI (Bezszeryfowa) | Georgia (Szeryfowa) |
| **Tło strony** | `#faebeb` (Jasnoczerwone) | `#f0f4f0` (Jasnozielone) |
| **Obramowanie sekcji** | Lewy akcent (`border-left`) | Pełna ramka (`border: 3px solid`) |
| **Efekt najechania (`:hover`)** | Skalowanie (`scale 1.02`) + tło | Podniesienie (`translateY`) + tło |
| **Interakcja kontenera** | Delikatny cień w `.container` | Rozświetlenie (`box-shadow` neonowy) |
| **Zdjęcie profilowe** | Okrągłe (`border-radius: 50%`) | Zaokrąglony kwadrat (`border-radius: 25%`) |
| **Przyciski kontaktowe** | Zaokrąglone (20px) | Prostokątne z lekkim łukiem (10px) |

## 📝 Changelog (Zadanie 3)

### v2.0 – Setup
- Utworzenie katalogu `zad3_motyw`.
- Przeniesienie struktury HTML z Zadania 2.

### v2.1 – Red Theme (Default)
- Implementacja `red.css` z czerwonym kolorem przewodnim.
- Zmiana czcionki na szeryfową i usunięcie zaokrągleń dla kontrastu.

### v2.2 – Green Theme
- Implementacja `green.css` na bazie stylów z poprzedniego zadania.
- Dodanie cieni i zaokrągleń dla odróżnienia od motywu czerwonego.

### v2.3 – Final Check
- Weryfikacja domyślnego podłączenia `red.css`.
- Testowanie poprawności wyświetlania obu motywów.
