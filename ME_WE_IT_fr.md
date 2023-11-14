# Me-We-It : une norme ouverte pour une IA responsable

Ce document vise à clarifier le processus de construction d’une intelligence artificielle (IA) en dévoilant les étapes qui interviennent dans la création _responsable_ d’une IA.

Il s’agit d’une norme ouverte proposée par des personnes qui ont constaté la valeur que l’IA peut générer et les dégâts qu’elle peut provoquer. Parmi elles se trouvent :

- des spécialistes émérites de la technologie, de la science des données ou de la recherche
- des parties prenantes en première ligne, notamment des développeurs et développeuses
- des utilisateurs et utilisatrices qui se préoccupent des conséquences de l’IA…

Cette norme ouverte a trois objectifs :

1. donner des pistes pour construire une IA plus éthique, afin de permettre au secteur de repartir sur des bases saines
2. aider le public à comprendre le processus de construction d’une IA
3. créer un espace dans lequel le public peut poser librement toutes ses questions à la communauté de l’IA et de la science des données

Elle prendra la forme d’un lieu de discussion en ligne gratuit. Les nouvelles approches et suggestions sont les bienvenues, car elles constituent d’importantes déclarations d’intention.

## Quel est l’intérêt de cette norme ouverte ?

Aujourd’hui, de nombreux discours catastrophistes alimentent l’hystérie ambiante et entretiennent l’opacité des systèmes d’IA. Pourtant, nous avons besoin d’une communication claire et responsable afin d’engager une discussion honnête et de prendre les bonnes décisions.

La création d’une IA implique un travail technique considérable, mais cette norme ouverte permet à chaque personne intéressée de prendre part aux discussions, quel que soit son niveau de connaissance en science des données. Pour cela, cette norme propose un cadre simple pour suivre et valider les approches standard de l’entrainement des machines et les sorties qu’elles produisent.

Il est plus que jamais nécessaire de lever le voile sur la manière dont apprend l’IA. Cette transparence nous permettra de nous tenir mutuellement responsables sans restreindre sévèrement l’innovation.

Le développement d’une IA peut s’accompagner d’avantages considérables :

- une plus grande efficacité
- de meilleures décisions
- des découvertes dans le domaine de la santé
- des solutions à des problèmes que nous n’avions pas les moyens de résoudre jusque-là…

Cependant, une IA peut aussi :

- exposer des modérateurs et modératrices à des contenus horribles
- désavantager les personnes marginalisées
- amplifier les préoccupations en matière de sécurité et de confidentialité des données
- porter atteinte à des droits de propriété intellectuelle (lors de l’utilisation de contenus qui n’ont pas été créés pour l’entrainer)
- perpétuer des biais préjudiciables…

Sans une étude et une planification minutieuses, nous risquons de créer des systèmes d’IA qui aggravent les problèmes que nous cherchons à résoudre.

## Première version de la norme ouverte

Les décideurs et décideuses politiques redoublent d’efforts pour rattraper leur retard en matière de réglementation. Ainsi, la législation sur l’intelligence artificielle de l’UE pourrait bien ajouter l’IA à des fins générales (GPAI, de l’anglais _General Purpose AI_) à la catégorie des systèmes d’IA à haut risque.

En attendant, nous vous proposons une solution pour réduire les silos et mener une discussion de groupe : une norme pratique, que chaque équipe peut utiliser immédiatement et qui clarifie la manière dont l’IA est construite.

Voici la première version (d’une longue série !) que nous proposons aux développeurs et développeuses afin d’évaluer leur travail. Nous pourrons peaufiner cette liste grâce aux questions du public et aux suggestions de la communauté de la science des données. Ces contributions nous aideront à rendre compte des étapes à suivre pour clarifier et valider nos intentions.

Il est peu probable que nous ayons bon sur toute la ligne, d’autant plus avec une technologie qui demande un suivi continu. Mais avec votre aide, chaque nouvelle version apportera des améliorations significatives.

