---
layout: "post"
title: "Ça se joue aux interstices"
date: "2019-04-26 20:30"
category: carnet
---

Aujourd'hui s'est tenue la seconde séance du séminaire interne du projet [Revue 2.0](http://revue20.org). Susan Brown a fait une présentation introductive aux web sémantique et aux données liées, dans une approche pédagogique ciblant les éditeurs des revues savantes partenaires du projet. Dans une deuxième partie, Susan a présenté les grandes lignes de l'article _"An Entity By Any Other Name: Linked Open Data as a Basis for a Decentered, Dynamic Scholarly Publishing Ecology"_ ([version anglaise](https://src-online.ca/index.php/src/article/view/212), [version française](https://via.hypothes.is/https://stylo.ecrituresnumeriques.ca/api/v1/htmlArticle/5cc1d219972e5900191acd92?preview=true)), co-écrit avec John Simpson.

Cet article fait le point sur les enjeux du web sémantique pour les données de la recherche et identifie les problématiques à adresser ces prochaines années pour réellement interconnecter les données entre elles.

> Comment alors les données liées peuvent-elles conduire à une meilleure écologie de la publication pour l’érudition et, en particulier, permettre aux publications savantes d’interagir avec les ensembles de données produites par les bibliothèques et les musées, d’une part, et les entreprises de publication officielle, d’autre part, et de les améliorer et de les enrichir&nbsp;? Ici, l’accent sera mis sur plusieurs avantages qui n’épuisent aucune possibilité&nbsp;: 1)&nbsp;l’interconnexion et, au moins au niveau de l’interface, l'intégration des ressources&nbsp;; 2)&nbsp;la mise à disposition d'informations contextuelles et relationnelles comme base pour une environnement riche de connaissances&nbsp;; 3)&nbsp;les boucles de rétroaction qui améliorent la qualité des données, en particulier ceux qui sont fournies par les fournisseurs d'information à grande échelle&nbsp;; et 4)&nbsp;l’incorporation d’une diversité de discours, de méthodologies, et de données y compris des ontologies nuancées et des ensembles de données qui respectent le local et le particulier avec les valeurs aberrantes même si elles peuvent apparaître comme du « bruit » dans de grands ensembles.[^trad]

[^trad]: Traduit de l’anglais par Jasmine Drudge-Willson.

La discussion qui a suivi a permis de soulever plusieurs aspects dont certains résonnent avec mes réflexions récentes. Je ne retiens ici que ces derniers.

## Diversité

L'un des problèmes soulevé par l'interconnexion des données liées est celui d'une double homogénéisation des données&nbsp;: d'une part lors de la conformation des données à des ontologies contrôlées, et d'autre part lors de l'alignement d'une ontologie à l'autre dans un soucis d'interopérabilité. Cette tension entre hétérogénéité et homogénéisation est bien connue. Dans le cas des ontologies et des données sémantiques, le problème est celui de la modélisation, qui impose par principe une réduction du sujet dans un modèle aux propriétés finies et limitées. Cela revient ailleurs à considérer qu'une description ne pourra jamais épuiser son sujet. Le pari de la modélisation est que les données finies et strictement caractérisées peuvent devenir manipulables et calculables, ouvrant alors tout un champs de possible (traitements, statistiques, visualisations) qui ne seraient pas envisageables sans passer par cette simplification de la réalité. C'est à proprement parlé le principe technique du numérique, qui consiste à échantilloner un signal analogique pour le simplifier (le réduire), et le rendre ainsi stockable et manipulable.

L'interconnexion des bases de données sémantiques ajoute alors un degré d'homogénéisation puisque l'alignement d'une ontologie à l'autre vient encore réduire l'expressivité de l'une ou l'autre. Autrement dit, à des fin d'interopérabilité, une donnée richement décrite dans un environnement donné risque très certainement d'être pauvrement "traduite" pour être compréhensible (ou adressable) dans un environnement sémantique plus limité.

Mais revenons à notre idée et à la question posée lors de la discussion&nbsp;: comment assurer une certaine diversité de vocabulaire, de description, mais aussi de modèle&nbsp;? Chaque discipline, chaque laboratoire, chaque producteur de données ne devraient-ils pouvoir développer ses propres modèles pour décrire le monde[^guy]&nbsp;? Peut-on vraiment sacrifier la richesse du langage naturel sur l'autel de la manipulabilité et de l'interopérabilité&nbsp;?

[^guy]: Voir à ce sujet l'article de Jean-Guy Meunier « Humanités numériques ou computationnelles : Enjeux herméneutiques » sur la modélisation des humanités, publié sur [Sens Public](http://www.sens-public.org/article1121.html).

À cette question, Stéphane Poullyau, directeur d'Human-Num et ingénieur du moteur de recherche [Isidore.science](http://isidore.science/), botte en touche. Non, malgré l'enjeu considérable, les algorithmes et les ontologies du moteur de recherche actuel n'adressent pas cette question, «&nbsp;on ne sait pas faire&nbsp;». Isidore, [dans ses récents développements](https://humanum.hypotheses.org/4784), a davantage parié sur l'outillage de la communauté pour valider les informations, les liens générés, les enrichissements proposés par l'algorithme, avec cette idée d'un *"cyber-approval"* sur les données («&nbsp;validées par la communauté&nbsp;»).

