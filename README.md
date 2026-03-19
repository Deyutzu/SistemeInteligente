# 🌲 Descrierea Proiectului
Acest proiect își propune să exploreze evoluția suprafețelor împădurite la nivel global în ultimul sfert de secol. Utilizând tehnici de Machine Learning, proiectul va analiza corelațiile dintre factorii geografici/economici și rata de defrișare sau reîmpădurire (afforestation).

Scopul principal: Construirea unui model de regresie capabil să prezică tendințele viitoare ale fondului forestier pe baza datelor istorice.

# Dataset
Setul de date utilizat este preluat de pe Kaggle: "Global Deforestation & Afforestation (2000-2025)".
Acesta conține informații despre:
Suprafața forestieră totală per țară/an.
Rata anuală de pierdere a pădurii.
Progresul programelor de reîmpădurire.
Conform sugestiei domnului profesor, am inclus în plan și un set de date secundar pentru precipitații. Voi folosi SQL (SQLite) pentru a integra aceste două baze de date, facilitând astfel o analiză corelativă între precipitatii și evoluția fondului forestier.

https://www.kaggle.com/datasets/ashyou09/global-deforestation-and-afforestation-2000-2025
https://data.worldbank.org/indicator/AG.LND.PRCP.MM

# Tehnologii propuse
Limbaj: Python
Librării: Pandas (manipulare date), Matplotlib/Seaborn (vizualizare), Scikit-Learn (modelare ML).
Algoritmi vizați: Linear Regression, Random Forest Regressor.
