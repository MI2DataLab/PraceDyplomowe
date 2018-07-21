# Prace Dyplomowe

Studia to przygoda. Przeżyj ją razem z nami.

http://mi2.mini.pw.edu.pl/

## Tematy prac dyplomowych na rok 2018/2019

Każda z poniższych prac powinna zakończyć się (1) projektem pewnego rozwiązania analitycznego, (2) implementacją tego rozwiązania jako pakietu R lub biblioteki python, (3) opisem wybranego przypadku użycia ilustrującego silne strony rozwiązania.

Poniżej wymieniono ogólną tematykę w której prowadzone są badania.

### Douczanie modeli

* personalizacja modeli klasyfikacji (np lasów losowych) do specjalistycznch zadań z być może zaburzonym wektorem odpowiedzi (inny rozkład wyjściowy)

### Interactive eXplainers

* D^3ALEX - interaktywne explainery w D3 (z wrapperami z R i/lub pythona). Interaktywny drilldown po wyjaśniaczach - Ewa B


### PDP extensions

* Słupki błędów na wykresach PDP i Factor Merger
* Ciągła rodzina transformacji od Ceteris Paribus (lambda = 0) przez M plots (lambda = 0.5) po PDP (lambda = 1) [Rafał C]

### Analizy porównawcze

* Analiza Break Down vs LIME vs Shapley

### Strzały

* Rzadkie wyjaśnienia (na bazie breakDown)
* Stabilność wyjaśnień (boostrapowe przedziały ufności)

### Surrogate-assisted feature extraction

Pakiet SAFE wykorzystuje wybrane modele elastyczne (las losowy, xgboost) do generowania nowych, lepszych zmiennych, które można wykorzystać do białych skrzynek

* Dla zmiennych ciągłych. Transformacja nieliniowa, transformacja schodkowa, na podstawie pdp
* Dla zmiennych dyskretnych. Redukcja liczby poziomów zmiennej jakościowej
* Identyfikacja interakcji dwóch zmiennych i tworzenie nowych zmiennych po interkacji

Propozycje znalezione przez jedne surogatki są testowane na nowych modelach, np liniowych i tam weryfikowane czy i o ile sa lepsze.
W wyniku użytkownik dostaje raport per zmienna, co jest transfromowane i czy to coś poprawia.

https://www.ncbi.nlm.nih.gov/pubmed/27632993
http://www.aclweb.org/anthology/W09-2202

### Explainery dla szeregów czasowych

* Globalne i lokalne wyjaśnienia z uwzględnieniem występowania zmiennej lub zmiennych czasowych w modelach ze zmiennymi objaśniającymi. Przykłady modelowania
  - praca dyplomowa na temat zastosowania ML w przewidywaniu szeregów czasowych ze zmiennymi objaśniającymi: https://dspace.mit.edu/bitstream/handle/1721.1/99565/924315586-MIT.pdf?sequence=1
  - ANN w przewidywaniu kursów walut: https://arxiv.org/abs/1607.02093
  - ML vs TS: https://www.datascience.com/blog/time-series-forecasting-machine-learning-differences
  - porównanie kilku metod ML dla przewidywania cen biletów lotniczych: https://arxiv.org/pdf/1705.07205.pdf


### Inne

* Rozszerzona diagnostyka poszczególnych predykcji modelu.
* AutoML. Automatyzacja procesu budowy modelu. Porównanie technik konstrukcji modelu, agregacji wyników modeli. http://www.ml4aad.org/automl/, [H2O](http://docs.h2o.ai/h2o/latest-stable/h2o-docs/automl.html), [sklearn](http://automl.github.io/auto-sklearn/stable/)
* Nowe techniki wizualizacji gęstych danych. [Tasks, Data, and Designs](https://graphics.cs.wisc.edu/Papers/2018/SG18/scatterplots-preprint.pdf) [Uncertainty Visualization](http://graphics.uni-konstanz.de/publikationen/Goertler2018BubbleTreemapsUncertainty/bubble-treemaps.pdf)

