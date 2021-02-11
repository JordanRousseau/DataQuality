# DataQuality

L'objectif de ce projet est de comparé les température des différentes capitales Européennes afin de trouver laquelles d'entres elle, correspond au données présente
dans le dataset `Savukoskikirkonkyla.xlsx` en ce basant sur les données des différentes capitales présentes dans `Climate.xlsx`

## Démarche

Afin de réaliser un travail collaboratif entre les différents membre du groupe, nous avons décidé d'utiliser Google Colab avec les librairies `pandas` et `numpy`.

La première chose à faire, fut donc d'associer notre Colab à un répertoire Google Drive dans lequel est stocké le fichier de référence.
Puis d'importer le dit fichier dans l'instance Colab.

Dans le but de trouver laquelle des capitale correspond aux données de `Climat.xlsx`, nous avons commencé par mettre en forme et analysé le données contenues dansce derniers. Ceci, pour pouvoir nous basé uniquement sur les données pertinentes, de qualitées et obtenir les référence nécessaire pour la comparaison.

Pour cela nous avons :

1 - Vérifier que l'import du fichier, ce soit bien effectué

2 - Calul du max par mois

3 - Calul du min par mois

4 - Calul du max par ans

5 - Calul du min par ans

6 - Évolution de la température pour tout les mois de l'année

![alt text](https://cdn.discordapp.com/attachments/689812910494711905/809367259268513842/unknown.png)

7 - Création du graphique des variations températures min/max au cours du mois par mois

![alt text](https://cdn.discordapp.com/attachments/689812910494711905/809367102477303868/unknown.png)

Une fois l'analyse des données de `Climat_corr.xlsx` réalisée, nous nous somme intéressé à la partie erreurs du fichier.

Tout fois, ce fichier contenenait de nombreuses erreurs que nous avons dû corrigées.

On obtiens le graphique suivant avant correction des erreurs:

![alt text](https://cdn.discordapp.com/attachments/689812910494711905/809367391162597376/unknown.png)

Et celui-ci après correction :

![alt text](https://cdn.discordapp.com/attachments/689812910494711905/809367542907928646/unknown.png)


Maintenant que nous avons corrigé et obtenu les différentes informations requises. Nous allons comparons maintenant les informations de `Climat_corr.xlsx` &
`Savukoskikirkonkyla.xlsx`

Voici le graphiques des données de `Savukoskikirkonkyla.xlsx`:

![alt text](https://cdn.discordapp.com/attachments/689812910494711905/809369213646667776/unknown.png)

Au vue des ressemble entre les deux fichiers, on peut en déduire qu'il s'agit d'une ville du Nord de l'Europe.

