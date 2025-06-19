## 🧮 Inne funkcje statystyczne

- **LICZ.JEŻELI (`COUNTIF`)**  
  Funkcja LICZ.JEŻELI, jedna z funkcji statystycznych, umożliwia policzenie liczby komórek, które spełniają dane kryteria. Można na przykład policzyć, ile razy konkretna nazwa miasta występuje na liście klientów.  
  **Przykład:** `=LICZ.JEŻELI(A1:A10, ">100")`

- **PERCENTYL (`PERCENTILE`)**  
  Zwraca k-ty percentyl wartości w zakresie. Funkcję tę można stosować do określania progu akceptacji. Na przykład można podjąć decyzję o przebadaniu kandydatów, których wyniki są powyżej 90-ego percentylu.  
  **Przykład:** `=PERCENTYL(A1:A10, 0.9)`

- **KWARTYL (`QUARTILE.INC`, `QUARTILE.EXC`)**  
 Zwraca kwartyl zbioru danych. Kwartyle często są używane w danych o sprzedaży i w danych statystycznych do dzielenia populacji na grupy. Na przykład funkcję KWARTYL można zastosować do znalezienia górnych 25% dochodów w populacji.  
  **Przykład:** `=KWARTYL.INC(A1:A10, 3)`

- **ŚREDNIA.JEŻELI / AVERAGEIFS**  
  Zwraca średnią (średnią arytmetyczną) wszystkich komórek z zakresu, które spełniają podane kryteria.
  **Argumenty:**  
  - **Zakres** – wymagany. Komórki do sprawdzenia według kryteriów.  
  - **Kryteria** – wymagane. Warunek (liczba, tekst, wyrażenie lub odwołanie), według którego obliczana jest średnia.  
  - **Średnia_zakres** – opcjonalny. Komórki, z których liczona jest średnia; jeśli pominięte, używany jest zakres.

    **Przykład:** `=ŚREDNIA.JEŻELI(A1:A10, ">100")`  
    **Przykład:** `=ŚREDNIA.JEŻELIS(A1:A10, B1:B10, ">50", C1:C10, "<100")`

- **LICZ.WARUNKI**
  
  Funkcja LICZ.WARUNKI stosuje kryteria do komórek w wielu zakresach i zlicza, ile razy kryteria nie zostały spełnione.

  **Przykład:** `=LICZ.WARUNKI(A1:A10, ">0", B1:B10, "<10")`