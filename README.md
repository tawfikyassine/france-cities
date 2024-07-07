# france cities (les villes de la France en json)
Updated France Cities Data for 2023: Comprehensive Dataset from Official Data.gouv.fr in Multiple Formats (final_cities.json). Explore and Enjoy!

# note : 
- json data version 03/2023
- insee is the unique identifier :)

```bash
"code_commune_insee" : the official unique identifier of the city
"code_postal" : zip code
"lat": latitude coordinate of the center of the city
"lng": longitude coordinate of the center of the city
"name": the name of the city
```
        
# how i did to make this file ? 
latitude & longitude coordinate for each city was getted from official la poste api.
link : https://datanova.laposte.fr/datasets/laposte-hexasmal/api-doc

Official small case names was getted from data.gouv.fr using the package : https://github.com/BaseAdresseNationale/codes-postaux
link : https://www.data.gouv.fr/fr/datasets/base-officielle-des-codes-postaux/


