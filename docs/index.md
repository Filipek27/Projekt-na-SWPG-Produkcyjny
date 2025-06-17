# Funkcje statystyczne w Excelu

Microsoft Excel oferuje wiele funkcji statystycznych, które pozwalają szybko analizować dane liczbowe, obliczać miary tendencji centralnej, zróżnicowania, korelacji i wiele innych. Poniżej przedstawiono najważniejsze z nich wraz z krótkim opisem.

## 📊 Miary tendencji centralnej

- **ŚREDNIA (`AVERAGE`)**  
  Zwraca średnią arytmetyczną dla podanego zakresu.  
  **Przykład:** `=AVERAGE(A1:A10)`

- **MEDIANA (`MEDIAN`)**  
  Zwraca wartość środkową z zestawu danych.  
  **Przykład:** `=MEDIAN(A1:A10)`

- **MODA (`MODE.SNGL` / `MODE.MULT`)**  
  Zwraca wartość najczęściej występującą w zestawie danych.  
  **Przykład:** `=MODE.SNGL(A1:A10)`

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

## 🔗 Korelacje i współczynniki

- **KORELACJA (`CORREL`)**  
  Oblicza współczynnik korelacji Pearsona między dwiema zmiennymi.  
  **Przykład:** `=CORREL(A1:A10, B1:B10)`

- **WSPÓŁCZYNNIK DETERMINACJI (`RSQ`)**  
  Zwraca wartość \( R^2 \), czyli dopasowanie liniowe.  
  **Przykład:** `=RSQ(A1:A10, B1:B10)`

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

---

## 📘 Podsumowanie

Funkcje statystyczne Excela są nieocenione przy analizie danych – zarówno prostych, jak i zaawansowanych. Pozwalają szybko uzyskać miarodajne informacje o rozkładzie, zmienności czy zależnościach między danymi.

---

