## 📐 Miary rozproszenia

- **ODCHYLENIE STANDARDOWE (`STDEV.S`, `STDEV.P`)**  
  Mierzy, jak bardzo wartości różnią się od średniej.  
    - `ODCH.STANDARD.PRÓBKI` (`STDEV.S`) – dla próbki  
    - `ODCH.STANDARD.POPUL` `(STDEV.P)` – dla całej populacji  

    **Przykład:** `=ODCH.STANDARD.PRÓBKI(A1:A10)`

- **WARIANCJA.PRÓBKI / WARIANCJA.POPUL (`VAR.S` / `VAR.P`)**  
  Kwadrat odchylenia standardowego.  
  **Przykład:** `=WARIANCJA.PRÓBKI(A1:A10)`

- **ZAKRES (`MAX` - `MIN`)**  
  Różnica między największą a najmniejszą wartością.  
  **Przykład:** `=MAX(A1:A10)-MIN(A1:A10)`

- **MAX.K / MIN.K (`LARGE` / `SMALL`)**  
  Zwraca n-tą największą lub najmniejszą wartość w zbiorze.  
  **Przykład:** `=MAX.K(A1:A10, 2)`  
  **Przykład:** `=MIN.K(A1:A10, 1)`

- **POZYCJA.NAJW / POZYCJA.ŚR (`RANK.EQ` / `RANK.AVG`)**  
  Określa pozycję liczby w zbiorze danych.  
  **Przykład:** `=POZYCJA.ŚR(A1, A1:A10)`