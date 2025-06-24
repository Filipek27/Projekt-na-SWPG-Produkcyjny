## 🧪 Testy statystyczne

- **T.TEST**  
  Zwraca prawdopodobieństwo skojarzone z testem t-Studenta. Funkcję T.TEST należy stosować do określenia, czy istnieje prawdopodobieństwo tego, że dwie próbki pochodzą z tych samych podległych populacji, które mają taką samą wartość średnią.  
  **Przykład:** `=T.TEST(A1:A10, B1:B10, 2, 1)`

- **Z.TEST**  
  Zwraca jednostronną wartość P dla testu z. Dla pewnej przyjętej w hipotezie średniej z populacji, x, funkcja Z.TEST zwraca prawdopodobieństwo, że średnia z próbki będzie większa od średniej z obserwacji w zbiorze danych (tablicy), tj. od obserwowanej średniej próbki.  
  **Przykład:** `=Z.TEST(A1:A10, 80)`

- **F.TEST**  
  Zwraca wynik testu F. Test F zwraca dwustronne prawdopodobieństwo, że wariancje w tablicach tablica1 i tablica2 nie różnią się znacząco. Funkcja umożliwia określenie, czy dwie próbki mają różne wariancje. Na przykład, mając wyniki testów ze szkół prywatnych i publicznych, można sprawdzić, czy w tych szkołach występują różne poziomy zróżnicowania wyników.  
  **Przykład:** `=F.TEST(A1:A10, B1:B10)`