# correlaid-hackathon-housing
Data for the CorrelAid x City Interaction Lab February 2021. Challenge 2: Housing Problems

## Read in Data

### Python 

### R
```r
df <- read.csv2("data/social-housing-paris/logements-sociaux-finances-a-paris.csv", stringsAsFactors = FALSE)

# directly with sf 
library(sf)

df_sf <- sf::read_sf("data/social-housing-paris/logements-sociaux-finances-a-paris.geojson")
```


## License
*Attribution*: Data was downloaded on 2021-02-09, 14:37 (UTC+1) from https://opendata.paris.fr/explore/dataset/logements-sociaux-finances-a-paris/information/

Data in this repository is licensed under the [Open Data Commons Open Database License (ODbL)](https://opendatacommons.org/licenses/odbl/).

## Translation of Description

```
Inventory of social housing financed in Paris, by district, by year, by owner, by number of units, by type of program, by category of financing and by type of construction.

More information :

The social housing units are differentiated in particular by:

> Category of financing :
- PLA I housing (Prêt locatif aidé d'intégration) is very social housing for people with particular difficulties in accessing housing. In particular, they include integration housing managed by associations for the housing of disadvantaged people.
- PLUS housing (Prêt locatif à usage social) corresponds to classic social housing.
- PLS housing (Prêt locatif social) is intermediate type social housing, intended in particular for the middle classes and accessible under income ceilings covering three out of four Parisian households.

> Method of construction :
- new construction
- the acquisition followed by a major rehabilitation and restructuring of buildings that can be compared to new construction
- the acquisition and conventionnement in social housing with no or little work.

> Year of approval = this is the administrative decision by which the competent authority gives its approval for the financing of a social housing operation
```


Translated with www.DeepL.com/Translator (free version)
