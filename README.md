# Barberlounge – sajt

Kod sajta Barberlounge, preuzet iz `public_html` foldera sa hostinga.

## Struktura

```
index.html     ulazna stranica
favicon.png    ikonica sajta
assets/        kompajlirani JS i CSS + slike koje kod učitava
img/           slike premium paketa (premium1–3.jpg)
```

> **Napomena:** ovo je produkcijski *build* (Vite + React). JS i CSS su već kompajlirani i minificirani.
> Izvorni projekat (`src/`, `package.json`, `vite.config.*`) nije u ovom repou.

## Veličine fajlova

| Fajl | Dimenzije | Veličina |
|---|---|---|
| `assets/pozadina-TlgOgpKF.png` | 2094 × 1054 | 2,0 MB |
| `img/premium3.jpg` | 1200 × 1200 | 747 KB |
| `img/premium1.jpg` | 1200 × 1200 | 706 KB |
| `img/premium2.jpg` | 1200 × 1200 | 589 KB |
| `favicon.png` | 1024 × 1024 | 207 KB |
| `assets/index-I7SeLNbT.js` | – | 205 KB |
| `assets/IMG_2283-DONP48dy.PNG` | 644 × 388 | 137 KB |
| `assets/index-DMt5vkvI.css` | – | 24 KB |
| `index.html` | – | 1 KB |

Ukupno oko 4,5 MB, od čega su oko 95 % slike.

## Pokretanje i postavljanje

- Putanje u `index.html` su apsolutne (`/assets/...`), pa otvaranje fajla duplim klikom daje praznu stranicu.
  Za lokalno testiranje pokreni server iz ovog foldera, npr. `npx serve .`
- Na hosting ide sadržaj repoa (bez `README.md` i `.gitattributes`) direktno u `public_html`.
