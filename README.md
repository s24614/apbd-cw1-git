# APBD - Ćwiczenie 1: Git i GitHub

Prosty program konsolowy w C# stworzony w ramach ćwiczeń z przedmiotu APBD na temat Gita i GitHuba.

Program wyświetla powitanie zwracane przez `Greeting.GetMessage()`, a dla tablicy `{ 2, 4, 6 }` oblicza i wypisuje: sumę (`StatisticsHelper.CalculateSum`), średnią arytmetyczną (`StatisticsHelper.CalculateAverage`), liczbę elementów oraz największą wartość (`StatisticsHelper.CalculateMax`).

## Uruchomienie

Wymagania: zainstalowany [.NET SDK 8.0](https://dotnet.microsoft.com/download/dotnet/8.0) oraz [Git](https://git-scm.com/downloads).

W katalogu projektu wykonaj:

```bash
dotnet run
```

Oczekiwany wynik:

```
Witaj w kalkulatorze APBD!
Suma: 12
Średnia: 4
Liczba elementów: 3
Maksimum: 6
```

## Budowa

```bash
dotnet build
```

## Historia

Repozytorium zawiera scenariusze ćwiczeniowe: fast-forward merge, three-way merge bez konfliktu oraz scalenie z konfliktem i jego ręcznym rozwiązaniem.
