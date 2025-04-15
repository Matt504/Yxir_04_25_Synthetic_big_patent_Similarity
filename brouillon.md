# Analyse

## Métriques quantitatives

* Taille du dataset : 499 * 4

* Valeurs manquantes : 0%

* Longueur des textes (mean/median/max/min) : 
* * anchor : 18507/19049/24641/15518
* * query : 128.42/162/230/78
* * positive : 1889.27/1543/12274/540
* * negative : 1912.24/1911/12274/540

## Analyse qualitative

* On remarque que ce DataSet traite de données sur des inventions, des technologies de pointes, des applications avec à chaque fois des query très pointues 

## Potential futur issues

* Inconsistent text lengths
* Unicode HTML tgas inside some columns : \u2122
* Some irrelevant information like : Fig., (a), [001], etc. 

# https://medium.com/ydata-ai/auditing-data-quality-with-pandas-profiling-b1bf1919f856