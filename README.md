# Mráz Bros – Tréner

Jednosúborová webová hra (trénerský manažér). Celá hra je v súbore `index.html`, bez závislostí a bez build kroku.

## Nasadenie na GitHub Pages

1. Nahrajte obsah tohto balíka do koreňa repozitára `javorkahub/trener` (vetva `main`), vrátane skrytého priečinka `.github`.
2. V repozitári otvorte Settings > Pages a v časti Build and deployment nastavte Source na **GitHub Actions**.
3. Po každom pushi do `main` workflow `Deploy na GitHub Pages` hru nasadí automaticky (spustiť ho možno aj ručne v záložke Actions).
4. Hra bude dostupná na adrese `https://javorkahub.github.io/trener/`.

## Poznámky

- Postup hry sa ukladá do úložiska prehliadača (localStorage) len pri akcii Ukončiť > Uložiť. Údaje sú viazané na konkrétny prehliadač a zariadenie.
- Údaje o hráčoch a tímoch sú čiastočne fiktívne; fotky štadiónov sú vložené priamo v `index.html`. Pred zverejnením skontrolujte, či máte právo fotky použiť.
