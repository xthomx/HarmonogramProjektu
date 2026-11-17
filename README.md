# Harmonogram projektu

Program do planowania harmonogramu projektu w stylu MS Project, z eksportem do Excela (.xlsx) do rozsyłania zainteresowanym.

## Uruchomienie
Otwórz `Harmonogram.html` w Edge lub Chrome (dwuklik). Nie wymaga instalacji ani internetu.

## Funkcje
- zadania, kamienie milowe (czas 0), fazy z hierarchią i zwijaniem
- zależności ZR / RR / ZZ / RZ z opóźnieniem lub zakładką (np. `3RR+2`)
- kalendarz dni roboczych, polskie święta, własne dni wolne
- ścieżka krytyczna, zapasy czasu, plan bazowy i odchylenia
- wykres Gantta ze strzałkami zależności (skala: dni / tygodnie / miesiące)
- zasoby z obłożeniem (`Anna, Piotr[50%]`) i widok przeciążeń
- cofnij / ponów, autozapis w przeglądarce, zapis i odczyt projektu (.json)

## Eksport do Excela
Przycisk „Eksport do Excela” tworzy plik .xlsx z arkuszami: **Gantt**, **Lista zadań**, **Kamienie milowe**, **Obciążenie zasobów**.
