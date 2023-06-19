# Préparation des données en utilisant OpenRefine

OpenRefine est un outil open source de préparation des données qui permet de nettoyer, transformer et organiser efficacement les ensembles de données. Il offre des fonctionnalités puissantes pour faciliter le processus de nettoyage, le regroupement et la transformation des données, ce qui en fait un outil précieux pour les chercheurs, les scientifiques des données et les professionnels travaillant avec des données de différentes sources. 

OpenRefine permet d'explorer et d'analyser les données de manière interactive, tout en offrant des fonctionnalités avancées telles que le facettage, le filtrage et l'enrichissement des données.

## Description

Le guide "Préparation des données en utilisant OpenRefine" est conçu pour vous accompagner et vous initier à l'utilisation d'OpenRefine. Vous apprendrez à facetter, filtrer, regrouper et transformer vos données à l'aide de cet outil. Grâce à des exercices pratiques et des démonstrations, vous serez en mesure d'appliquer ces techniques à vos propres ensembles de données, vous permettant ainsi de préparer efficacement vos données pour la recherche en sciences humaines numériques.

## Installation OpenRefine on Codespace

```
wget https://github.com/OpenRefine/OpenRefine/releases/download/3.7.2/openrefine-linux-3.7.2.tar.gz
```
![image](https://github.com/kplr-training/Data-Strategy/assets/123748177/70abcbae-12e7-4f88-83ef-81e7c6375cae)

```
tar -xzf openrefine-linux-3.7.2.tar.gz
```
```
cd openrefine-3.7.2
```
![image](https://github.com/kplr-training/Data-Strategy/assets/123748177/eb08d9df-4075-4b5d-96fd-0c18c14c865e)

```
./refine
```

![image](https://github.com/kplr-training/Data-Strategy/assets/123748177/f2d1d4f6-c1ec-4011-a0eb-3d6fa525cd8e)

![image](https://github.com/kplr-training/Data-Strategy/assets/123748177/0eaa3018-3605-45e2-a19c-b125ce76ccf8)

## Data preparation using OpenRefine

### Création du projet

[Télécharger le fichier des données](https://www.thomaspadilla.org/data/dataprep/authors-people.csv)

![image](https://github.com/kplr-training/Data-Strategy/assets/123748177/6bf23384-ddf1-45bc-9e17-e2e079624e1c)

![image](https://github.com/kplr-training/Data-Strategy/assets/123748177/6d22f1e4-a106-43c2-ae9a-3367dbcbb5df)

![image](https://github.com/kplr-training/Data-Strategy/assets/123748177/0494e326-33b7-45ab-9c8c-06a2fafb77ca)

### Examination des données

Prenez quelques instants pour observer la structure des données en gardant à l'esprit les principes de "données organisées". L'examen des données est une étape essentielle dans le processus d'analyse. Cela implique de prendre le temps d'explorer les données, d'examiner leur structure, leur qualité et leur contenu. Lors de cet examen, il est important d'identifier les éventuelles erreurs, les incohérences et les valeurs manquantes. 

De plus, il est recommandé de comprendre la signification des différentes variables et de repérer les schémas ou les tendances qui pourraient être présents. Cet examen approfondi des données permet de poser les bases d'une analyse rigoureuse et de formuler des questions pertinentes pour orienter la suite du travail de traitement et d'interprétation des données.

### Facettage des données

Chaque colonne dispose d'une fonction de facettes qui vous permet d'identifier rapidement les incohérences dans vos données en comptant le nombre d'occurrences uniques pour chaque élément de données de cette colonne. En utilisant cette fonction, vous allez analyser la répartition des bandes dessinées dans l'ensemble de données par éditeur. La première étape consiste à évaluer la cohérence des données dans la colonne "Éditeur".

1- Cliquez sur la colonne "Éditeur" > Sélectionnez "Facette" > Sélectionnez "Facette de texte".

![image](https://github.com/kplr-training/Data-Strategy/assets/123748177/0e20a443-611d-48d3-bb66-f24e760675d8)

2- Appliquez la facette par 'count' sur le côté gauche puis observez le nombre d'enregistrements pour l'éditeur "Titan".

![image](https://github.com/kplr-training/Data-Strategy/assets/123748177/e291a883-ef56-4e9c-88bf-4b34974673ff)

3- Appliquez la facette par 'name' sur le côté gauche puis faites défiler jusqu'à "Titan" et observez les différentes représentations de "Titan".

![image](https://github.com/kplr-training/Data-Strategy/assets/123748177/4c9710e2-afb5-4276-a484-4e3f6df5836a)

4- Survolez le curseur à droite de "Titan.," puis cliquez sur "Modifier". Tapez "Titan" et donc "Titan.," sera transformé en "Titan" pour les 33 occurrences.



