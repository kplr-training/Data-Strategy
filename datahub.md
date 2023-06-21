# DataHub pour la gouvernance des données

DataHub est une plateforme open-source développée par LinkedIn pour la gestion des métadonnées et la collaboration autour des données. C'est un outil conçu pour aider les organisations à découvrir, à comprendre et à gérer leurs actifs de données. 

DataHub permet de cataloguer les données, de suivre leur origine et leur évolution, de faciliter la collaboration entre les équipes travaillant sur les données et de fournir des fonctionnalités de recherche et de découverte des données. Il vise à améliorer la gouvernance des données, à garantir la qualité des données et à faciliter l'accès et l'utilisation des données au sein de l'organisation. DataHub est extensible et peut être intégré à d'autres outils et technologies de gestion des données.


## I- Interface de DataHub 

Pour accèder à l'interface de démonstration de DataHub pour tester l'outil, vous pouvez taper l'adresse suivante dans votre navigateur:

https://khaoulakplr-datahub-b4utc2qdeb9.ws-eu100.gitpod.io

Vous aurez l'interface suivante :

![image](https://github.com/kplr-training/Data-Strategy/assets/123748177/153c1b9f-e732-49f4-a205-13b7aafefb0a)

## II- La conception d'un glossaire

La conception d'un glossaire est un aspect essentiel de la gouvernance des données. Un glossaire est une collection organisée de termes, définitions et métadonnées liés aux données utilisées dans une organisation.

La conception d'un glossaire consiste à définir et organiser les termes, définitions et concepts utilisés dans un domaine spécifique ou au sein d'une organisation. Cela permet d'assurer une compréhension commune et cohérente des données et des métadonnées. La conception d'un glossaire implique l'identification des termes clés, la définition de ces termes, l'établissement de relations entre les termes, l'organisation logique du glossaire et sa maintenance régulière.


Dans le coin supérieur droit, vous voyez une barre de menu avec quelques options. Pour ajouter des connaissances métier `Business Knowledge`au catalogue de données `Data Catalog`, vous vous intéressez à l'option "Gouverner". Voici les sous-options disponibles :

![image](https://github.com/kplr-training/Data-Strategy/assets/123748177/eee82530-16d0-4bf1-9375-4009f784f09d)

Une conception de catalogue appropriée nécessite une bonne compréhension des concepts de métadonnées disponibles :

- Domaine : une zone d'activité commerciale plus large où nous souhaitons organiser des actifs de données connexes (par exemple, tous les actifs de données - - appartenant à l'organisation des ventes)
- Groupe de termes : similaire à un dossier d'un système d'exploitation qui peut contenir des termes ou même d'autres groupes de termes.
- Termes : des mots ou des expressions ayant une définition métier spécifique qui leur est assignée.
- Tags : des étiquettes informelles et peu contrôlées qui aident à la recherche et à la découverte.

La question maintenant est de savoir comment utiliser ces concepts de manière appropriée. Des directives doivent être élaborées par le bureau central de la gouvernance des données afin que chaque domaine d'activité utilise les concepts de la même manière. On pourrait dire que les "groupes de termes" doivent être traités comme des processus métier. 

### Exemple :

Prenons l'exemple suivant : nous voulons avoir un processus métier (groupe de termes) "Approvisionnement en équipements" qui contient tous les termes liés à l'approvisionnement en équipements (par exemple, nom de l'équipement, fabricant de l'équipement, équipement lui-même). Ces termes appartiennent au domaine "Fabrication". Cela peut être fait dans DataHub de la manière suivante :

1- Dans le menu `Govern`, choisissez `Domains`: 

![image](https://github.com/kplr-training/Data-Strategy/assets/123748177/03bedb82-e0c0-4f79-91b9-c02be14e1389)

2- Maintenant, créez le domaine `Manufacturing`.

![image](https://github.com/kplr-training/Data-Strategy/assets/123748177/cdefc9c8-e32a-408a-bee4-5fd08ca28104)

3- Revenez dans le menu `Govern`, choisissez `Glossary`: 

![image](https://github.com/kplr-training/Data-Strategy/assets/123748177/d7ab64c5-0a2a-45d6-aecc-4703d5405920)

4- Cliquez `Add Term Group`: 

![image](https://github.com/kplr-training/Data-Strategy/assets/123748177/dda919b7-6421-4801-9246-4f7d3836e892)

5- Créez le Term Group `Equipement Procurement`:

![image](https://github.com/kplr-training/Data-Strategy/assets/123748177/edf8ab4d-14dc-4c28-81ea-f49e8e750c36)

6- Cliquez `Add Term`: 

![image](https://github.com/kplr-training/Data-Strategy/assets/123748177/abb1ac74-ee55-426b-ab27-42687ed14a67)

7- Créez le Term  `Equipement`:

![image](https://github.com/kplr-training/Data-Strategy/assets/123748177/f038a741-9d21-4227-8ccf-7861563c6761)

8- Dans la liste à gauche, cherchez `Equipement`:

![image](https://github.com/kplr-training/Data-Strategy/assets/123748177/6dddd9b8-5835-4cfb-9d19-f01c197ac077)

9- Liez ce dernier au domaine déjà créé

![image](https://github.com/kplr-training/Data-Strategy/assets/123748177/616a132d-169e-423a-a429-a6fb91e313f8)


![image](https://github.com/kplr-training/Data-Strategy/assets/123748177/483f7ac8-d9d8-4aa8-810d-f2249b1586c3)

10- Une fois votre Term créé, vous pouvez définir une définition officielle et ajouter également des informations supplémentaires sous forme de liens :

![image](https://github.com/kplr-training/Data-Strategy/assets/123748177/1dbcba18-e9e8-44cb-ac66-a6533484c6c4)

- Vous pouvez ajouter une description:

![image](https://github.com/kplr-training/Data-Strategy/assets/123748177/cf2e8edd-e946-4981-b03a-cdb46d347c5d)

- Vous pouvez ainsi ajouter un lien:

![image](https://github.com/kplr-training/Data-Strategy/assets/123748177/099377a1-f7bf-4a99-9a74-dd98e79561a0)

![image](https://github.com/kplr-training/Data-Strategy/assets/123748177/069204ba-9b60-498d-a2df-0acb1853ee5f)

## III- Modélisation sémantique

Vous pouvez aller encore plus loin dans la modélisation sémantique de vos Terms ! Supposez que vous vouliez spécifier des termes qui fournissent des informations détaillées sur un équipement, comme son nom ou son fabricant. Vous pouvez également construire une hiérarchie de ce type dans DataHub en utilisant la relation "contient", qui est similaire à une relation objet/attribut :

1- Créez d'abord deux autres Terms qui seront liés au Term `Equipement`

![image](https://github.com/kplr-training/Data-Strategy/assets/123748177/baa77960-083a-4e5f-99cb-605257f20e91)

![image](https://github.com/kplr-training/Data-Strategy/assets/123748177/59f1f11c-90ee-4b03-8cd4-8c68e3c00235)

2- Dans la partie `Related Terms` du Term `Equipement`, choisissez `Add Terms`:

![image](https://github.com/kplr-training/Data-Strategy/assets/123748177/48ed9616-9ad1-4170-b149-b1d3a19adf2e)

3- Ajoutez les deux Terms créés:

![image](https://github.com/kplr-training/Data-Strategy/assets/123748177/7d1608b5-9ca7-40af-ac82-7786a48188b1)

4- Vous aurez le résultat suivant:

![image](https://github.com/kplr-training/Data-Strategy/assets/123748177/8dfbdbc2-16cb-4d63-9ab0-6c4325c7ecfd)

De plus, vous pouvez utiliser l'héritage dans votre glossaire. Par exemple, nous voulons différencier les types d'équipements tels que "équipement de mesure" et "équipement logistique" qui ne diffèrent pas de "équipement" mais sont simplement des types plus spécifiques d'"équipement". Dans ce cas, vous pouvez relier ces termes via la fonction "inherits" :

1- Créez d'abord un Term `Logistics equipement`

![image](https://github.com/kplr-training/Data-Strategy/assets/123748177/c78ffa14-bf20-4b5a-a36f-0ffab0e49386)

2- Puis, dans la partie `inherits` de `Related Terms` , ajouté le Term d'ou vous allez hérité: 

![image](https://github.com/kplr-training/Data-Strategy/assets/123748177/6b222821-0406-49ab-a507-3fa4ce15b77e)


![image](https://github.com/kplr-training/Data-Strategy/assets/123748177/b772c947-5548-4b0f-90e2-443e676d13c5)

3- Vous aurez le résultat suivant:

![image](https://github.com/kplr-training/Data-Strategy/assets/123748177/add9b824-e880-4d6a-8937-629127379fe6)


## IV- Data Discovery

### Recherche et filtrage 

Vous pouvez commencer votre exploration des données à travers l'interface utilisateur de DataHub. 

1- Dans la page d'acceuil, cliquez sur `Explore All`

![image](https://github.com/kplr-training/Data-Strategy/assets/123748177/9298ad88-a542-49f0-87eb-c226bbf893e2)

2- Vous aurez cette interface, à gauche vous avez les différents filtres que vous pouvez appliquer ainsi que en haut vous avez une barre de recherche: 

![image](https://github.com/kplr-training/Data-Strategy/assets/123748177/d5712adb-751f-4caa-be31-6428d492c944)

3- Choissisant par exemple les filtres suivants:

![image](https://github.com/kplr-training/Data-Strategy/assets/123748177/a5f6d9cf-c359-4dce-8585-2b33b6b86e43)


## V- Data profiling 

Supposons qu'on veux examiner de plus près les données, on clique simplement sur l'ensemble de données `Dataset` depuis la liste. Choisissez par exemple le dataset `SampleHiveDataset`.

### Table Profiling

1- La première information qu'on vois est un aperçu du schéma de la table qui affiche les champs, leur type de données et même certains détails du modèle de données tels que les clés primaires et étrangères. En haut (sous le nom de l'ensemble de données), nous voyons également en un coup d'œil qu'il y a actuellement `3.5K lignes et 2 colonnes` dans notre dataset.

![image](https://github.com/kplr-training/Data-Strategy/assets/123748177/2b30361e-2712-4445-abd0-efda009371b5)

2- La deuxième feuille fait référence à la description qui est vide par défaut.

![image](https://github.com/kplr-training/Data-Strategy/assets/123748177/2bcabc91-ab57-4505-abfa-48a9353b06a1)

Ici, les responsables des données peuvent ajouter des connaissances techniques sur cette table dans DataHub et/ou ajouter des liens vers des documents déjà existants. C'est un outil important pour favoriser la maturité de l'architecture des données dans une entreprise - le catalogue de données est aussi utile que les connaissances partagées et saisies par les experts.

### Column Profiling

Pour consulter les informations statistiques de chaque colonne de la table sélectionnée, vous pouvez accéder à la feuille intitulée `Stats`. Cette feuille vous permet de visualiser les données statistiques relatives à chaque colonne.

![image](https://github.com/kplr-training/Data-Strategy/assets/123748177/ba650694-37d4-4824-b666-53fcb4852ad5)

Vous pouvez observer des mesures descriptives telles que le minimum, le maximum et la moyenne, qui sont plus pertinentes dans les tables transactionnelles contenant un grand nombre d'enregistrements. De plus, vous pouvez consulter des valeurs d'exemple pour chaque colonne de votre ensemble de données.


### Liaison entre les entités

Bien sûr, la découverte des données a déjà été instructive et favorise la transparence, surtout si vous n'avez jamais eu l'occasion de découvrir une telle fonctionnalité en pratique. Cependant, la pleine puissance d'un catalogue de données n'est libérée que lorsque nous réunissons le monde de l'informatique et le monde des affaires. 

Le "monde de l'informatique" dans ce sens fait référence à toutes les informations techniques relatives aux ensembles de données. Le "monde des affaires" est ce dont nous avons discuté dans la partie précédente : toutes les informations commerciales que nous gérons dans le glossaire. 

Comment cela fonctionne-t-il avec DataHub ? Dans la capture d'écran ci-dessous, nous voyons plusieurs informations marquées, qui font référence à plusieurs types de liens vers le "monde des affaires" et qui peuvent être utilisés conjointement.

![image](https://github.com/kplr-training/Data-Strategy/assets/123748177/8c7bf795-3098-4940-bede-326f313c5860)

1- Vous pouvez ajouter un terme du glossaire à une colonne de table. Ce lien indique que les données brutes d'un certain terme se trouvent dans cette colonne, par exemple les noms réels des produits.

2- Aussi, ajouter un terme du glossaire à l'ensemble de la table. Ce lien indique qu'un certain terme est plutôt complexe et décrit par plusieurs attributs qui se trouvent dans cette table.

3- Et vous pouvez ajouter un domaine auquel l'ensemble de données appartient. Ce lien est similaire à la liaison des termes du glossaire à un domaine.

4- Finalement, vous avez la possibilité d'ajouter des propriétaires de l'ensemble de données.

## VI- Data Lineage

La data lineage, ou traçabilité des données, est l'ensemble des informations qui permettent de suivre l'origine, les transformations et les mouvements des données tout au long de leur cycle de vie. 

Elle fournit une vue détaillée et historique sur la façon dont les données ont été créées, modifiées, utilisées et propagées à travers différents systèmes, processus et transformations.


Dans DataHub, la data lineage fait référence à la capacité de visualiser et de comprendre les dépendances amont et aval d'une entité de données. Cela signifie que vous pouvez identifier les sources de données qui alimentent une entité spécifique, ainsi que les utilisations ultérieures de cette entité par d'autres entités ou processus. 

- Pour visualiser le lineage de ces données de test, redirigez vous vers la troisième feuille:
  
![image](https://github.com/kplr-training/Data-Strategy/assets/123748177/da62cdf8-7bc5-48d7-973f-c3c5b9c71743)

- Cliquez sur `Visualize lineage`

![image](https://github.com/kplr-training/Data-Strategy/assets/123748177/54e29015-877f-43bb-91ec-120809e6eee8)

- Vous aurez l'interface suivante qui offre une représentation graphique claire et intuitive des dépendances des données. Elle permet de voir les relations entre les différentes entités de données, les flux de données et les transformations effectuées.

![image](https://github.com/kplr-training/Data-Strategy/assets/123748177/53442cc3-c8da-452e-b835-ce4d44155582)

- Vous pouvez cliquer `Show columns` pour visualiser les colonnes des différents datasets:

![image](https://github.com/kplr-training/Data-Strategy/assets/123748177/a659678f-6c4a-4ca2-8e8c-e02d445ecffd)

- En cliquant sur le `+` que vous avez sur les différents bornes, vous pouvez visualiser les relations cachées:

![image](https://github.com/kplr-training/Data-Strategy/assets/123748177/5842021d-8241-488e-a97e-1d63a4b52a36)








