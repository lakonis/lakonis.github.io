---
layout: post
title: Communauté de savoir et réseau de fragments
date: '2017-03-21 00:11'
category: carnet
---

Il est toujours réconfortant de voir qu'un travail passé retrouve une actualité, à fortiori quand l'actualité participe de l'avancée de la thèse. Ici, il s'agit de mon intervention [aux journées d'études «&nbsp;Editorialisation et nouvelles formes de publication&nbsp;»](http://editorialisation.org/), organisées à l'Université de Montréal en avril 2015. Ces journées font d'autant plus écho aujourd'hui qu'elles ont motivé ma toute première venue à Montréal, et m'entraînaient avant l'heure dans le statut de doctorant.

L'intervention s'intitulait _«&nbsp;Vers un framework pour la circulation des connaissances&nbsp;»_ et articulait deux parties :

* l'étude de cas de l'outil d'annotation [Hypothes.is](https://hypothes.is/), qui faisait ses premiers pas à l'époque,
* et une exploration plus théorique sur les formes réticulaires que laissaient entrevoir les annotations web.

<iframe src="http://nicolassauret.net/s_circulationFramework/"  style="width:100%;height:30vw;border:none;"></iframe>

<a class="btn btn-default btn-sm" href="http://nicolassauret.net/s_circulationFramework/" title="Intervention «Vers un framework pour la circulation des connaissances»">
<i class="fa fa-eye"></i> Ouvrir les slides
</a>

L'intervention revient au goût du jour pour trois raisons :

1. d'une part le W3C a finalement publié le 23 février 2017 [ses recommandations pour l'annotation sur le web](https://www.w3.org/blog/news/archives/6156), à partir des travaux de [l'Open Annotation Community Group](http://www.w3.org/community/openannotation/).
2. d'autre part, l'outil Hypothes.is est préssenti pour implémenter l'annotation et la discussion dans le cadre de la refonte de la revue Sens Public,
3. enfin, parmi [les 5 axes envisagés](https://github.com/EcrituresNumeriques/sensPublicApp/blob/master/doc/cahiersDesCharges.md) dans cette refonte, l'axe «&nbsp;Connecter&nbsp;» rappelle fortement les principes que j'identifiais dans la modélisation des réseaux de pairs.

Voici comment se posait la question :

> Pour les lieux et les institutions de savoir, organiser la circulation de ses ressources ne consiste plus seulement à y donner accès, il s'agit désormais d'en organiser la réappropriation.
Cela nécessite de repenser la médiation des ressources dans le sens d'un élargissement de la communauté scientifique à d'autres communautés de savoir, ou autrement dit à organiser la porosité entre réseaux de pairs.
C'est certes une question de Knowledge Design, mais aussi une question de Design de communauté, ou encore de la visibilité des pairs, qui est un des aspects parmi d'autres.
>
> La question qui se pose alors : comment les dispositifs d'éditorialisation organisent ces réseaux, comment modélisent-ils et structurent-ils les interrelations entre ses acteurs ?

En repartant de la modélisation d'une annotation Hypothes.is en quatre objets : des ressources web, des annotations, des tags et des contributeurs, on pouvait inférer plusieurs types de relations entre pairs, constitutives de réseaux de pairs&nbsp;:

> ![Réseaux de pairs]({{ site.github.url }}/img/reseauDePairs.png)
>
> * **une relation forte entre des contributeurs** ayant annoté le même document. Il s'agit d'une relation spatiale, presque physique, où le document fait lieu, un lieu de rencontre, et de collaboration. Ses deux contributeurs ont en quelque sorte occupé temporairement le même espace, de manière synchrone ou asynchrone. Sans parler encore de communauté sur un même document, on peut identifier un groupe doué d'une motivation commune, celle de faire la lecture de ce document, dont les intentions sont diverses et peuvent potentiellement se croiser.  
On retrouve l'intimité instrumentale du modèle de blackboard ou tableau auquel Michel Gensollen rattache la contribution sur Amazon ou les communautés P2P ou de logiciel libre. Le principe est de laisser une trace visible et partagée aux futurs lecteurs.
> * **une relation directe entre des contributeurs** se répondant les uns les autres, dont un sous-type serait **le lien entre le contributeur et l'auteur** du document initial. Je n'ai pas représenté l'auteur du document sur la modélisation précédente, mais il est évidemment essentiel pour le sujet qui nous intéresse aujourd'hui.
> * une relation plus faible mais puissante, inférée à partir **d'un même tag employé** par plusieurs contributeurs. Le lien est alors sémantique, le document s'efface au profit de la thématique, la rencontre est plus aléatoire, le lien est transversal, comme les chemins de navigation qu'il peut générer. il peut créer des accidents, des non-sens ou des associations heureuses.
> * d'autres relations peuvent encore exister, sur la base **de collections d'annotations par exemple constituées éditorialement**.

La modélisation des communautés de savoirs en réseaux de pairs peut paraître réductrice, tant ces communautés sont avant tout construites sur des dynamiques de partage, d'échange, de pratiques sociales qui vont au-delà des objets se référençant les uns les autres (textes, annotations, bibliographies).

> ![Réseaux de ressources]({{ site.github.url }}/img/reseauDeRessources.png)

Malgré tout, il y a dans cette modélisation une ouverture possible vers un modèle épistémologique renouvellé. Toujours basé sur l'écrit et la référence comme [condition du socle commun de connaissance]({{ site.github.url }}{% post_url 2017-03-08-entretien-avec-gerard-wormser-revue-et-modele-epistemologique %}), ce modèle reposerait sur une granularité plus fine des textes référencés et sur la fluidification de la circulation, tant des textes référencés que des annotations. En effet, avec l’acquisition d'une URI propre, l'annotation se libère du texte qu'elle adresse et accède à une indépendance propice à de nouvelles éditorialisations et donc à sa circulation et son appropriation. Dans ce nouveau paradigme de l'annotation, il n'est plus pertinent de distinguer le texte annoté et l'annotation dans un rapport hiérarchique classique où le texte discuté conserverait une supériorité de valeur, ou une autorité sur la discussion. Ils seraient plutôt à distinguer dans un seul rapport temporel, l'une venant nécessairement après l'autre.

Parmi les différents types de relations citées, celle de collections d'annotations éditorialisées fait également écho à [l'axe «&nbsp;Collectionner&nbsp;»](https://github.com/EcrituresNumeriques/sensPublicApp/blob/master/doc/cahiersDesCharges.md#axe-4--collectionner) de la refonte de la revue Sens Public. Il s'agit en effet :

> de créer des collections d'élements qui pourront être soit des fragments d'articles, soit des annotations (propres ou appartenant à d'autres utilisateurs). Cet axe fait se croiser deux contributions théoriques, celle d'anthologie de Milad Doueihi et celle de cristal de connaissance, «crystal of knowledge» de JC. Guédon[^guedon].
>
> Si la collection ne relève pas de la production d'un texte nouveau, elle relève bien malgré tout d'une démarche critique dans la mesure où le lecteur construit sa propre interprétation d'un champs ou d'un concept, en y agrégeant des éléments de connaissances glânés au fil de ses lectures. C'est l'association de ces éléments qui est herméneutique, au sens où il construit du sens. On pourrait envisager que ces collections puissent être soit publiques, soit privées, selon la volonté du collectionneur.

[^guedon]: Stern, Niels, Jean-Claude Guédon et Thomas Wiben Jensen. « Crystals of Knowledge Production. An Intercontinental Conversation about Open Science and the Humanities ». Nordic Perspectives on Open Science 1, no 0 (23 octobre 2015), 1‑24. doi:10.7557/11.3619.

Le W3C accompagne ses recommandations pour l'annotation du web par un diagramme très proche de ce que j'imaginais à partir des interfaces proposées en 2015 par Hypothes.is. Cela n'est pas un hasard puisque [l'équipe d'Hypothes.is a été très impliquée](https://hypothes.is/blog/annotation-is-now-a-web-standard/) dans l'Open Annotation Community Group et qu'ils ont largement contribué à la mise en place du standard et à une première implémentation avec la librairie [Annotator.js](http://annotatorjs.org/) de Nick Stenning.

<iframe src="http://www.w3.org/annotation/diagrams/annotation-architecture.svg"></iframe> [Ouvrir en plein écran](http://www.w3.org/annotation/diagrams/annotation-architecture.svg)
