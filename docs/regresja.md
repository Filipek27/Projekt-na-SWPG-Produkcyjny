## 📉 Analiza regresji i prognozowanie

- **FORECAST.LINEAR**  
  Prognozuje przyszłą wartość na podstawie regresji liniowej. Przyszła wartość jest wartością y dla danej wartości x. Ta funkcja umożliwiają np. przewidywanie przyszłej sprzedaży, wymagań dotyczących zapasów lub trendów konsumpcyjnych.  
  **Przykład:** `=FORECAST.LINEAR(13, A1:A12, B1:B12)`

- **REGLINW (`TREND`)**  
  Zwraca wartości przewidywane na podstawie trendu liniowego, używając metody najmniejszych kwadratów.  
  **Przykład:** `=REGLINW(B1:B10, A1:A10)`

- **REGLINP (`LINEST`)**  
  Zwraca współczynniki prostej regresji (nachylenie, przecięcie) przy użyciu metody najmniejszych kwadratów. Funkcję REGLINP można również połączyć z innymi funkcjami, aby obliczyć statystyki dla innych typów modeli liniowych w nieznanych parametrach, takich jak wielomianowe, logarytmiczne, wykładnicze i szeregi potęgowe.  
  **Przykład:** `=REGLINP(B1:B10, A1:A10, TRUE, TRUE)`