Vous trouverez ci-dessous les premières questions à se poser (selon nous) pour faire en sorte de diffuser des modèles d’IA plus éthiques. Nous encourageons chaque équipe et chaque personne qui construit une IA à s’y référer au quotidien.

Ces questions doivent être posées dans un langage simple et sans jargon pour permettre à tous les publics de comprendre ce processus. Elles seront traduites dans toutes les langues au fur et à mesure que nous trouverons des bénévoles pour nous y aider.

Les questions sont classées de manière à clarifier l’importance de la réduction des silos :

- selon les personnes impliquées dans ce processus : Me (moi), We (nous), It (le modèle) et
- selon les étapes fondamentales de la construction d’une IA (entrainement, construction et tests)

**Me :** les questions que chaque personne qui travaille sur l’IA devrait se poser avant de commencer et au fil du processus.

**We :** les questions à se poser en tant que groupe, notamment pour définir la diversité nécessaire afin de limiter autant que possible les biais humains.

**It :** les questions à poser aux personnes et au groupe en lien avec le modèle en cours de création et les conséquences qu’il peut avoir pour notre monde.

### Étape 1. Entrainement - Sélection et ingestion des données

**Me (moi) :** les questions à me poser avant de commencer cette partie du processus. Je devrais enregistrer mes réponses afin de suivre l’évolution de ma réflexion.

* Quelles sont mes raisons de sélectionner ces données d’entrainement ? En quoi cette sélection est-elle cohérente avec mon intention pour ce modèle ?
* Comment ces données d’entrainement ont-elles été obtenues ?
* Les données d’entrainement contiennent-elles des matériels protégés, comme des œuvres soumises au droit d’auteur, des informations permettant d’identifier des personnes (PII), des données relatives à des cartes de paiement (PCI) ou encore des données de santé protégées (PHI) ?
* Ai-je pris en compte la législation sur la protection des données ou sur la vie privée (comme le RGPD et la loi CPRA) ?
* Ai-je pris en compte d’autres systèmes pour la gestion des sources de données ?
* Ai-je déjà utilisé des données similaires avec des modèles d’IA ou d’apprentissage automatique, ou est-ce la première fois que j’utilise cette source de données ?
* Si j’ai déjà utilisé ces données par le passé, ai-je constaté des problèmes résultant des modèles entrainés à l’aide de ces données ?
* Si j’utilise ces données pour la première fois, quelles sont mes attentes quant à leurs conséquences sur les sorties du modèle ?
* Ai-je utilisé une carte de modèle pour communiquer les risques ? Comment ce document sera-t-il mis à jour avec l’équipe de collaboration ?
* Quel est l’impact espéré des données d’entrainement sur ce modèle ? Quelle est la sortie attendue ? Selon moi, comment ces données affecteront-elles le comportement de ce modèle ?
* Y a-t-il des caractéristiques qui pourraient servir de variables instrumentales (p. ex. des données granulaires au niveau du quartier) pour des populations marginalisées ? Le cas échéant, ai-je mis en place des paramètres de contrôle suffisants pour m’assurer de ne pas perpétuer des biais qui pourraient être appris à partir des données d’entrainement ?
* Puis-je résumer le contenu de ces données d’entrainement de sorte à rendre compte de leur essence d’une manière compréhensible pour les personnes sans connaissance en science de données ?
* Est-ce que je ressens une pression (notamment temporelle) qui m’incite à utiliser des données issues de sources discutables ?
* Suis-je en mesure de citer la source des données d’entrainement ?
* Quels biais pourraient influencer ma sélection de ces données ?
* Ai-je pris en compte les biais qui m’influencent et que je ne comprends pas ? Ai-je partagé ma logique avec un groupe qui peut m’aider à identifier les biais mis en œuvre lors de la sélection des données ?
* Selon moi, en quoi ces données d’entrainement seront-elles bénéfiques à ce modèle ?

