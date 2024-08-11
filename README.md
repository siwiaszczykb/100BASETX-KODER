# Koder 100BASETX

## Opis projektu

Projekt polega na implementacji i symulacji kodera. Celem projektu jest zaprojektowanie i przetestowanie układu kodera oraz przeprowadzenie symulacji i analizy wyników. W projekcie wykorzystano różne narzędzia oraz języki opisu sprzętu, a wyniki zostały przedstawione w postaci wykresów oraz plików wynikowych.

## Funkcje projektu

- **Projektowanie kodera**: Implementacja kodera.
- **Symulacja**: Przeprowadzenie symulacji działania kodera.
- **Analiza wyników**: Generowanie i analiza wyników z symulacji, porównanie wyników rzeczywistych z idealnymi.
- **Dokumentacja**: Szczegółowa dokumentacja techniczna projektu, w tym schematy, wykresy oraz opis implementacji.

## Struktura projektu

Projekt składa się z następujących folderów:

- **asc**: Zawiera pliki z danymi wejściowymi i wyjściowymi z symulacji oraz pliki tekstowe używane w analizie:
  - `idealne.asc`, `rzeczywiste.asc`: Pliki zawierające schematy porównawcze (elementy idealne i rzeczywiste).
  - `plot-wyjsciowy.plt`: Plik używany do generowania gotowych wykresów.
  - `s1.txt`, `s2.txt`, `s3.txt`, `s4.txt`: Pliki tekstowe używane w analizach.

- **doc**: Zawiera dokumentację projektu oraz pliki graficzne przedstawiające wyniki symulacji:
  - `koder.pdf`: Dokumentacja projektu.
  - Pliki graficzne (`*.png`, `*.jpg`): Wykresy i wyniki symulacji oraz schematy blokowe projektu.

## Instalacja i uruchomienie

1. Sklonuj repozytorium:
   ```sh
   git clone https://github.com/siwiaszczykb/100BASETX-KODER.git
   ```

2. Przejdź do katalogu z projektem:
   ```sh
   cd 100BASETX-KODER
   ```

3. Uruchom symulację w LTSpice

## Wymagania

- Narzędzie symulacyjne LTSpice lub inne kompatybilne.
- Środowisko do pracy z LaTeXem (do edycji dokumentacji).

## Dokumentacja

Dokumentacja projektu znajduje się w pliku `doc/koder.pdf`. Zawiera ona pełen opis implementacji kodera, wyniki symulacji, schematy oraz analizę wyników.

## Autor

Projekt został zrealizowany grupowo w ramach kursu Podstawy Teletransmisji na Politechnice Śląskiej w roku akademickim 2023/2024.
