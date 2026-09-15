# Instrukcja Git – wypychanie zmian do repozytorium

## 1. Sprawdzenie statusu

W terminalu w folderze projektu wpisz:

```bash
git status
```

To pokaże, jakie pliki zostały zmienione, dodane lub usunięte.

## 2. Dodanie zmian do stage

Jeśli chcesz dodać wszystkie zmiany:

```bash
git add .
```

Jeśli chcesz dodać tylko wybrany plik:

```bash
git add nazwa_pliku
```

## 3. Utworzenie commita

```bash
git commit -m "opis zmian"
```

Przykład:

```bash
git commit -m "Dodano sekcję z cytatami"
```

## 4. Wysłanie zmian na GitHub

Jeśli to pierwszy push dla tego brancha:

```bash
git push -u origin main
```

Jeśli repozytorium już ma ustawiony upstream:

```bash
git push
```

## 5. Pełny standardowy workflow

```bash
git status
git add .
git commit -m "opis zmian"
git push
```

## 6. Jeśli branch jest inny niż main

Sprawdź nazwę brancha:

```bash
git branch
```

Wypchnij zmiany na aktualny branch:

```bash
git push -u origin nazwa-brancha
```

## 7. Jeśli pojawia się błąd z uprawnieniami

Najczęściej trzeba zalogować się do GitHub w przeglądarce lub użyć tokena PAT.

## 8. Najczęstsze polecenia

```bash
git status
git add .
git commit -m "Opis zmian"
git push
```

## 9. Przykład z tego projektu

```bash
git add .
git commit -m "Aktualizacja strony i treści"
git push
```

## 10. Ważne

- `git add .` dodaje wszystkie zmiany,
- `git commit` zapisuje zmianę lokalnie,
- `git push` wysyła ją na GitHub.

Jeśli chcesz, mogę też przygotować wersję tej instrukcji w języku bardziej „dla początkujących” albo dodać gotowe polecenia dla tego konkretnego repozytorium.
