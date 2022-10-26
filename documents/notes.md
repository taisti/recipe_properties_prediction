Cel `Food computingu`:
- budowa systemu rekomendacyjnego,
- zamiennik składników,
- ostrzeżenia zdrowotne,
- spersonalizowana i zbilansowana dieta,
- promowanie zdrowej żywności.

Restrykcje przepisu:
- preferencje osobiste:
	- wygląd,
	- dźwięk,
	- temperatura.
- zawartość składników mineralnych,
- ograniczenia dietetyczne,
- ograniczenia zdrowotne,
- ograniczenia społeczne:
	- religijne,
	- kulturowe.

Cel pracy - budowa systemu rekomendacyjnego, który wykrywa przepisy z grupy ryzyka (restrykcji).

Zbiór danych:
- inny zbiór danych na [kaggle](https://www.kaggle.com/datasets/shuyangli94/food-com-recipes-and-user-interactions),
	- [Generating Personalized Recipes from Historical User Preferences](https://www.aclweb.org/anthology/D19-1613/),
	- 180K+ przepisów,
	- 700K+ recenzji przepisów,
	- przepisy z okna czasowego 18 lat prawd. $(2000, 2018)$,
	- gotowe zbiory `walidacyjny`, `treningowy`, `testowy` oraz zbiory pomocnicze z których powstały,
	- przepisy stokenizowane przez BPE dla GPT,
	- kolumny tj. `kalorie, składniki`, `techniki`, `nazwa przepisu`, `ocena użytkowników dot. przepisu`, `recenzja`, `data recenzji`, `czas przygotowania`, `tagi`, `informacje dietetyczne`, `opis`,
- źródło [Food.com](Food.com),
	- 230 000 przepisy w języku angielskim,
	- $>$ 1 000 000 interakcji użytkowników,
	- lata $(2000, 2018)$,
	- dużo nie oznakowanych,
	- tagi nie powiązane z ograniczeniami żywieniowymi,
- lista składników i  kategorii,
- przepisy powiązane wyłącznie z ograniczeniami żywieniowymi,
- 10 kategorii ograniczeń żywieniowych,
- ~ 30 000 przepisów,
- ~ 7 000 składników
- podzielili tagi na mniejsze elementy,
- w wynikach ~ 70%-80%