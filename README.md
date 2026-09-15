# Rozmowa z Bogiem

Prosta strona na GitHub Pages.

## Jak dodać nowy wpis?

1. Wejdź w plik `posts.json`
2. Na samej górze listy (zaraz po `[`) dodaj nowy wpis w takiej formie:

```json
{
  "date": "16 września 2026",
  "title": "Tytuł (opcjonalny)",
  "content": "Tutaj treść Twojego wpisu.\nMożesz pisać w wielu liniach."
},
```

3. Zapisz plik (Commit changes)
4. Gotowe – strona się odświeży z nowym wpisem na górze.

## Jak wrzucić stronę na GitHub Pages?

1. Załóż nowe repozytorium na GitHubie (np. `rozmowa-z-bogiem`)
2. Wgraj wszystkie pliki z tego folderu
3. Wejdź w Settings → Pages
4. Wybierz branch `main` i folder `/ (root)`
5. Zapisz

Po kilku minutach strona będzie dostępna pod adresem:
`https://TWOJA-NAZWA.github.io/rozmowa-z-bogiem/`
