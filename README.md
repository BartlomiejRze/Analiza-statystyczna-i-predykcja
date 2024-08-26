# Opis projektu
Projekt skupia się na badaniu i zrozumieniu czynników wpływających na ceny klocków LEGO oferowanych przez wybrany sklep. Celem projektu jest dostarczenie głębszej wiedzy na temat tego, jak różnorodne czynniki, takie jak ilość klocków, seria, rok produkcji, i inne, wpływają na kształtowanie cen produktów LEGO w danym sklepie. W naszej analizie zdecydowaliśmy się na połączenie modelu Gradient Boosting Regressor wraz 
z Polynomial Features. W przypadku regresji, można użyć Polynomial Features do przekształcenia danych, a następnie zastosować Gradient Boosting Regressor do dopasowania modelu do nieliniowych zależności. Ten kombinowany sposób pomaga w radzeniu sobie z bardziej skomplikowanymi strukturami danych, które nie są dobrze odzwierciedlone przez proste modele liniowe.

**Biblioteki jakie zostały użyte w analizie to m.in.**
- Selenium (użyta w procesie pozyskiwania danych ze strony internetowej),
- Seaborn (użyta w celu wizualizacji danych),
- Scikit-learn (biblioteka do uczenia maszynowego, zawiera wiele narzędzi i algorytmów umożliwiających łatwe tworzenie modeli, analizę danych i wiele innych zadań związanych z przetwarzaniem danych),
- Re (dostarcza funkcji i obiektów, które umożliwiają korzystanie z wyrażeń regularnych).

# Metodologia:
-	Zbieranie Danych: Pozyskanie danych dotyczących cen, rodzajów klocków LEGO, informacji o ilości figurek, informacji o pudełku i instrukcji 
-	Analiza Statystyczna: Zastosowanie narzędzi statystycznych do identyfikacji korelacji i zależności między cenami, a różnymi determinantami.
-	Predykcja: Przeprowadzenie analizy jakie czynniki wpływają na wartość produktów LEGO oraz predykcja ich cen.

# Podsumowanie:

![image](https://github.com/user-attachments/assets/8eec27fd-53d2-458c-befb-d17ecead7c6e)

**Model uzyskał następujące wyniki:**
zarówno MSE (~1340.5444) jaki i MAE (~24.8972) jest relatywnie wysokie i wskazuje na rozbieżności między prognozowanymi, a rzeczywistymi wartościami cen zestawów LEGO. 
Z kolei R² (~0.8967) sugeruje, że model dosyć dobrze wyjaśnia zmienność danych. Około 90% zmienności zależnej zmiennej prognozowanej jest wyjaśniane przez model.
