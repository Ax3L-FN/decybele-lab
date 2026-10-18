# Decybele LAB

Statyczna aplikacja do ćwiczenia przeliczeń dB, dBW, dBm, dBV, dBµV, stosunków, kaskad i sumowania mocy. Bez zależności, bez builda i bez serwera.

## Lokalnie

Otwórz `index.html` w dowolnej nowoczesnej przeglądarce.

## GitHub Pages

1. Utwórz publiczne repozytorium na GitHubie, np. `decybele-lab`.
2. Prześlij `index.html` i `README.md` do głównego katalogu repozytorium (lub użyj `git add . && git commit -m "Decybele LAB" && git push`).
3. Otwórz **Settings → Pages → Build and deployment**, ustaw **Deploy from a branch**, wybierz `main` oraz `/(root)` i zapisz.
4. Otwórz adres `https://TWOJ-LOGIN.github.io/decybele-lab/` (po wdrożeniu).

Weryfikacja: karta Trening losuje zadania, Kalkulator przelicza obie strony, Ściąga zawiera wzory. Statystyki prób przechowuje przeglądarka w localStorage.

Podstawowe wzory: `dBW = 10log10(P[W])`, `dBm = 10log10(P[mW])`, `dBV = 20log10(U[V])`.