**We (nous) :** les questions à nous poser en tant que groupe de travail avant de commencer cette partie du processus. Nous devrions enregistrer nos réponses afin de suivre l’évolution de notre réflexion.

* Quelle est l’intention du groupe derrière l’entrainement de ce modèle ?
* Qui a collaboré à l’élaboration de la stratégie et à la sélection des données d’entrainement ?
* L’équipe qui travaille à la sélection des données d’entrainement est-elle composée de personnes issues de milieux variés et aux expériences diverses afin de contribuer à réduire les biais dans la sélection des données ?
* Quels sont les biais probables inhérents à l’équipe qui a sélectionné les données d’entrainement ?
* Est-ce que chaque membre de l’équipe comprend d’où viennent les données d’entrainement et peut l’expliquer avec ses propres mots ?
* Utilisons-nous une carte de modèle pour communiquer les risques ? Est-ce que chaque contributeur ou contributrice a créé son propre document qui peut être partagé avec l’ensemble de l’équipe ?
* Avons-nous pris en compte la législation sur l’intelligence artificielle de l’UE ou toute autre réglementation proposée ou déjà en place ?
* Les données d’entrainement contiennent-elles des matériels protégés, comme des œuvres soumises au droit d’auteur, des informations permettant d’identifier des personnes (PII), des données relatives à des cartes de paiement (PCI) ou encore des données de santé protégées (PHI) ?
* Avons-nous pris en compte la législation sur la protection des données ou sur la vie privée (comme le RGPD et la loi CPRA) ?
* Avons-nous pris en compte d’autres systèmes pour la gestion des sources de données ?
* Quel pourcentage des données d’entrainement conservons-nous à des fins de test ? Comment sélectionnons-nous les données à conserver ?

**It (lui) :** les questions à nous poser au sujet de l’algorithme ou du modèle avant de commencer cette partie du processus. Nous devrions enregistrer nos réponses afin de suivre l’évolution de notre réflexion.

* Avons-nous des moyens de compenser si une partie de cet ensemble de données se révélait illégale, peu fiable ou inacceptable à l’avenir ?
* Quelles données sont nécessaires à un entrainement réfléchi et conscient ?
* Savons-nous d’où provient l’ensemble de données ? Pouvons-nous expliquer en quoi il consiste ? Est-il bénéfique au modèle ?
* Quels sont les biais probables inhérents aux données ?
* Les données contiennent-elles des informations permettant d’identifier des personnes ou des données protégés, comme des œuvres soumises au droit d’auteur ?
* Suis-je prête ou prêt à assumer la responsabilité du modèle si une partie de l’ensemble de données provoquait des problèmes juridiques à l’avenir ?
* Quelles pourraient être les utilisations ou les conséquences imprévues, y compris les résultats de niveau suivant que les données d’entrainement pourraient enseigner au modèle ?
* Quels biais probables pourraient être amplifiés par l’ajout des données d’entrainement au modèle ?

### Étape 2. Construction - Création ou sélection des algorithmes et des modèles

**Me (moi) :** les questions à me poser avant de commencer cette partie du processus. Je devrais enregistrer mes réponses afin de suivre l’évolution de ma réflexion.

* Quelle est mon intention pour ce modèle ? Quelle est ma raison de l’entrainer ?
* Si j’utilise l’apprentissage par renforcement, comment ce modèle s’optimisera-t-il dans l’environnement de production ? Est-il possible que ma sélection des résultats à tester soit biaisée ?
* Si j’utilise l’apprentissage par transfert, quels biais le processus de transfert pourrait-il dévoiler ?
* Si j’utilise l’apprentissage ensembliste avec des modèles ou des systèmes qui s’entrainent les uns les autres, y a-t-il un risque pour que le système assimile de nouveaux biais ou de mauvaises pratiques de collecte de données ?
* Selon moi, comment se comportera ce modèle ? Puis-je citer quelques exemples de sorties que j’espère obtenir ?
* Quels biais humains ont influencé mes objectifs et mon raisonnement ?
* Si je n’ai pas écrit le modèle de A à Z, d’où vient-il ? Comment a-t-il été entrainé à l’origine ?

