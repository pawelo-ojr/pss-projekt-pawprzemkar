# pss-projekt-pawprzemkar
Projekt zespołowy z przedmiotu **Projektowanie serwisów sieciowych** (Politechnika Bydgoska, 2026/27):
własne REST API, które zespół projektuje, testuje i prezentuje.

## Zespół

| Rola | Login GitHub | Karta |
|---|---|---|
| A — opiekun repozytorium | LOGIN_A | [zespol/pawelo-ojr.md](zespol/pawelo-ojr.md) |
| B | LOGIN_B | [zespol/przemyslawmc.md](zespol/przemyslawmc.md) |
| C | LOGIN_C | [zespol/Karol-0-4](zespol/Karol-0-4.md) |

## Pomysły na temat projektu (wybór w LAB 08)

- system monitorowania wilgotnosci

## Jak pracujemy

- Gałąź `main` zmieniamy tylko przez Pull Request zaakceptowany przez inną osobę.
- Każda zmiana powstaje na krótkiej gałęzi, np. `docs/ak-karta` albo `postman/bn-lab02`.
- Opisy commitów piszemy w formie `typ: opis`, np. `docs: dodaj kartę członka zespołu`.
- Hasła, tokeny i klucze nigdy nie trafiają do repozytorium (patrz `.gitignore` i `postman/README.md`).

## Struktura repozytorium

| Ścieżka | Zawartość |
|---|---|
| `zespol/` | karty członków zespołu |
| `postman/` | kolekcje i środowiska Postmana (eksport JSON v2.1) |
| `.github/pull_request_template.md` | szablon opisu Pull Requesta |
