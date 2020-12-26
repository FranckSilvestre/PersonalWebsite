---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Enseignement à distance en mode synchrone - Problèmes et éléments de solution"
subtitle: ""
summary: ""
authors: [admin]
tags: [REX, enseignement à distance, teaching design pattern, elaastic]
categories: [IUT Rodez, enseignement à distance]
date: 2020-12-24T14:04:27+01:00
lastmod: 2020-12-24T14:04:27+01:00
featured: false
draft: true

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
---

Depuis le mois de novembre, les étudiant.e.s de l'IUT de Rodez, comme beaucoup d'étudiant.e.s en France et ailleurs, se retrouvent, une fois de plus, à suivre les cours à distance. 
Les emplois du temps, à tord ou à raison, n'ont pas été modifiés. Les étudiants et enseignants se retrouvent donc à heure fixe, conformément aux horaires prévus dans l'emploi du temps, pour des sessions de visioconférences.
Ce billet présente un retour d'expérience, de mon expérience (ceci n'est pas un article scientifique !), du point de vue de l'enseignant en informatique que je suis, ayant à dispenser l'ensemble de mes enseignements à distance, dans le contexte exposé.

Le parti-pris de ce retour d'expérience est une présentation de deux problèmes rencontrés suivi d'une tentative de réponse à chacun de ses problèmes. La  structure des points abordés s'inspire de l'approche [*Design Pattern*](https://fr.wikipedia.org/wiki/Patron_de_conception) adaptée pour l'enseignement. 

## Problème n°1 - Le manque d'attention et d'engagement à distance ne se détecte pas facilement

#### Le problème

Pendant que je présente une notion, un nouveau concept, une procédure, etc. via la plateforme de visio-conférence institutionnelle, la plupart des étudiant.e.s sont connecté.e.s en parallèle sur une autre plateforme leur permettant d'échanger, de discuter entre elles.eux. En soi, il ne s'agit pas d'une mauvaise nouvelle de constater que nos étudiant.e.s maintiennent le lien entre elles.eux. Le problème est que cette déclinaison du traditionnel "bavardage" en cours/TD/TP, ne peut faire l'objet d'aucun contrôle à distance : vidéo et micro coupés (même si on demande l'activation de la vidéo, il ya le sacro-saint problème de la bande passante qui fait que la vidéo n'est jamais activée), comment voir et entendre qui discute et à quel moment ?  Les traditionnels petits rappels à l'ordre pendant les cours en présentiel ne font plus sens quand tout se fait à distance.

#### Éléments de solution

1. Il s'agit d'abord d'attirer l'attention très régulièrment : les micros sondages "Oui/Non"  
À période très régulière, je demande aux étudiant.e.s, d'utiliser la plateforme institutionnelle pour m'indiquer si ils.elles pensent avoir compris la notion présentée ou si iLs.elles sont à jour dans la procédure décrite. J'exige alors d'utiliser le clic sur un bouton vert (Oui) de la plateforme pour indiquer que tout est *OK*, un clic sur le bouton rouge (Non) si quelque chose pose problème.
Très souvent, il n'y a que des "Oui", car un "Non" signifie en général une sollicitation de ma part pour savoir ce qui n'est pas clair. Cette démarche n'est donc pas un bon moyen de savoir si les étudiant.e.s ont réellement compris une notion. Mais cela permet de maintenir un minimum d'attention car, ce qui ne répondent ni oui, ni non, sont alors sollicité.e.s explicitement pour s'exprimer et "revenir" ainsi dans la partie, au moins quelques minutes... 

![Attirer l'attention fréquemment](/post/images/compris-oui-non.png)


2. Susciter l'engagement cognitif encore plus systématiquement... 
J'avais déjà pour habitude de mobiliser différentes approches pendant les cours pour mobiliser les étudiant.e.s sur des activités dites "génératives" ou "interactives" : les activités génératives demandent aux apprenants la construction de nouvelles ressources à partir du matériel pédagogique qu'il ont reçu. Les activités interactives placent les apprenants en situation de construire des connaissances en s'appuyant sur les autres apprenants.  Ces types d'activités ont été décrits, entre autres, par les chercheuses Chie et Wylie dans [un article révélant le lien entre type d'activité et niveau d'engagement cognitif](https://www.tandfonline.com/doi/abs/10.1080/00461520.2014.965823). Les activités génératives et interactives sont celles qui suscitent le plus fort niveau d'engagement cognitif. Ce qui a changé dans ma pratique à distance, c'est l'augmentation de la fréquence d'utilisation d'un dispositif permettant de proposer sur une même séquence, du génératif et de l'interactif. Plus précisément, j'ai systématisé la notion d'activité préliminaire à toute présentation d'un concept nouveau. En effet, il a été mis en évidence par ... qu'interroger des étudiant.e.s avant la présentation "transmissive" d'une ressource augmente leur engagement cognitif pendant la présentation.

La platforme utilisée, [Elaastic](https://www.irit.fr/elaastic/), est celle que nous développons à l'[IRIT](https://www.irit.fr) dans le cadre de nos recherches sur le développement de technologies facilitant la mise en œuvre de pédagogies actives, c'est à dire de pédagogies qui engagement fortement les étudiants. La capture d'écran ci-dessous présente le résultat obtenu, en terme de participation, à une activité d'introduction à la planification dans les projets informatiques menés suivant une [méthode agile](https://www.agilealliance.org/agile101/). L'activité a été déclenchée dès l'ouverture du cours programmé à 8h. 38 présents sur un cours où plus de 50 étudiants sont inscrits. Sur les 38 présents, 35 s'inscrivent effectivement à l'activité et 33 participent réellement.

![Susciter l'engagement cognitif](/post/images/elaastic-before-pres.png)

### Contexte d'utilisation optimal et limites

Les micros sondages "Oui/Non" fournissent un indicateur quantitatif à un instant donné. Il est particulièrement utile pour vérifier, sur une activité de TP guidée, que l'on a pas perdu un.e étudiant.e sur une étape critique. Dans le contexte d'un présentation purement magistrale, cet indicateur ne révèle en rien le niveau d'engagement cognitif des étudiant.e.s interrogé.e.s. 

Les activités menées avec [Elaastic](https://www.irit.fr/elaastic/) permettent d'aller plus loin en terme de mesure qualitative de l'engagement cognitif des apprenants : la visualisation rapide des réponses textuelles pendant ou après que les étudiants aient répondu à la question permettent de distinguer rapidement des réponses baclées ou au contraire des réponses montrant de la réflexion. Le *feedback* associé à une séquence elaastic permet de cibler les étudiants semblant les moins engagés dans l'espoir de les ramener dans un cercle vertueux conduisant à l'apprentissage.  
L'augmentation de la fréquence d'utilisation de l'outil a conduit à alléger certains contenus. C'est une des limites de l'approche : pour conserver une exigence d'apprentissage en profondeur, et donc une exigence forte en terme d'apprentissage, il faut accepter, si nécessaire, une baisse du périmètre du contenu, tout comme on le fait en informatique, dans le contexte de projets *agiles* pour garantir un niveau de qualité élévé des livrables.

## Problème n°2 - Le silence est roi

#### Le problème

Les étudiant.e.s ne répondent pas spontanément aux questions ouvertes dans une session en grand nombre (20 à 40 présents). Vidéos et micros coupés, cette absence de réponses peut rapidement transformer une session en un étrange monologue de l'enseignant.

#### Éléments de solution

La plateforme de visioconférence utilisée à l'IUT de Rodez permet, à partir de la salle principale accueillant tous les participants de la classe virtuelle, de créer des salles virtuelles isolées les unes des autres. L'enseignant peut créér autant de salle qu'il le souhaite et peut choisir le mode de répartition des étudiant.e.s dans les salles : 

- le mode de répartition aléatoire : la plateforme garantit alors une répartition équilibrée des effectifs, 
- le mode "affectation par l'enseignant" : c'est donc l'enseignant qui force la répartition des effectifs,
- le mode "affectation libre" : les étudiant.e.s choisissent librement leur salle d'affectation.

Une fois les étudiant.e.s regroupés en petits effectifs (4 ou 5 maximum, en ce qui me concerne), je peux circuler de salle en salle et sonder les étudiant.e.s via un tour de table où chacun est invité à prendre la parole pour exprimer l'état d'avancement sur un travail ou pour poser des questions sur ce qui nécessiterait clarification.  
Dans ce contexte, les étudiant.e.s parlent.

#### Contexte d'utilisation optimal et limites

Le dispositif présenté est optimal quand les étudiant.e.s ont un travail à réaliser comme un exercice de TD ou de TP. Il permet de se rapprocher de ce que l'on vit en présentiel durant les séances de TP ou de TD, où il est possible de circuler dans la salle pour suivre la progression des étudant.e.s et interagir avec elles.eux en fonction des travaux observés. Le partage d'écran activé pour tous les participants permet d'avoir accès aux productions de chacun.e.  
Ces petites salles peuvent susciter la collaboration et l'entraide au sein du groupe, mais pas systématiquement. En effet, nous sommes toujours face à la concurrence déloyale de l'autre plateforme, celles des étudiant.e.s, qui est un autre levier pour l'entraide et la collaboration. Pour que les 2 plateformes ne se fassent pas concurrence, il est donc important, si les travaux demandés sont individuels, de laisser les étudiant.e.s choisir la répartition. Dans le cas contraire, on risque de se retrouver dans une salle désertée par des étudiant.e.s qui sont allés retrouver leurs ami.e.s de travail dans l'autre platforme (c'est du vécu !). Je ne mobilise donc la répartition aléatoire que quand la collaboration/coopération fait partie du travail demandé avec par exemple une solution commune à produire et une restitution du groupe à l'ensemble. C'est une manière de "forcer" les échanges entre des apprenant.e.s qui n'ont pas forcément l'habitude de se cottoyer.



