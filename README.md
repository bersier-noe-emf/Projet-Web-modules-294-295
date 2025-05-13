# Documentations Projet 294-295


La documentation de votre projet doit être rédigée dans le Þchier README.md de votre dépôt GitHub. 
Toutes les captures d’écran et illustrations doivent être placées dans un dossier /documentation
dédié. Votre travail doit suivre la structure déÞnie par la table des matières fournie (les indications en 
bleu sont à supprimer).
Il est fortement recommandé d’enrichir votre documentation avec des illustrations et des captures 
d’écran. Cependant, il est essentiel d’accompagner chaque image d’une explication claire, même 
brève, aÞn de mettre en évidence les éléments pertinents et de faciliter la compréhension de votre projet.
Le diagramme d’activité et le diagramme d’interaction concerneront le même use case et il ne s’agira 
ni du use case « login » ni du use case « logout ».
## Introduction

Vous présentez ici votre projet de façon générale et détaillée. Vous expliquez l'objectif général de 
votre application et expliquez également, de façon plus détaillée, ce que votre application permet 
de faire.
## Analyse

### Diagramme de cas d'utilisation

Vous intégrez ici un diagramme des cas d'utilisation. Le diagramme doit contenir des acteurs 
et les actions disponibles dans votre application. 
Chaque acteur et chaque cas est décrit brièvement pour permettre une compréhension claire 
du diagramme.
### Maquettes
A l'aide de l'outil de votre choix, vous créez les maquettes des différents écrans disponibles 
dans votre application. Les maquettes doivent permettre d'identiÞer les éléments que votre 
interface aura et leur disposition. 
Vous expliquez brièvement chaque maquette et mettez en avant les éléments pertinents de 
vos différents écrans. 
### Diagramme d'activité
Le diagramme d’activité est un schéma UML qui vous permet de représenter le déroulement 
logique d’un processus sous forme de séquence d’actions, de conditions et de décisions. Pour 
ce projet, vous devez modéliser les principaux flux liés aux cas d’utilisation (par exemple : 
connexion, ajout de données, afÞchage). Chaque diagramme doit montrer clairement les 
étapes, les choix possibles et, si nécessaire, les traitements parallèles. Cela vous aidera à 
visualiser et structurer le fonctionnement de votre application, côté client et/ou serveur.
Par conséquent, on verra clairement dans ce diagramme les activités exécutées côté client et 
les activités exécutées côté serveur. Les deux systèmes (client / serveur) seront identiÞables 
avec un encadré dans le diagramme.
### Diagramme ER
Le diagramme entité-relation (ER) vous permet de représenter les entités principales de votre 
base de données ainsi que les relations entre elles, sans entrer dans le détail des attributs. 
Vous devez l’utiliser pour donner une vue d’ensemble des données gérées par votre 
application et des liens logiques qui les relient (ex. : un utilisateur passe plusieurs commandes). 
Chaque entité doit être nommée clairement, et les relations doivent être représentées avec 
leurs cardinalités. Ce diagramme vous aide à structurer votre base de données avant de passer 
à sa création technique. 
## Conception
### Diagramme de classes client

Insérez ici le diagramme de classe de votre client. Le diagramme doit contenir les différentes 
classes de votre structure MVC avec les méthodes à implémenter. 
### Diagramme de classes serveur
Le diagramme de classes serveur vous permet de représenter l’organisation logique de votre 
code côté Node.js, même si vous n’utilisez pas de classes au sens strict. Vous devez y faire 
apparaître la séparation en couches selon le modèle MVC : les routes (vue) qui reçoivent les 
requêtes, les contrôleurs (avec les éventuels middlewares) qui traitent la logique métier, et les 
services ou modèles qui accèdent à la base de données. Ce diagramme doit illustrer les 
responsabilités de chaque Þchier ou module et leurs relations. Il vous aide à structurer 
clairement votre application serveur avant ou pendant le développement. 
### Diagramme d'interaction
Le diagramme d’interaction vous permet de représenter les échanges entre les différentes 
parties de votre application, côté client et serveur. Vous devez y faire Þgurer les objets côté 
client (vue HTML, contrôleurs JavaScript, services côté client) ainsi que ceux du serveur 
(routes, middlewares, contrôleurs, services). Le diagramme montre le séquencement des 
appels et les interactions entre les objets lors du traitement d’un cas d’utilisation (ex. : envoi 
d’un formulaire, récupération de données). Il vous aide à visualiser le parcours complet d’une 
requête, du navigateur jusqu’à la base de données et retour.
### Schéma relationnel
Le diagramme relationnel peut être réalisé grâce à Workbench. Le diagramme relationnel 
présente la structure concrète de votre base de données, des tables et des champs qu'elle 
contient ainsi que la relation entre les différentes tables.
### Conception des tests
Vous décrivez ici les différents tests qui seront exécutés lorsque l'application sera terminée. 
Mettez cela sous forme de tableau avec une description des éléments testés, le résultat 
attendu.
## Réalisation
### Descente de code
Vous décrivez et expliquez une action réalisable dans votre application. Vous pouvez 
notamment prendre un des cas de votre diagramme des cas d'utilisation. Vous expliquez toutes 
les étapes du client jusqu'au serveur et la base de données ainsi que le retour vers le client. 
Vos explications contiennent des extraits de codes pertinents – il ne sert surtout à rien de 
mettre tout le code dans votre rapport !
Utilisez la Markdown pour vos extraits de code.
Côté client, la descente de code illustre les différents éléments de la structure MVC de votre 
application, les éléments de l'interface, les différents événements, la validation des données et 
leurs transmissions à la partie serveur.
Pour le serveur, la descente de code doit illustrer : les routes, la méthode http utilisée, les 
codes de retours, la vériÞcation du token JWT, l'accès à la base de données, la validation des 
données côté serveur.
### Différence entre la conception et l’implémentation
Durant l’implémentation, il est probable que vous fassiez des choix différents de ce que vous 
aviez imaginez durant la conception. Il s’agit ici d’identiÞer et d’expliquer ces différences. 
### Problèmes rencontrés
Vous listez et décrivez ici les problèmes que vous avez rencontrés ainsi que ce qui a été fait 
pour solutionner ces problèmes.

## Réalisation des tests
Vous reportez ici le tableau établi au point 3.5 Conception des tests et vous y mettez les résultats. 
Vous expliquez les éventuelles erreurs. 
## Conclusion
Dans la conclusion du rapport, vous devez faire une synthèse claire et honnête de votre projet. 
Commencez par résumer ce qui a été réalisé, en précisant les fonctionnalités développées, ce qui 
fonctionne correctement, et ce qui ne fonctionne pas ou est encore en cours. Mentionnez 
également les éventuels éléments manquants ou partiellement aboutis.
Prenez ensuite du recul pour analyser l’ensemble du travail effectué : ce que vous avez appris, les 
compétences techniques et organisationnelles développées, et les difÞcultés rencontrées.
EnÞn, mettez en avant les points positifs du projet (organisation, collaboration, qualité du code, etc.) 
et identiÞez les points à améliorer, que ce soit dans la méthode de travail, la gestion du temps ou 
les choix techniques. L’objectif est de