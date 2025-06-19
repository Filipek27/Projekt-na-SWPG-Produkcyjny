## 📐 Miary rozproszenia

- **ODCHYLENIE STANDARDOWE (`STDEV.S`, `STDEV.P`)**  
  Mierzy, jak bardzo wartości różnią się od średniej.  
  - `STDEV.S` – dla próbki  
  - `STDEV.P` – dla całej populacji  
  **Przykład:** `=STDEV.S(A1:A10)`

- **WARIANCJA (`VAR.S`, `VAR.P`)**  
  Kwadrat odchylenia standardowego.  
  **Przykład:** `=VAR.S(A1:A10)`

- **ZAKRES (`MAX` - `MIN`)**  
  Różnica między największą a najmniejszą wartością.  
  **Przykład:** `=MAX(A1:A10)-MIN(A1:A10)`

- **LARGE / SMALL**  
  Zwraca n-tą największą lub najmniejszą wartość w zbiorze.  
  **Przykład:** `=LARGE(A1:A10, 2)`  
  **Przykład:** `=SMALL(A1:A10, 1)`

- **RANK.EQ / RANK.AVG**  
  Określa pozycję liczby w zbiorze danych.  
  **Przykład:** `=RANK.EQ(A1, A1:A10)`