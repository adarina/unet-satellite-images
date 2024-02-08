
# Instrukcja uruchomieniu projektu U-net Road i Land

Aby uruchomić jeden z dwóch projektów w środowisku Google Colab, wykonaj poniższe kroki:

## 1. Otwórz Google Colab
Otwórz przeglądarkę internetową i przejdź pod adres https://colab.research.google.com.

## 2. Zaimportuj wybrany notatnik
W Google Colab, wybierz opcję "File" (Plik) w menu głównym, a następnie wybierz "Open Notebook" (Otwórz notatnik).

## 3. Wybierz środowisko uruchomieniowe
Upewnij się, że masz dostęp do odpowiedniego środowiska uruchomieniowego. Wybierz "Runtime" (Uruchomienie) w menu głównym, a następnie wybierz "Change runtime type" (Zmień typ uruchomienia). Wybierz odpowiednią opcję, taką jak CPU, GPU lub TPU, w zależności od dostępnych zasobów.

## 4. Zmień ścieżkę do katalogu z danymi
W komórce notatnika, która odnosi się do danych (```drive-dir```), upewnij się, że zmieniono ścieżkę do katalogu głównego.

## 5. Wykonaj notatnik
Kliknij "Runtime" (Uruchomienie) w menu głównym i wybierz "Run all" (Uruchom wszystko), aby uruchomić wszystkie komórki notatnika lub uruchamiaj komórki po kolei (zalecane w szczególności, gdy nie chcemy trenować na nowo modelu tylko wczytać istniejący).