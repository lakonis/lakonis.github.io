## Modéliser le réel
&nbsp;

### production ou représentation ?
&nbsp;

<small>Nicolas Sauret<br>-<br>
FRA6730<br>6 décembre 2016</small>



%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
### Suivez le guide

1. Modèle
2. Modèle computationnel
3. Humanités numériques

===
Dans cette présentation, nous allons nous intéresser à la notion de modèle en général, en regardant comment le modèle se positionne par rapport aux concepts qui nous ont intéressé ce semestre. Puis à partir d'un article de JG Meunier, nous allons développer la notion à travers le modèle computationnel et son application aux humanités numériques.


%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%

# Modèle

===
selon notre pratique personnelle des modèles, on peut comprendre le terme de deux manières différentes, voire opposées :

§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§

### Le modèle comme représentation

* le modèle comme objet représentatif d'un autre
* modèle réduit

<div style="display:inline-block; vertical-align:middle; width:50%">
![](http://g01.a.alicdn.com/kf/HTB1kaBRIFXXXXc8XpXXq6xXFXXX2/20-cm-avion-de-passagers-modelB787-8-Air-Canada-B787-8-aircraft-m&eacute;tal-solide-mod&egrave;le-d.jpg)
</div>

<!-- ![](http://i2.cdscdn.com/pdt2/3/6/8/1/700x700/auc0830715102368/rw/air-canada-boeing-777-300-1-200.jpg) -->

===
La plus évidente est de considérer le modèle comme la représentation d'un objet. Le modèle est donc construit à partir du réel, c'est une réduction du réel, on parle de _modèle réduit_, qui vient reproduire le réel, le mimer. Il est du côté de la mimésis au sens le plus basique.

§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§

### Le modèle comme production

* le modèle comme objet à partir duquel on produit des représentations

<div style="display:inline-block; vertical-align:middle; width:50%">
![Modèle WIkipédia](https://upload.wikimedia.org/wikipedia/commons/thumb/a/ac/2009-08-31-akt-muehla-031.jpg/640px-2009-08-31-akt-muehla-031.jpg)
</div>

<small>source: Wikipedia</small>

===
Une deuxième conception considère le modèle comme un objet à partir duquel on va pouvoir produire des représentations. Ici la photo d'un modèle et d'un nu. Mais j'aurais pu mettre aussi un plan d'architecture, à partir duquel les différents corps de métier vont travailler pour réaliser un bâtiment. On peut aussi penser au modèle physique de la gravité qui, exprimé dans une forme mathématique, nous permet de prévoir la trajectoire d'un projectile, ou encore le modèle chimique d'une solution gazeuse qui permet d'effectuer des expérimentations sans même posséder cette solution gazeuse.

Ces différents modèles relèvent finalement d'une production du réel davantage que d'une représentation du réel.

On a donc une dualité de sens, mais ce qui ressort c'est que le modèle semble se positionner comme une instance intermédiaire soit entre le réel et sa représentation, soit entre une intention et sa réalisation dans le réel.

§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§
### Modèle descriptif / modèle prédictif

<!-- * modèle descriptif : du réel vers le modèle
* modèle prédictif : du modèle vers le réel -->

   |_how_|_why_|
--:|:----|:----|
**modèle descriptif** |du réel vers le modèle|représenter des données _historiques_ |
**modèle prédictif** |du modèle vers le réel|déterminer des variables inconnues à partir de données connues|

===
En informatique, cette dualité est connue, puisqu'on distingue les modèles descriptif (du réel vers le modèle) et les modèles prédictifs (du modèle vers le réel).
Dans le premiers cas, il s'agit de représenter des données dites "historiques" : on peut penser comme exemple de modèle descriptif à une carte géographiques ou à une comptabilité, qui est un modèle possible pour décrire les activités d'une entreprise par exemple.

Pour le modèle prédictif, des variables connues, dites « explicatives », vont être utilisées pour déterminer des variables inconnues, dites « à expliquer ». Un exemple typique est le modèle météorologique qui tente de prévoir la météo de demain à partir de la météo d'aujourd'hui.
<!-- Notons que la météorologie est une science entièrement basée sur des modèles, et est donc une discipline ayant beaucoup apporté aux autres disciplines sur la théorie des modèles. -->

Dans les deux cas, **le modèle est une réduction**. C'est la réduction d'un fait, d'un objet, d'une tâche, d'une réalité à modéliser ou à simuler, en une série limitée de paramètres et de relations. C'est donc le résultat d'une sélection des variables, on doit faire un choix sur les éléments à conserver dans le modèle, ceux qui sont pertinents pour notre visée scientifique.

<!-- En fait les deux types de modèles sont liés, puisqu'une bonne prédiction, ou une bonne simulation nécessite de s'appliquer aussi aux données connues, et donc de produire une bonne description. A l'inverse, une bonne description permet de faire un diagnostic et de prendre des décisions, c'est-à-dire faire un pari sur le futur. -->
<!-- §§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§

===
-->
§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§

### Un concept aristotélicien

* δύναμις ou puissance

===
De ce point de vue, le modèle s'inscrit parfaitement dans le paradigme aristotélicien de la mimésis : Aristote considère en effet la poétique comme une organisation sensée du monde, une sélection (qui consiste à écarter les détails non intéressants et à conserver les détails pertinents). C'est finalement une rationalisation du monde.
Mais on peut également appliquer au modèle ce concept de la _dunamis_ (δύναμις), que l'on a abordé en cours. En effet le modèle est "en puissance" puisqu'il est susceptible de génèrer une production du réel.

Et, comme la poésie, le modèle aurait eu, dans la pensée d'Aristote, une valeur en soi, qui ne dépend pas de ce qu'il modélise, qui ne doit pas être valorisé par rapport à ce dont il est le modèle, mais par rapport à ce qu'il permet générer, de produire, de simuler. L'absence de hiérarchie entre réalité et mimesis chez Aristote fonctionnerait ici très bien pour le modèle.


§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§

### Un concept valéryen

<blockquote style="font-size:0.7em;">«&nbsp;Mais ta main, cependant, n’est plus libre d’errer sur le mur ; à présent, « tu veux » quelque chose, et tu imposes à ton tracement cette loi extérieure : qu’il reproduise une forme donnée.<br>
Tu t’obliges à ceci, et même tu as défini cette loi que tu t’es imposée, par ces quelques mots «&nbsp;représenter l’ombre de la tête de Socrate sur une surface plane&nbsp;».<br>
Cette loi n’est pas suffisante pour guider ta main, puisqu’il y faut encore la présence du modèle ; mais elle régit l’ensemble de son action ; elle en fait un tout, qui a sa fin, sa sanction, et ses bornes.&nbsp;»</blockquote>
Paul Valéry, _Eupalinos ou l'architecte_.

===
De même, dans la lignée du séminaire, on peut rapprocher le modèle du mouvement, de l'imaginaire tels que Paul Valéry les pense. Le modèle, comme la fonction géométrique de l'architecte, est de l'ordre du virtuel, de l'écriture du mouvement. Il est source de possibles.

§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§

### Du côté des sciences

<blockquote style="font-size:0.7em">«&nbsp;Le modèle est un objet précieux pour l’acquisition des connaissances, mais aussi pour le dialogue entre scientifiques. Il peut même être un trait d’union entre disciplines. Dans l’activité de recherche, pouvoir le mettre en défaut, pouvoir le réfuter, soit par l’expérience, soit pas les observations est son intérêt premier. C’est lorsqu’il «&nbsp;ne marche pas&nbsp;» qu’on acquiert de la connaissance. Alors, il est loisible de le modifier et de vérifier que la modification est à nouveau en adéquation avec les données. Ainsi se met en place la boucle vertueuse, maintenant bien connue, associant expérimentation ou observation, modélisation et simulation qui permet d’avancer dans le processus d’acquisition des connaissances.&nbsp;»</blockquote>

<p style="font-size:70%;">Pavé Alain, _« La modélisation et la simulation des objets et processus complexes. Questions scientifiques, méthodologiques et éthiques »_, Natures Sciences Sociétés, 2/2005 (Vol. 13).</p>

===
Du côté des sciences, je lirai juste cette citation d'Alain Pavé dans son article _La modélisation et la simulation des objets et processus complexes_.
La citation est assez explicite sur le rôle du modèle dans le champs scientifique, et cela permet une transition vers la seconde partie de l'exposé.

%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%

# Modèle computationnel

Jean-Guy Meunier, _Humanités numériques ou computationnelles : Enjeux herméneutiques_, Sens Public, 2014

===
Je reprends ici l'article de Jean Guy Meunier : Humanités numériques ou computationnelles : Enjeux herméneutiques, publié sur la revue Sens Public en 2014, et dans lequel il détaille ce qu'est un modèle computationnel et comment il peut s'appliquer aux humanités numériques.

§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§

### Humanités computationnelles

* l'ordinateur comme **machine modélisante**

> «Computers are essentially modeling machines, not knowledge jukeboxes»
> <small>Mc Carthy, Willard. Modeling: A Study in Words and Meanings,in SCHREIBMAN Susan, SIEMENS Ray, UNSWORTH John, A Companion to Digital Humanities, Wiley-Blackwell, 2008.</small>

* **médiation épistémique** : outil de perception et instrument de pensée
* modélisation computationnelle


===
Pour JGM, les humanités numériques sont mal nommées, et il préfererait les nommer humanités computationnelles, en considérant que l'ordinateur, la machine numérique, est avant tout une machine de calcul. Il ne rejette pas la dimension culturelle du numérique, mais il considère d'abord le champs scientifique, et insiste ainsi sur ce qu'apporte réellement le numérique aux disciplines, à savoir une **médiation épistémique** opérée par la machine, machine qui est **modélisante**, et qui intervient entre le chercheur et le monde.

Il cite Mc Carthy qui écrit en 2008 : «Computers are essentially modeling machines, not knowledge jukeboxes»

L'ordinateur est donc un outil de perception et un instrument de pensée : perception du monde, ou de l'objet d'étude sur lequel se penche le chercheur, et instrument de pensée, cad vecteur d'interprétation du monde, ou de l'objet d'étude.

Or la machine fonctionne sur la base d'une **modélisation**, qu'on appelle **computationnelle**, terme que l'on va maintenant expliciter un peu...

§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§

### Modélisation computationnelle

1. modélisation intentionnelle (ou représentationnelle)
2. modélisation fonctionnelle
3. modélisation matérielle (ou physique)

===
...sans rentrer dans tous les concepts utilisés, car ils sont parfois très techniques, et que le temps est compté. On pourra préciser au cours de l'exposé tel ou tel terme  selon les besoins.

En fait la modélisation computationnelle fait intervenir 3 modélisations distinctes, qui permettent de passer d'un niveau conceptuel à un autre, et ce de manière transitive.

JGM s'appuie sur les travaux de Dennet(1978), Pylyshyn (1984) et Marr (1982), qui distinguent :
1. la modélisation intentionnelle ou représentationnelle, qui exprime les objets et les tâches à effectuer sur ces objets en utilisant des concepts issus du discours ordinaires. Il s'agit d'une représentation.
2. la modélisation fonctionnelle, traduit ces objets et tâches en termes d'intrants et de fonctions. Ces fonctions devront être computables. (on va y revenir)
3. la modélisation physique ou matérielle, présente les mécanismes de la machine qui réalisent les fonctions physiquement. Dans le cas de l'ordinateur, la matérialité de la machine est bien sûr électronique, mais on parle bien de modélisation physique dans le sens où une machine réalise très concrètement une suite de calcul.


§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§

modèle intentionnel| modèle fonctionnel| modèle physique|
:--|:--|:--
<span style="font-size:0.7em;line-height:0.7em">_«Si donc je te dis de marcher _[de cinq pas]_ en te tenant toujours également distant de deux arbres, tu engendres une de ces figures, pourvu que tu conserves dans ton mouvement cette condition que je t’ai donnée.»_</span> | <span style="font-size:0.7em">f: [0;5]<br>f(x)=x</span>|<p style="font-size:0.5em;line-height:1.2;"> `int walkBetweenTrees(int a, int b){`<br>&nbsp;&nbsp;`  int x, y;`<br>&nbsp;&nbsp;`  for (x = a; x < b; x++){`<br>&nbsp;&nbsp;&nbsp;&nbsp;`    y = x;`<br>&nbsp;&nbsp;&nbsp;&nbsp;`    return y;`<br>&nbsp;&nbsp;`  }`<br>`}`<br><br>`main(){`<br>&nbsp;&nbsp;`  int a = 0, b = 5;`<br>&nbsp;&nbsp;`  walkBetweenTrees(a,b);`<br>`}`</p>

_&nbsp;_
===
Reprenons alors l'exemple de Paul Valéry et voyons ce que donnerait ces trois modélisations :

* une expression du problème en langage socratique, ou valéryen, c'est au choix.
* la traduction du problème en fonction mathématique, c'est ce qui exciterait Valery je crois,
* et finalement la traduction du problème en code informatique, ici du C++, bien évidemment à titre démonstratif, il est probablement très mal foutu, mais c'est simplement pour vous montrer une instance de modélisation informatique.

Pour JGMeunier, toute recherche utilisant l'ordinateur comme machine computationnelle, devrait savoir exprimer ces trois niveaux de modélisation, pour justifier la validité des recherches.

<!-- §§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§

### Numérique

* forme sémiotique d'encodage de configurations électriques

===

<!-- Or, sachant que pour rendre compte du véritable modèle physique de la machine, il faudrait descendre encore dans des niveaux de langage, et "parler physiquement à la machine", en exprimant notre problème en _langage machine_ par exemple.
On pourra considérer ici que le C++ est un langage suffisamment bas niveau pour sentir la matérialité de la machine.

La question que pose ensuite JGM, c'est "Où se trouve le numérique dans ces modélisations ?"

Pas dans le modèle représentationnel, ni à vrai dire dans le modèle physique, car il faut ici prendre conscience de ce que manipule réellement la machine : des impulsions électriques, cad un courant qui passe ou qui ne passe pas. Le code informatique lorsqu'il est compilé produit un code en langage machine qui est lui-même traduit en impulsions électriques. Pas de numérique au sens propre du terme.

Et c'est finalement dans le modèle fonctionnel, cad aussi dans le modèle computationnel, qu’apparaît le numérique. JGM introduit ici le numérique comme ne désignant rien d'autre qu'une **forme sémiotique d'encodage de deux configurations électriques** (passe/passe pas) : forme sémiotique qui repose sur deux symboles : 0 et 1.

La combinaison de ces symboles permettent des expressions de plus en plus complexes, basés sur des systèmes d'encodage numérique, ici au sens où on l'entend le plus souvent : des chiffres pour encoder des éléments plus complexes.

Autre élément soulevé par JGM : ce n'est pas parce qu'on a pu encoder des objets, des discours, des fonctions, en numérique, qu'ils sont rendus computable. -->

§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§

### Computationnel

* calculabilité : manipulation formelle de symboles (sans signification) :
  <i class="fa fa-arrow-right"></i> déterminer si une équation appartient ou pas à une système mathématique.

* fonction computationnelle :
  * doit être récursive, algorithmique et combinatoire
  * soit 3 propriétés nécessaire : atomicité, systématicité et productivité


===
Il détaille ensuite ce qu'on entend par computation, ce qu'est la computationnalité, qu'il relie à la calculabilité, qui est une **manipulation formelle de symboles** (sans signification) qui consiste à déterminer si une équation appartient ou pas à un système mathématique.

L'équivalence entre calculabilité et computationnalité, c'est la machine de Turing qui la fait : Turing a montré qu'une fonction calculable était computationnel dans une machine physique mécanique, la machine de Turing. L'ordinateur étant une instanciation de la machine de Turing dans une machine électronique.

Une fonction pour être computationnelle doit être récursive, algorithmique et combinatoire, ou comme l'exprime d'autres sources, doivent posséder ces 3 propriétés : atomicité, systématicité et productivité.
Je vous passe les détails.

Or une fonction possédant ces trois propriétés est de fait un **système formel**, avec pour conséquence que ces fonctions computables sont de nature essentiellement **syntaxique** : cad que la sémantique des fonctions leur sont externe. Autrement dit, le calcul peut être effectué par une machine, mais son interprétation n'est pas possible par la machine. La machine ne comprend pas de quoi on parle.

Ainsi, on retiendra que même si on fournit à la machine des 0 et des 1 pour exprimer un objet ou une fonction, cela ne suffit pas à rendre ces fonctions computationnelles. Être numérique n'est pas une condition nécessaire ni suffisante de la computationnalité.

En fait en mathématique, il existe une infinité de fonctions non computables, ou non calculable, tandis qu'il existe un sous-ensemble de fonctions computables très restreints au regard de l'ensemble des fonctions.

Et pour revenir au numérique, le numérique est avant tout une représentation sémiotique, c'est-à-dire un encodage formel. Un système numérique n'est pas nécessairement un système computationnel.

%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%

# Humanités numériques

§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§

### Modélisation des humanités ?

===
La question que se pose ensuite JGM, est de savoir si la modélisation des problèmes de recherche spécifiques aux humanités permet d'aboutir à des modèles computationnels.

A nouveau, il s'agit de procéder aux trois modélisations en exprimant successivement les objets de recherche et les opérations de recherche dans ces modélisations.
Il faut donc se poser les questions comme Quels sont les entités à manipuler, quels objets, quels faits, quelles tâches et quelle succession de tâches permettent de traiter ces entités et d'aboutir à un résultat ?

La modélisation représentationnelles peut relativement bien se passer, mais c'est la traduction dans le modèle fonctionnel qui peut potentiellement poser problème, cad pourrait aboutir à l'expression de fonction ne remplissant pas toutes les propriétés d'une fonction computable, à savoir : l'atomicité, la systématicité, la productivité.

#### entités/atomes
Donc si on regarde d'un peu plus près, notamment la question de l'atomicité : est ce qu'il est possible d'identifier des unités qui permettent d'approcher l'atomicité ? peut-on discrétiser nos objets de recherche en des formes facilement manipulable par la machine ?

Par exemple, en musique, on peut décomposer un morceau en _note_, en _portée_, en _mesure_, en _pièce_, en _compositeur_, etc. En littérature, on peut penser à des unités comme : le _mot_, la _ligne_, le _chapitre_, l'_auteur_, le _livre_, etc.

Jusque-là tout va bien. Nous avons une modélisation du texte où l'on sait isoler les mots, les lettres, etc., et cette modélisation est applicable à tout texte, c'est donc un premier pas vers un modèle, et vers la  manipulabilité.

#### fonctions
On pourra aussi identifier des tâches élémentaires qui pourront être traduites en fonctions computationnelles : copier, imprimer, paginer, indexer un texte, compter les mots, etc.

Tout cela est déjà bien intégré dans nos machines et dans nos logiciels, au point que ces éléments nous sont devenus transparents. Les modèles utilisés vont même beaucoup plus loin, puisqu'il existe des modèles grammaticaux de texte pour les différentes langues, qui permettent ensuite au logiciel de nous proposer des corrections orthographiques, typographiques et même syntaxiques.


<!-- #### Edition savante
On peut même complexifier, comme le font les éditions savantes, cette fois-ci en enrichissant le texte d'une couche d'information : on peut indiquer à la machine de quels types sont les mots (verbe, nom, pronom, féminin, masculin, pluriel, passé composé, etc.) où même faire des indications d'ordre analytique (racine du mot, désambiguation, etc.), de manière à envisager des requêtes plus complexes, jusqu'à produire des requêtes dont la résolution peut s'avérer extrêment complexe pour l'homme : [exemple].

Et pourtant, aussi complexe et fastidieux soit le calcul demandé, vous pouvez être certains que la requête elle-même est relativement simple, car elle relève d'un problème et d'une résolution syntaxique, qui ne peut concurrencer le niveau sémantique des humains.

Et cette opération d'enrichissement du texte revient en fait à le projeter sur un plan unique, ou sur plusieurs plans, mais le résultat est le même : cette projection ou ces projections sont des réductions du texte. C'est un enrichissement du point de vue de la machine, qui passe de symboles indifférenciés à des symboles différenciées, mais c'est clairement un appauvrissement du point de vue humain.

Quel bénéfice alors ? La force d'un tel protocole est de pouvoir associer à l'objet d'étude un modèle computationnel que la machine saura manipuler. Par ailleurs, je vais pouvoir recycler ce modèle sur n'importe quel texte. Et donc augmenter les capacités de traitement en travaillant sur des corpus beaucoup plus grand.

Oui, mais à quoi cela sert si les requêtes, ne fonctionnent que sur des modèles réduits, et sont par ailleurs relativement simples, et même carrément simpliste au regard de mon problème de recherche ? -->

§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§

### Sémioticité

Les objets de recherche en HN sont de nature sémiotique :
* pas atomisable
* pas réductibles à des fonctions
* multiplicité des représentations


===
Et pourtant, on est encore loin des tâches qui intéressent les chercheurs en humanités. Ces tâches là sont autrement plus complexes. Meunier nous en donne quelques exemples :

* l'identification d'un style musical
* la chorégraphie d'une danse, la formation des concepts, l'évolution de thèmes, la structure narrative, les liaisons intertextuelles, les tendances architecturales, les conditions de production de discours, les structures argumentatives, la production d'une toile, la transmission des mêmes, etc.

Ces objets et ces processus sont ils exprimables en un modèle computationnel ? Est ce que les fonctions qui permettraient de les exprimer sont calculables, sont computables ?

#### Atomicité
Les difficultés surviennent très vite, car on se rend compte que les entités qui intéressent les humanités sont de **nature sémiotique** : c'est-à-dire que leur qualité première **n'est pas d'être dénombrable** ou quantifiable, mais c'est d'avoir **un sens** ou **une signification**.

Or on a vu que les fonctions pour être computationelles sont nécessairement d'ordre syntaxique.

Le problème est à double sens :
* soit on atomise les objets, c'est-à-dire qu'on les déconstruit, on les discrétise en un grand nombre d'unités discrètes, mais alors on perdra leur sémioticité.
* Soit au contraire, si on tente de conserver la sémioticité, mais dans ce cas, on perdra l'atomicité nécessaire pour les rendre admissibles par des fonctions computationnelles.

<!-- #### Syntaxique
Un autre problème est le caractère purement syntaxique des fonctions dites computationnelles. A nouveau ici, la sémantique ou la signification échappera à la machine. -->

#### Multiplicité des modèles
Par ailleurs, JGMeunier montre qu'un même fait ou situation complexe peut être exprimé dans de multiples modélisations représentationnelles. Je n'ai pas le temps malheurusement de développer ses exemples, mais il montre par exemple qu'un groupe de personnes tapant dans leurs mains de manière frénétique ne sera pas modélisé de la même manière par un sociologue, un ethnologue ou un anthropologue. Et du coup ces modèles représentationnels refléteront les disciplines et les cultures des chercheurs, affectant d'autant les résultats d'une éventuelle computation, et probablement par la suite l'évaluation des résultats.

§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§
### Commentaire sur l'article

===
JGMeunier semble déplorer cette multiplicité des modèles en HN, multiplicité nécessaire du fait de la sémioticité des objets et de la  complexité des tâches. Il déplore par exemple que les modèles soient traversés de choix théoriques, de choix culturels, etc. qui viendraient affecter les résultats..

Mais il vrai que cela ne permet pas à un modèle d'être réellement un modèle, cad transposable à d'autres questions de recherche, à d'autres corpus, etc. On a vu avec la citation d'Alain Pavé qu'effectivement les modèles en science étant central pour la discussion scientifique, multiplier les modèles en en produisant un pour chaque objet d'étude d'une part, et d'autre part en en produisant un par chercheur, revient effectivement à tuer le modèle. Trop de modèles, tue le modèle.

Et pourtant, intuitivement, on sent bien qu'il est indispensable tant pour les humanités numériques que pour les humanités pré-numériques, d'exprimer une subjectivité, de conserver une singularité.

JGMeunier en fait cherche à avertir les chercheurs et à les sensibiliser au rôle central de la computation pour les recherches qui se réclament des humanités numériques, davantage que de la numérisation pure et simple des corpus.

Sans l'exprimer directement, mais dans le sens de la nécessité de la subjectivité, il conclut tout de même son article en disant que l'ordinateur doit se positionner correctement dans la chaine des opérations interprétatives réalisées par les chercheurs en humanités. C'est à peu près la même chose, c'est-à-dire que tout résultat d'une computation, d'un modèle, n'est qu'un résultat de calcul, et qu'il reste à interprêter pour acquérir une valeur scientifique du point de vue des humanités. Le résultat syntaxique des calculs restent une représentation ou une simulation du modèle, une "vue de l'ordinateur", qui faut interprêter pour produire une "vue de l'esprit". Et cette interprétation doit bien évidemment intégrer les biais culturels, les choix et les sélections du modèle.

Cette interprétation des résultats revient en fait à la maïeutique qui permet de décrire souvent le travail du chercheur sur des données informatiques. On parle de dialogue entre le corpus et le chercheur, entre le monde et le chercheur, à travers la médiation de l'ordinateur.

Pour revenir au modèle, l'ordinateur vient assister le chercheur dans la manipulation du modèle du corpus, mais non dans l'interprétation, ni du modèle ni de ses résultats.

§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§

### Oracle

===
Pour terminer, je voudrais introduire un autre agent dans l'équation et qui intervient dans ce dialogue corpus/chercheur :

Turing avait anticipé sur ces fonctions non computables et avait proposé comme solution d'avoir recours à des Oracles qu'il n'a pas véritablement définis, mais que plusieurs sources interprêtent aujourd'hui comme étant le Web, ou de manière plus locales dans des systèmes d'informations donnés, comme étant les ontologies. En informatiques, les ontologies sont du vocabulaire contrôlé, contenant la sémantique d'un métier, d'un domaine, d'un champs de recherche par exemple. Elles sont du savoir en boite que les machines peuvent interroger à souhait lorsque la sémantique des objets manipulés leur échappe. La machine, sans véritable conscience ou compréhension, est tout de même capable d'associer des éléments sémantiques avec des résultats syntaxiques, facilitant leur interprétation.
