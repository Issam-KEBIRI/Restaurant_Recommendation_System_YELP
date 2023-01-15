# Restaurant Recommendation System YELP

![GitHub](https://img.shields.io/github/license/kebiri-isam-dine/UniversityProjects?color=g&style=for-the-badge)
![GitHub last commit](https://img.shields.io/github/last-commit/kebiri-isam-dine/Restaurant_Recommendation_System_YELP?color=red&style=for-the-badge)
![GitHub contributors](https://img.shields.io/github/contributors/kebiri-isam-dine/Restaurant_Recommendation_System_YELP?color=yellow&style=for-the-badge)

![GitHub dev_language](https://img.shields.io/badge/Neo4j-018bff?style=for-the-badge&logo=neo4j&logoColor=white)
![GitHub dev_language](https://img.shields.io/badge/Python-FFD43B?style=for-the-badge&logo=python&logoColor=blue)
![GitHub dev_language](https://img.shields.io/badge/json-6aa84f?style=for-the-badge&logo=json&logoColor=white)

![GitHub Org's stars](https://img.shields.io/github/stars/kebiri-isam-dine?style=social)
![GitHub followers](https://img.shields.io/github/followers/kebiri-isam-dine?style=social)



## About The Project
<img src="./Project/YELP_restaurents.png">

#### Study context :
Le cas d’étude proposé concerne le site participatif d’avis Yelp décrit dans le document « Contexte d’étude - Analyse de données Yelp ». Globalement, des utilisateurs donnent leur avis sur des restaurants. Ces utilisateurs possèdent ou non des amis qui sont aussi des utilisateurs du site.

#### Work required :   
➥ Proposez une **modélisation** permettant de couvrir ce cas d’étude    
➥ Écrire un script python permettant de **transformer** et **nettoyer** les fichiers [yelp_restaurants.json](Dataset/Json_OriginalDdata/yelp_restaurants.json), [yelp_user.json](Dataset/Json_OriginalDdata/yelp_user.json) et [yelp_review.json](Dataset/Json_OriginalDdata/yelp_review.json) en autant de fichiers .csv que nécessaire     
➥ Créer une nouvelle base de données locale sous neo4j et définir les requêtes en **langage cypher** permettant de répondre aux besoins décrits [ici](Project/Project.pdf)    
➥ Construction du **moteur de recommandation** d’influenceurs, pour sélectionner ces utilisateurs-influenceurs pour chacun des restaurants, on se propose de calculer un **score d’influence** des utilisateurs de la plateforme avec les règles décrites [ici](Project/Project.pdf)       



### Keywords

Recommendation System, YELP Dataset, influence score, pandas, json, csv, neo4j database, cypher query language

### Built With

* Python 3.6
* neo4j 

## Installation

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install :

```python 
pip install py2neo
```

## Packages

```python

import pandas as pd
import numpy as np
from IPython.display import Image
from py2neo import Graph
from random import randrange
```



## Dataset
Les trois Dataset YELP en json :   
➥ [yelp_restaurants.json](Dataset/Json_OriginalDdata/yelp_restaurants.json)     
➥ [yelp_user.json](Dataset/Json_OriginalDdata/yelp_user.json)      
➥ [yelp_review.json](Dataset/Json_OriginalDdata/yelp_review.json)       



## Output

- Data cleaning and transformation in .csv :    
➥ [friend.csv](Dataset/CSV_Output/friend.csv)     
➥ [restaurant.csv](Dataset/CSV_Output/restaurant.csv)      
➥ [review.csv](Dataset/CSV_Output/review.csv)     

- Data query in .cypher [here](Data_query.cypher)

- Le moteur de recommandation d’influenceurs et calcul du score d’influence dans le script python [main.ipynb](main.ipynb)
     


## Results
Affichage du **graphe globale**
<img src="./screen_neo4j/graph.png">

## License

[GPL-3.0](https://choosealicense.com/licenses/gpl-3.0/)

## Contact

📫 How to reach me: kebiri.isam.dine@gmail.com

🌐 My Portfolio: <https://kebiri-isam-dine.github.io/>

🔗 Project Link: [https://github.com/kebiri-isam-dine/Restaurant_Recommendation_System_YELP](https://github.com/kebiri-isam-dine/Restaurant_Recommendation_System_YELP)
