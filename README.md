# Card-product

## Opis projektu

**Card-product** to prosta aplikacja webowa prezentująca kartę produktową butów z wieloma wariantami kolorystycznymi i rozmiarowymi. Projekt powstał w celach naukowych i testowych, aby przećwiczyć budowę interaktywnego komponentu produktowego z wykorzystaniem nowoczesnych technologii frontendowych.

**Live website:** [https://jakubba.github.io/Card-product/](https://jakubba.github.io/Card-product/)

Aplikacja umożliwia:

- Przeglądanie różnych wariantów produktu (kolory, rozmiary, szerokości, toe+heel)
- Dynamiczną zmianę zdjęć produktu w zależności od wybranego wariantu
- Wybór rozmiaru, szerokości i typu toe+heel
- Podgląd dodatkowych zdjęć produktu (galeria z funkcją "pokaż więcej")

## Wykorzystane technologie

- **HTML5** – struktura aplikacji
- **Tailwind CSS** – stylowanie i szybkie prototypowanie UI
- **Alpine.js** – lekki framework JavaScript do obsługi prostych interakcji (testowo, do nauki)
- **Vanilla JavaScript** – obsługa logiki zmiany wariantów, wyboru opcji, modali itp.
- **Fancybox** – galeria zdjęć produktu (lightbox)
- **Font Awesome** – ikony (np. serduszko do wishlisty)
- **JSON** – dane o produktach i wariantach (`product.json`)

## Struktura projektu

```
Card-product/
├── assets/
│   ├── icons/
│   ├── images-colors/
│   └── images-product/
├── index.html
├── product.json
└── README.md
```

- **index.html** – główny plik aplikacji, cała logika i UI
- **product.json** – dane o wszystkich wariantach produktu (kolory, rozmiary, zdjęcia itd.)
- **assets/** – zasoby statyczne (ikony SVG, zdjęcia kolorów, zdjęcia produktów)

## Mechaniki i funkcjonalności

- **Wybór wariantu kolorystycznego** – kliknięcie w miniaturę koloru zmienia zdjęcia i dane produktu
- **Wybór rozmiaru, szerokości, toe+heel** – modal z opcjami, dynamiczne podświetlanie wybranych opcji
- **Galeria zdjęć** – możliwość powiększenia zdjęcia, pokazania dodatkowych zdjęć ("show more media")
- **Responsywność** – UI dostosowuje się do różnych rozdzielczości
- **Przykładowe akcje** – przyciski "Add to cart", "Check availability", "Wishlist" (bez backendu)

## Wnioski z testowania bibliotek

- **Tailwind CSS** – bardzo wygodny do szybkiego prototypowania i budowy responsywnego UI. Umożliwia łatwe modyfikacje wyglądu bez konieczności pisania własnych klas CSS.
- **Alpine.js** – świetny do prostych interakcji i dynamicznych elementów, szczególnie gdy nie chcemy używać dużych frameworków typu React czy Vue. W tym projekcie sprawdził się do testów, ale większość logiki napisana została w czystym JavaScript, co daje większą kontrolę.
- **Fancybox** – bardzo intuicyjna i łatwa w integracji galeria zdjęć. Pozwala szybko dodać efekt lightbox do zdjęć produktu.
- **Font Awesome** – szybki sposób na dodanie ikon, nie wymaga dodatkowej konfiguracji.
- **Vanilla JS** – daje pełną kontrolę nad logiką i pozwala lepiej zrozumieć działanie aplikacji, choć przy większych projektach warto rozważyć framework.

**Podsumowanie:**  
Wszystkie użyte biblioteki są łatwe w integracji i dobrze sprawdzają się w małych projektach lub prototypach. Tailwind i Fancybox szczególnie przyspieszają pracę nad UI. Alpine.js jest ciekawą alternatywą dla prostych interakcji, ale przy większej ilości logiki lepiej sprawdza się czysty JavaScript lub większy framework.

## Jak uruchomić projekt?

1. Sklonuj repozytorium lub pobierz pliki.
2. Otwórz plik `index.html` w przeglądarce.
3. Wszystkie dane i zasoby są ładowane lokalnie (brak backendu).

## Uwagi

- Projekt powstał w celach edukacyjnych – kod nie jest zoptymalizowany pod produkcję.
- Alpine.js został użyty testowo, większość logiki napisana jest w czystym JavaScript.
- Zdjęcia i dane produktów są przykładowe.

---

Autor: Jacob B