## Écologie

L'article de Susan Brown et de John Simpson nous donne une autre piste que je trouve inspirante, celle de l'écologie.

> L'application d'un cadre écologique met l'accent sur [l'idée selon] laquelle toute tentative de modification des communications et des discours scientifiques doit être comprise en termes de diversité et de systématisation, car elle implique de modifier les liens entre les personnes et les conditions matérielles et institutionnelles dans lesquelles elles travaillent.

En considérant ces ensembles de données liées sous l'angle écologique, les auteur·e·s proposent de s'intéresser aux interfaces entre deux écosystèmes distincts, dénommées par Hedge des «&nbsp;écotones&nbsp;»[^hedge]. Ce concept n'est pas sans rappeler la réflexion de Romain Lalande sur la notion de lisière entre deux communautés, qu'il rapproche encore de la créolisation d'Edouard Glissant :

> Ce que produit [cette] mise en relation consciente et inconsciente de deux cultures « valorisées égales ou inégales », c’est ce qu’Edouard Glissant appelle Créolisation. La créolisation se distingue du métissage par l’impossibilité de distinguer les éléments constitutif du tout : les traces des cultures se transforment l’une et l’autre en étant en relation pour proposer une culture nouvelle, libre de toute appartenance atavique.
>
> Avec moins de poésie mais tout autant de justesse, les naturalistes pourraient parlent ici de lisières, qui constituent un espace neutre de relation entre deux écosystèmes, et dont la caractéristique principale est d’abriter une diversité plus riche que la somme des écosystèmes en présences.[^romain]

Il me semble que tout est là lorsque se pose le problème de la diversité au sein des données liées et de leur interconnexion. L'enjeu ne se situe pas nécessairement dans l'expressivité de la description même des données, mais plutôt dans l'interstice de ces jeux de données, à la lisière entre deux écosystèmes, là où les données doivent dialoguer et s'interprêter. Ainsi, la richesse et les particularités qui auraient pu être effacées lors du processus de modélisation et d'alignement pourront à nouveau se manifester, sous une autre forme, déplacées, mais toujours créatrices de diversité.

## Interprétation

Cet interstice, j'avais pu le retrouver aussi dans les écrits de Louise Merzeau, que j'interprêtais alors comme désignant plutôt la distance qui sépare deux fragments de sens associés ensemble pour produire un nouveau fragment de sens. C'est le principe du montage, [l'effet Koulechov](https://fr.wikipedia.org/wiki/Effet_Koulechov), qui identifie la création de sens justement dans ce raccord de plan, raccord qui rapproche autant qu'il marque une séparation, un interstice prolifique, où se loge, il me semble, le principe d'interprétation.

> [Louise Merzeau] invoque ainsi la culture anthologique (Doueihi, 2008) pour préciser la nature particulière de cette glose qui fonctionne par des associations sans cesse reconfigurées à partir de fragments. Mais l’association n’est pas fusion et entre les fragments de sens se loge toujours un espace interstitiel, matérialisant à la fois le rapprochement nécessaire à l’interrogation, et la distance propice à la critique. Finalement, ces interstices sont les lieux mêmes de l’interprétation.[^conversation]

Je reviens alors à mon obsession, celle de la circulation et de l'appropriation. Alors que les auteur·e·s de l'article et la présentation de Susan mettaient l'accent sur la validation des données grâce des boucles de rétroactions (_feedback loop_) permettant de corriger, de créer ou d'enrichir les données sémantiques, je préfèrerais pour ma part parier sur des éditorialisations favorisant les dynamiques de circulation et d'appropriation des données, aussi  pauvres ou erronées soient ces dernières. Ce sont évidemment deux aspects fortement complémentaires et l'un ne peut remplacer l'autre, cependant, il me semble qu'investir sur des dispositifs de conversation sur et avec les données est susceptible de produire davantage de richesse, de diversité et de nouveauté. C'est un peu la stratégie proposée par Isidore.science en ouvrant [un service de veille ou de collection](https://humanum.hypotheses.org/5320), qui rappelle à nouveau la culture anthologique, et l'idée que l'appropriation des ressources embarque toujours une part de réécriture et donc d'interprétation.



[^conversation]: voir l'article [« Design de la conversation scientifique : naissance d’un format éditorial »](https://www.cairn.info/revue-sciences-du-design-2018-2-page-57.htm) dans Sciences du design 2018/2 (n°8).

[^romain]: Voir l'article de Romain Lalande « Les récits des Communs se nourrissent d'ailleurs. De l'importance de cultiver nos lisières » en cours d'écriture et [publié en édition continue](https://via.hypothes.is/https://stylo.ecrituresnumeriques.ca/api/v1/htmlArticle/5bfd580e560a91001754d4f7?preview=true) sur Sens Public dans le cadre du dossier [« Écrire les communs : au devant de l'irréversible »](http://sens-public.org/article1383.html).

[^hedge]: Hegde, Medha. (2012). Ecotones: the transitional zones. Biotech Articles, 12. URL: http://www.biotecharticles.com/Biology-Article/Ecotones-The-Transitional-Zones-2191.html [July 17, 2015].
