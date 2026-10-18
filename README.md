# APBD - Ćwiczenie 1: Git i GitHub

Prosty program konsolowy w C# stworzony w ramach ćwiczeń z przedmiotu APBD na temat Gita i GitHuba.

Program wywołuje metodę `Greeting.GetMessage()`, oblicza sumę elementów tablicy `{ 2, 4, 6 }` metodą `StatisticsHelper.CalculateSum` i wypisuje oba wyniki na konsolę.

## Uruchomienie

Wymagania: zainstalowany [.NET SDK 8.0](https://dotnet.microsoft.com/download/dotnet/8.0) oraz [Git](https://git-scm.com/downloads).

W katalogu projektu wykonaj:

```bash
dotnet run
```

Oczekiwany wynik:

```
Hello, APBD!
Suma: 12
```

## Budowa

```bash
dotnet build
```

## Historia

Repozytorium zawiera scenariusze ćwiczeniowe: fast-forward merge, three-way merge bez konfliktu oraz scalenie z konfliktem i jego ręcznym rozwiązaniem.
