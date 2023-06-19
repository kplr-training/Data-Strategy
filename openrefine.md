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

4- Survolez le curseur à droite de `Titan.,` puis cliquez sur "Modifier". Tapez `Titan` et donc `Titan.,` sera transformé en "Titan" pour les 33 occurrences.

![image](https://github.com/kplr-training/Data-Strategy/assets/123748177/899d1108-6256-460f-9dc9-fec663df2b73)

![image](https://github.com/kplr-training/Data-Strategy/assets/123748177/1d2feb6b-eb07-4a35-a84f-c1e0addea8c0)

Vous aurez le message suivant qui s'affiche en haut :

![image](https://github.com/kplr-training/Data-Strategy/assets/123748177/a3cc616d-0ba6-44cb-bd34-636592edf401)



## Filtrage des données

Chaque colonne contient une fonction de "filtre de texte". Le filtre de texte est utile pour identifier les éléments de données qui peuvent avoir de nombreuses variantes. Comme nous l'avons vu dans la section précédente, l'éditeur "Titan" peut être représenté de différentes manières. Pour explorer davantage cela, nous utilisons le filtre de texte pour filtrer toutes les occurrences de "Titan".

1- Cliquez sur la colonne 'Editeur' et choissisez `Text filter`

![image](https://github.com/kplr-training/Data-Strategy/assets/123748177/836388cc-b954-4f23-98a7-fb51977249c4)

2- Puis tapez le nom `Titan`

![image](https://github.com/kplr-training/Data-Strategy/assets/123748177/2c81de54-7a04-4004-af85-d6c0754f681d)

Vous aurez le résultat suivant: 

![image](https://github.com/kplr-training/Data-Strategy/assets/123748177/0dbf1e50-dd8c-4d57-aa24-f02f92e05453)

Quelques résultats intéressants en découlent. Nous constatons en haut que 4684 lignes correspondent à "Titan". Si vous vous étiez basés sur le résultat de l'étape précédente, vous auriez pu supposer que "Titan" avait seulement 3627 bandes dessinées dans la collection. Un examen plus approfondi à l'aide de la fonction de filtre de texte nous montre combien d'enregistrements nous aurions pu manquer en raison de fautes de frappe et de variantes d'orthographe.

3- À ce stade, il est possible de supprimer une partie des incohérences observées en cliquant sur l'option "Modifier" à l'intérieur des cellules de variantes individuelles.

![image](https://github.com/kplr-training/Data-Strategy/assets/123748177/0b45b16d-c618-49a9-9792-a30ec511f6bf)

4- Vous tapez `Titan` en appliquant cette modification à toutes les cellules identiques

![image](https://github.com/kplr-training/Data-Strategy/assets/123748177/f7c578fc-48b7-494c-b40b-30867e4f7077)

Vous aurez donc des données bien nettoyées.

![image](https://github.com/kplr-training/Data-Strategy/assets/123748177/d190ae80-c5ed-4390-b5bf-68913cea020f)

## Clustring des données 

En plus des facettes et des filtres, il est également possible de regrouper et de normaliser les variations dans l'ensemble de données. Le regroupement permettra de trouver des motifs de variation sans que vous ayez besoin de :

- Fouiller l'ensemble de données à la recherche de petites variations.
- ou les éliminer une par une à l'aide de facettes ou de filtres.

Commencez par la méthode par défaut de "collision de clé" en utilisant la fonction "empreinte digitale" ("fingerprint").

![image](https://github.com/kplr-training/Data-Strategy/assets/123748177/39433a36-7b66-4715-966a-d8dc57ee2947)

Le regroupement révèle des motifs d'irrégularité dans la colonne de données sélectionnée. Il est alors possible de passer en revue les résultats du regroupement et de fusionner les données dans la forme souhaitée. Dans l'exemple ci-dessous, en fusionnant les données variantes de la première section avec la forme "Titan", 4454 enregistrements seront modifiés.

![image](https://github.com/kplr-training/Data-Strategy/assets/123748177/441bd2b3-2c89-4012-9e62-c324c54c1e65)

Vérifiez que les modifications sont bien apportées!

![image](https://github.com/kplr-training/Data-Strategy/assets/123748177/e9899b1f-224c-4034-8b2e-76d561723555)

**NB: Si effectuer autant de modifications à la fois vous rend nerveux, ne vous inquiétez pas. L'un des grands avantages d'OpenRefine est qu'il stocke l'historique des modifications apportées à vos données et vous permet de revenir à des états précédents à n'importe quelle étape. Ainsi, vous pouvez toujours revenir en arrière et annuler des modifications si nécessaire, ce qui vous offre une grande flexibilité et une tranquillité d'esprit lors de l'édition de vos données.**

![image](https://github.com/kplr-training/Data-Strategy/assets/123748177/a8056307-3271-4a96-94c7-7fbf3980c752)

## Transformation des données

Il existe deux méthodes différentes pour transformer les données à l'aide d'OpenRefine: 

#### Méthode 1:

La première méthode vous permet d'utiliser des transformations prédéfinies qui effectuent des fonctions telles que la suppression des espaces vides en début et fin de texte (un espace supplémentaire au début ou à la fin d'une entrée). 

Cela peut sembler être un problème de mise en forme de données trivial, mais sans cette transformation, chaque élément de données avec un espace supplémentaire en début ou fin serait interprété comme différent d'une information identique par ailleurs (par exemple, " Titan " et "Titan").

![image](https://github.com/kplr-training/Data-Strategy/assets/123748177/ad58f415-afc8-48db-9e63-2e1f179b062c)

Vérifiez que les modifications sont bien apportées!

![image](https://github.com/kplr-training/Data-Strategy/assets/123748177/45f32314-3ff9-4f42-8f10-072604b8b4a3)

#### Méthode 2:

L'autre méthode de transformation vous permet d'utiliser le langage d'expression OpenRefine (GREL) pour normaliser les données. Dans l'exemple suivant, nous utilisons une expression régulière simple pour remplacer toutes les occurrences d'un point dans la colonne "Auteur-Personnes". 

Cette action modifie 3430 noms d'auteur. Si nous n'utilisions pas GREL, il nous faudrait beaucoup de temps pour parcourir chaque emplacement d'un point associé à chaque auteur dans l'ensemble de données.

![image](https://github.com/kplr-training/Data-Strategy/assets/123748177/dacdb082-44e2-4655-91eb-2211e2f40a81)

```
value.replace('.','')
```
![image](https://github.com/kplr-training/Data-Strategy/assets/123748177/ccc71195-346d-4242-b9bd-cdd79619fe27)

Vérifiez que les modifications sont bien apportées!

![image](https://github.com/kplr-training/Data-Strategy/assets/123748177/8e22aeb2-2f68-4a4b-be73-a0e72b4de941)

### Exportation des données

Une fois que vous avez atteint une étape où vous estimez que vos données sont prêtes, vous aurez de nombreuses options pour les extraire d'OpenRefine et les diffuser.

![image](https://github.com/kplr-training/Data-Strategy/assets/123748177/7bd618ed-bc30-4834-bb38-50a9eb6e5f53)

L'export de l'historique des modifications des données (si vous souhaitez conserver une documentation détaillée de vos données, c'est une excellente option) permet d'exporter l'historique complet des modifications que vous avez apportées à vos données dans OpenRefine. 

Cela peut inclure toutes les transformations, les regroupements, les nettoyages et autres opérations effectuées sur les données. En exportant cet historique, vous pouvez conserver une trace détaillée de toutes les étapes que vous avez suivies, ce qui facilite la documentation de votre processus de préparation des données.

![image](https://github.com/kplr-training/Data-Strategy/assets/123748177/1e530795-90e7-42b5-9fba-5d5770482dda)
