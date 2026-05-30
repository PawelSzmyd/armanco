# ARMANCO — Astro

Strona ARMANCO Sp. z o.o. zbudowana w Astro. Czysta, statyczna, bez żadnych zewnętrznych zależności poza Google Fonts i Google Maps.

## Lokalne uruchomienie

```bash
npm install
npm run dev
```

## Build

```bash
npm run build
```

## Deploy na Vercel

1. Wgraj ten folder na GitHub (nowe repozytorium)
2. W Vercel → **Add New Project** → wybierz repozytorium
3. Framework: **Astro** (wykryje automatycznie)
4. Deploy

## Struktura

```
src/
├── layouts/
│   └── Layout.astro        # HTML shell, meta tagi, fonty
├── pages/
│   └── index.astro         # Strona główna
└── components/
    ├── Header.astro
    ├── HeroSection.astro
    ├── ServicesSection.astro
    ├── ContactSection.astro
    └── Footer.astro
public/
└── favicon.svg
```
