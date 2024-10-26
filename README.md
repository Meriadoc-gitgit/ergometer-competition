# ergometer-competition
 
## Présentation du projet

Le fichier `.zip` joint contient les données recueillies au cours d’une compétition d’ergomètre *(machine à ramer)* → L’ensemble de fichiers sous forme `.json`.

La compétition se déroule comme suit: chaque série comporte 4 rameurs qui vont parcourir 2000m virtuels sur leurs machines. 

<aside>
👉🏻

**But**: Être le plus rapide possible sur ces 2000m. 

</aside>

Les données de chaque série sont enregistrées par les machines et recueillies. 

Les courses ont été paramétrées pour que chaque parcours de 2000m soit divisé en 4 parties de 500m, ie. les stats données par les ergomètres sont calculées et restituées tous les 500m. 

Chaque fichier `.zip` correspond à une série. 

## Tâches

### Question 1

Extraire les données des fichiers et les places dans un tableau restituant pour chaque rameur:

- sa performance, à savoir son temps sur 2000m
- la cadence moyenne sur 2000m
- le nombre de coups de rames sur 2000m
- le temps sur chaque portion de 500m
- la cadence moyenne sur chaque portion de 500m
- le nombre de coups de rame sur chaque portion de 500m

Le tableau aura une ligne par rameur.

### Question 2

En déduire pour chaque participant: 

- la vitesse moyenne en km/h sur 2000m
- la vitesse moyenne en km/h sur chaque portion de 500m
- la longueur moyenne parcourue par coup de rame sur 2000m
- la longueur moyenne parcourue par coup de rame sur 500m

### Question 3

Placer sur un graphique admettant 

- en abscisse le cadence moyenne sur 500m
- en ordonnée la longueur moyenne du coup sur 500

tous les points correspondant aux enregistrements sur 500m.

→ Questions: 

- À quelle cadence la vitesse maximale est-elle atteinte ?
- À quel point cela correspond-il sur le graphique ?

## Aller plus loin

<aside>
👉🏻

### Suggestions

- Faire des analyses sur la base de données construite
- Faire des statistiques
- Réaliser des graphiques, un dashboard
- Utiliser des données externes, etc.
</aside>