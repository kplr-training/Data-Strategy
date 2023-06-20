# DataHub pour la gouvernance des données

DataHub est une plateforme open-source développée par LinkedIn pour la gestion des métadonnées et la collaboration autour des données. C'est un outil conçu pour aider les organisations à découvrir, à comprendre et à gérer leurs actifs de données. 

DataHub permet de cataloguer les données, de suivre leur origine et leur évolution, de faciliter la collaboration entre les équipes travaillant sur les données et de fournir des fonctionnalités de recherche et de découverte des données. Il vise à améliorer la gouvernance des données, à garantir la qualité des données et à faciliter l'accès et l'utilisation des données au sein de l'organisation. DataHub est extensible et peut être intégré à d'autres outils et technologies de gestion des données.


## Interface de DataHub 

Pour accèder à l'interface de démonstration de DataHub pour tester l'outil, vous pouvez taper l'adresse suivante dans votre navigateur:

https://demo.datahubproject.io

Vous aurez l'interface suivante :

![image](https://github.com/kplr-training/Data-Strategy/assets/123748177/869fb051-484a-4d1e-9948-dd255962229e)

## La conception d'un glossaire

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

#### Exemple :

Prenons l'exemple suivant : nous voulons avoir un processus métier (groupe de termes) "Approvisionnement en équipements" qui contient tous les termes liés à l'approvisionnement en équipements (par exemple, nom de l'équipement, fabricant de l'équipement, équipement lui-même). Ces termes appartiennent au domaine "Fabrication". Cela peut être fait dans DataHub de la manière suivante :

1- Dans le menu `Govern`, choisissez `Domains`: 

![image](https://github.com/kplr-training/Data-Strategy/assets/123748177/4af1e38a-54cf-4ee2-8333-fae537fd02ba)

2- Maintenant, créez le domaine `Manufacturing`.

![image](https://github.com/kplr-training/Data-Strategy/assets/123748177/cdefc9c8-e32a-408a-bee4-5fd08ca28104)

3- Revenez dans le menu `Govern`, choisissez `Glossery`: 

![image](https://github.com/kplr-training/Data-Strategy/assets/123748177/1c2c3739-1df2-4a1c-b33f-28922d35afde)

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