**We (nous) :** les questions à nous poser en tant que groupe de travail avant de commencer cette partie du processus. Nous devrions enregistrer nos réponses afin de suivre l’évolution de notre réflexion.

* Avec qui ai-je collaboré à l’entrainement de ce modèle et à l’élaboration de la stratégie ?
* Quels biais humains sont présents dans ce groupe ? Nous sommes-nous demandé si le groupe de travail était assez varié pour prendre en compte des points de vue divergents ?
* Quelles personnes ont collaboré à la construction du modèle et à l’élaboration de la stratégie ?
* Qui sont les parties prenantes ? Sont-elles toutes impliquées dans cette étape du processus ?
* Avons-nous pris en compte la législation sur l’intelligence artificielle de l’UE ou toute autre réglementation proposée ou déjà en place ?
* Ces modèles ont-ils été entrainés à l’aide de matériels protégés, comme des œuvres soumises au droit d’auteur, des informations permettant d’identifier des personnes (PII), des données relatives à des cartes de paiement (PCI) ou encore des données de santé protégées (PHI) ?
* Avons-nous pris en compte la législation sur la protection des données ou sur la vie privée (comme le RGPD et la loi CPRA) ?
* Avons-nous pris en compte d’autres systèmes pour la gestion des sources de données ?

**It (lui) :** les questions à nous poser au sujet de l’algorithme ou du modèle avant de commencer cette partie du processus. Nous devrions enregistrer nos réponses afin de suivre l’évolution de notre réflexion.

* Le modèle a-t-il été développé de A à Z ? Sinon, d’où vient-il ?
* À quoi devrait servir le modèle à l’issue de son entrainement ?
* Si nous n’avons pas créé le modèle nous-mêmes, comprenons-nous l’intention du créateur ou de la créatrice du modèle original ?
* Quelles pourraient être les utilisations ou les conséquences imprévues, y compris les résultats de niveau suivant ?
* Quels biais probables pourraient être amplifiés par le modèle ?
* Avons-nous des exemples de modèles entrainés à l’aide de données similaires et déjà déployés ? Quelles en ont été les conséquences délibérées ou imprévues ?
* Quels sont les dangers potentiels du modèle ? Avons-nous un plan pour les pires scénarios ?
* Quelles mesures de précaution avons-nous mises en place ?
* Qui contrôle le modèle ?
* Comment assurerons-nous la mise en conformité avec les lois et règlements ainsi que le suivi continu de cette conformité ?
* Comment les biais seront-ils découverts et résolus ?
* Comment arrêter le modèle ? Dans quelles circonstances devrait-on le faire ?
* Y a-t-il des parties prenantes intéressées ou des réalités de financement qui pourraient empêcher l’arrêt ?
* Quelles obligations contractuelles dicteront la gestion et l’utilisation de ce modèle ?

### Étape 3. Tests - Gestion des données de test et étiquetage

**Me (moi) :** les questions à me poser avant de commencer cette partie du processus. Je devrais enregistrer mes réponses afin de suivre l’évolution de ma réflexion.

* Les données que j’utilise à des fins de tests sont-elles suffisantes pour analyser le comportement du modèle ?
* Envisageons-nous de faire des tests d’utilisation dans l’environnement de production ? Comment adapterons-nous le modèle si ces tests ont des résultats non souhaités ?
* Selon moi, quelle est la meilleure approche pour évaluer les résultats de ce modèle avant de parler de notre approche avec le reste du groupe ?
* Ai-je l’assurance que l’équipe et moi-même avons conscience des conséquences que pourrait avoir notre travail ? Avons-nous envisagé toutes les conséquences potentiellement négatives qui pourraient résulter de notre travail et pour lesquelles nous devrions faire des tests avant la mise en production ?
* Selon moi, avons-nous fait preuve de suffisamment de rigueur dans notre stratégie et notre déploiement des tests pour nous assurer de faire apparaitre tous les problèmes qui pourraient résulter des sorties du modèle ?
* Les résultats des données d’entrainement et les retours des personnes chargées de l’étiquetage correspondent-ils à mon intention originale pour ce modèle ? Dans le cas contraire, qu’est-ce qui a changé et comment sais-je que cela a changé ?

