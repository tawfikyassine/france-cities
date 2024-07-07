# france-cities
France cities update 2023 from official data.gouv.fr data in many format available in the file final_cities.json enjoy!

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


