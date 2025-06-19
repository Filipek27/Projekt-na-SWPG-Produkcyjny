## 🧮 Inne funkcje statystyczne

- **LICZ.JEŻELI (`COUNTIF`)**  
  Liczy, ile komórek spełnia dany warunek.  
  **Przykład:** `=COUNTIF(A1:A10, ">100")`

- **PERCENTYL (`PERCENTILE.INC`, `PERCENTILE.EXC`)**  
  Zwraca wartość dla danego percentyla.  
  **Przykład:** `=PERCENTILE.INC(A1:A10, 0.9)`

- **KWARTYL (`QUARTILE.INC`, `QUARTILE.EXC`)**  
  Oblicza kwartyle (np. Q1, Q2, Q3).  
  **Przykład:** `=QUARTILE.INC(A1:A10, 3)`

- **AVERAGEIF / AVERAGEIFS**  
  Oblicza średnią na podstawie jednego lub wielu warunków.  
  **Przykład:** `=AVERAGEIF(A1:A10, ">100")`  
  **Przykład:** `=AVERAGEIFS(A1:A10, B1:B10, ">50", C1:C10, "<100")`

- **COUNTIFS**  
  Liczy komórki spełniające wiele warunków.  
  **Przykład:** `=COUNTIFS(A1:A10, ">0", B1:B10, "<10")`