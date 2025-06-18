# Funkcje statystyczne w Excelu

Microsoft Excel oferuje wiele funkcji statystycznych, które pozwalają szybko analizować dane liczbowe, obliczać miary tendencji centralnej, zróżnicowania, korelacji i wiele innych. Poniżej przedstawiono najważniejsze z nich wraz z krótkim opisem.

## 📊 Miary tendencji centralnej

- **ŚREDNIA (`ŚREDNIA`)**  
  Zwraca średnią arytmetyczną dla podanego zakresu.  
  **Przykład:** `=ŚREDNIA(A1:A10)`

- **MEDIANA (`MEDIANA`)**  
  Zwraca wartość środkową z zestawu danych.  
  **Przykład:** `=MEDIANA(A1:A10)`

- **MODA (`WYST.NAJCZĘŚCIEJ.WART` / `WYST.NAJCZĘŚCIEJ.TABL`)**  
  Zwraca wartość najczęściej występującą w zestawie danych.  
  **Przykład:** `=WYST.NAJCZĘŚCIEJ.WART(A1:A10)`

## 📐 Miary rozproszenia

- **ODCHYLENIE STANDARDOWE (`ODCH.STANDARD.PRÓBKI`, `ODCH.STAND.POPUL`)**  
  Mierzy, jak bardzo wartości różnią się od średniej.  
     - `ODCH.STANDARD.PRÓBKI` – dla próbki  
     - `ODCH.STAND.POPUL` – dla całej populacji  
  **Przykład:** `=ODCH.STANDARD.PRÓBKI(A1:A10)`

- **WARIANCJA (`WARIANCJA.PRÓBKI`, `WARIANCJA.POP`)**  
  Kwadrat odchylenia standardowego.  
  **Przykład:** `=WARIANCJA.PRÓBKI(A1:A10)`

- **ZAKRES (`MAX` - `MIN`)**  
  Różnica między największą a najmniejszą wartością.  
  **Przykład:** `=MAX(A1:A10)-MIN(A1:A10)`

## 🔗 Korelacje i współczynniki

- **KORELACJA (`WSP.KORELACJI`)**  
  Oblicza współczynnik korelacji Pearsona między dwiema zmiennymi.  
  **Przykład:** `=WSP.KORELACJI(A1:A10, B1:B10)`

- **WSPÓŁCZYNNIK DETERMINACJI (`R.KWADRAT`)**  
  Zwraca wartość \( R^2 \), czyli dopasowanie liniowe.  
  **Przykład:** `=R.KWADRAT(A1:A10, B1:B10)`

## 🧮 Inne funkcje statystyczne

- **LICZ JEŻELI (`LICZ.JEŻELI`)**  
  Liczy, ile komórek spełnia dany warunek.  
  **Przykład:** `=LICZ.JEŻELI(A1:A10, ">100")`

- **PERCENTYL (`PERCENTYL.PRZED.ZAMK`, `PERCENTYL.PRZED.OTW`)**  
  Zwraca wartość dla danego percentyla.  
  **Przykład:** `=PERCENTYL.PRZED.ZAMK(A1:A10, 0.9)`

- **KWARTYL (`KWARTYL.PRZED.ZAMK`, `KWARTYL.PRZED.OTW`)**  
  Oblicza kwartyle (np. Q1, Q2, Q3).  
  **Przykład:** `=KWARTYL.PRZED.ZAMK(A1:A10, 3)`

---

## 📘 Podsumowanie

Funkcje statystyczne Excela są nieocenione przy analizie danych – zarówno prostych, jak i zaawansowanych. Pozwalają szybko uzyskać miarodajne informacje o rozkładzie, zmienności czy zależnościach między danymi.

---

