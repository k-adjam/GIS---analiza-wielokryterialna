# Analiza Wielokryterialna Przydatności Terenów do Zalesienia

## Opis projektu
Celem projektu było opracowanie narzędzia GIS umożliwiającego analizę wielokryterialną przydatności terenów do zalesienia w okolicach wsi Budzów (powiat suski). Analiza została przeprowadzona w środowisku **ArcMap** przy użyciu **Model Buildera**.

## Kryteria wyboru lokalizacji
Do analizy przyjęto następujące kryteria:
- **Nachylenie terenu** – preferowane strome stoki.
- **Bliskość wód powierzchniowych** – korzystne dla wzrostu roślinności.
- **Bliskość istniejących lasów** – ułatwia rozprzestrzenianie się ekosystemu.
- **Oddalenie od zabudowy** – minimalizuje wpływ urbanizacji.
- **Grunty rolne** – wykluczono trwałe użytki zielone i pastwiska.
- **Minimalna powierzchnia terenu** – co najmniej 0,1 ha.

## Wykorzystane narzędzia i metody
- **GIS**: ArcMap, Model Builder
- **Dane wejściowe**: 
  - Numeryczny Model Terenu (NMT)
  - BDOT10k (warstwy: zabudowa, lasy, grunty rolne, rzeki, drogi)
- **Metody analizy**:
  - Standaryzacja kryteriów metodą *Natural Breaks*
  - Wyznaczanie odległości (*Euclidean Distance*)
  - Reklasyfikacja i nadanie wag (*Weighted Overlay*)
  - Finalna selekcja obszarów (*Select by Attribute*)

## Wyniki
Analiza pozwoliła na wyznaczenie optymalnych terenów do zalesienia. Wynikowa mapa wskazuje, że najlepsze lokalizacje znajdują się:
- W pobliżu rzek,
- Na skraju istniejących lasów,
- Na gruntach rolnych o dużym nachyleniu.

