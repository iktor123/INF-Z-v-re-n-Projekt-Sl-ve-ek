# Slávkova stránka

Osobní web s prezentacemi, herním vybavením a zájmy o zvířata.

## Struktura webu

```
slavkova-stranka/
├── index.html                          ← Hlavní stránka
├── style.css                           ← Styly pro celý web
├── prezentace/
│   ├── index.html                      ← Přehled prezentací
│   ├── veledila.html                   ← Veledíla
│   └── css-style.html                  ← CSS style
├── gaming/
│   ├── index.html                      ← Přehled gamingu
│   ├── pocitac/
│   │   ├── index.html                  ← Přehled počítače
│   │   ├── prislusenstvi.html          ← Klávesnice, sluchátka, myš
│   │   ├── komponenty.html             ← Case a hardware
│   │   └── hry.html                    ← R6, Valorant
│   └── mobil/
│       ├── index.html                  ← Přehled mobilu
│       ├── model.html                  ← Redmi Note 13
│       └── hry.html                    ← Geometry Dash, Brawl Stars
└── zajmy/
    ├── index.html                      ← Přehled zájmů
    ├── kodex/
    │   ├── index.html                  ← Kodex zvířecího zpěvu
    │   ├── lachtani.html               ← Lachtání zpívání
    │   └── krtci-orchestr.html         ← Krtčí orchestr
    └── hledani-krtku/
        ├── index.html                  ← Přehled lokací
        ├── lesy.html                   ← Lesy
        ├── pole.html                   ← Pole
        └── zahrady.html                ← Zahrady
```

---

## Jak dát web na GitHub (krok za krokem)

### 1. Založ si účet na GitHubu
Jdi na [github.com](https://github.com) a zaregistruj se (je to zdarma).

### 2. Vytvoř nový repozitář
1. Klikni na zelené tlačítko **"New"** (nebo **"+"** vpravo nahoře → New repository)
2. **Repository name:** napiš `slavkova-stranka`
3. Zaškrtni **"Public"** (aby byl web veřejně přístupný)
4. Klikni **"Create repository"**

### 3. Nahraj soubory
Na stránce repozitáře klikni na **"uploading an existing file"** (nebo **Add file → Upload files**).

Přetáhni **celou složku** `slavkova-stranka` (nebo vyber všechny soubory i podsložky).

> ⚠️ Pozor: GitHub neumí nahrát prázdné složky, ale soubory v podsložkách nahraje správně.

Dole klikni na **"Commit changes"**.

### 4. Zapni GitHub Pages (zveřejnění webu)
1. V repozitáři klikni na **Settings** (nahoře)
2. V levém menu najdi **Pages**
3. Pod **"Source"** vyber **"Deploy from a branch"**
4. Branch: **main**, složka: **/ (root)**
5. Klikni **Save**

Po chvíli (1–2 minuty) bude web dostupný na adrese:
```
https://TVOJE-JMENO.github.io/slavkova-stranka/
```

### 5. Hotovo! 🎉
Web je online. Kdykoli změníš soubory a nahraješ je znovu, GitHub Pages se automaticky aktualizuje.