**We (nous) :** les questions à nous poser en tant que groupe de travail avant de commencer cette partie du processus. Nous devrions enregistrer nos réponses afin de suivre l’évolution de notre réflexion.

* Comment évaluons-nous le comportement et les résultats de ce modèle ?
* Avons-nous conscience de la provenance des données de test ? Les données de test représentent-elles adéquatement les données d’entrainement, compte tenu de leur ampleur ?
* Si les données sont étiquetées par des personnes, de qui s’agit-il ? Ces personnes reçoivent-elles un traitement humain ?
* Avant d’étiqueter les données, les personnes qui s’en sont chargées ont-elles reçu des instructions susceptibles d’influencer leur avis ? Si oui, lesquelles ?
* Quelles questions les personnes chargées de l’étiquetage ou les membres du groupe de travail posent-ils au sujet des données ?
* La stratégie d’étiquetage s’inscrit-elle dans la continuité de la stratégie de sélection des données d’entrainement et de création du modèle ?
* L’équipe d’étiquetage des données présente-t-elle une diversité suffisante ?
* Quels biais humains sont susceptibles d’affecter l’étiquetage ou les tests ?
* Recueillons-nous des données sur les tests d’utilisation dans l’environnement de production ? Si oui, comment seront-elles intégrées à un processus itératif ?
* Le groupe d’utilisateurs et d’utilisatrices est-il constitué d’un public varié représentatif de l’ensemble des futurs utilisateurs et utilisatrices ?
* Est-il possible que des biais résultent de la programmation du modèle ?
* Avec qui avons-nous collaboré à l’élaboration de la stratégie de test ou d’étiquetage des données ?
* Des équipes produits participent-elles à la récupération des données d’utilisation et au partage de la logique humaine avec le reste du groupe ?
* Une fois le modèle testé : le groupe de travail est-il allé au bout de son intention ? (Dans le cas contraire, expliquer pourquoi en détail avec des données quantifiables.)

**It (lui) :** les questions à nous poser au sujet de l’algorithme ou du modèle avant de commencer cette partie du processus. Nous devrions enregistrer nos réponses afin de suivre l’évolution de notre réflexion.

* Les données étiquetées ou les résultats des tests correspondent-ils à notre intention pour les sorties du modèle ?
* Si nous testons nos modèles pour en évaluer l’exactitude, à quel point les résultats constatés correspondent-ils à l’intention fondamentale derrière ce modèle ?
* Allons-nous désormais ajuster le modèle à partir des sorties des données de test ou des données étiquetées ? (Le cas échéant, recommencer le processus à l’Étape 1.)
* En cas d’apprentissage par renforcement, comment les résultats du modèle peuvent-ils amplifier les biais et influencer les nouvelles données des utilisateurs et utilisatrices ?
* Avons-nous évalué les sorties du modèle en tenant compte de la législation sur l’intelligence artificielle de l’UE ou de toute autre réglementation proposée ou déjà en place ?
* Avons-nous effectué des tests pour déterminer si les sorties du modèle contiennent des matériels protégés, comme des œuvres soumises au droit d’auteur, des informations permettant d’identifier des personnes (PII), des données relatives à des cartes de paiement (PCI) ou encore des données de santé protégées (PHI) ?
* Avons-nous pris en compte la législation sur la protection des données ou sur la vie privée (comme le RGPD et la loi CPRA) ?
* Avons-nous pris en compte d’autres systèmes pour la gestion des sources de données ?
