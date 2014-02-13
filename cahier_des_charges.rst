##################
Cahier des charges
##################

L'objectif final de ce projet est de concevoir et construire une pico-brasserie pilotable par un dispositif électronique et informatique. Avant toute chose, elle doit répondre aux besoins principaux du brasseur amateur  :

* assurer une production de bière régulière en quantité et en qualité;
* expérimenter différentes techniques et maitriser ses processus de brassage;
* satisfaire sa curiosité et sa passion pour le brassage amateur;

Les paragraphes suivants décrivent les exigences retenues pour la conception de la pico-brasserie et qui permettent de satisfaire ces besoins. Ils décrivent également les contraintes techniques prises en compte dans la conception. 

*************************
Description des exigences
*************************

Relatives au processus de brassage
==================================

La pico-brasserie Lulu la nantaise doit être **polyvalente** et permettre à l'utilisateur de réaliser des brassins basés sur différentes méthodes de brassage **tout grain** ou **à partir d'extrait de malt**.

La pico-brasserie doit disposer des équipements permettant de réaliser les différentes étapes de brassage :

* empâtage en `infusion` (mono ou multi paliers) ou en `décoction`;
* ébullition ;
* refroidissement et mise en fermentation ;

Le dimensionnement des éléments de la pico-brasserie doit permettre d'assurer une **production comprise entre 20 et 70 litres** de bière à chaque brassin.

Relatives au contrôle et pilotage
=================================

La pico-brasserie doit être équipée de capteurs de température afin de suivre précisément la température du moût pendant les paliers d’empâtage et la phase d'ébullition. Ces mesures doivent être enregistrées et seront utilisées pour :

* produire des graphiques temporels de l'évolution des températures;
* comparer les mesures effectuées au cours des différents brassage afin d'assurer une qualité constante de réalisation du processus de brassage;

La source de chauffage des cuves doit être asservie par un dispositif de contrôle afin :

* d'atteindre rapidement les consignes de température ;
* d'assurer un maintien précis des températures constantes ;

Le dispositif de contrôle doit également permettre le pilotage des autres actionneurs de la pico-brasserie (vannes, pompes) afin de permettre la programmation d'actions et l'automatisation du processus de brassage.

**********************
Contraintes techniques
**********************

Relatives à l'électricité
=========================

Pour faciliter le contrôle et le pilotage, **la pico-brasserie reposera uniquement sur des équipements fonctionnant à l'énergie électrique**. En particulier, le chauffage des cuves ne nécessitera pas de gaz, ce qui sécurisera également l'installation. Les éléments de chauffage seront donc constitués de résistances électriques.

Le dimensionnement des éléments électriques devra être compatible avec le **fonctionnement de la pico-brasserie sur une installation électrique domestique**. Concrètement, la consommation maximale de la pico-brasserie ne devra dépasser la capacité de l'installation électrique et du contrat d'alimentation. Classiquement, les contrats domestiques limitent à 30A [#f1]_ le courant consommé par l'installation électrique. Une marge suffisante devra être prise en compte pour les autres équipements de l'installation.

Eau et électricité font rarement bon ménage. **La sécurité de l'installation électrique et de l'utilisateur** constituent donc un impératif. L'installation de la pico-brasserie devra donc respecter les normes électriques en vigueur (à préciser), notamment :

* la mise à la terre du corps des appareils métalliques;
* un dimensionnement des conducteurs adapté aux courants;
* la présence d'un interrupteur différentiel pour protéger l'utilisateur et d'un disjoncteur pour l'installation électrique;

.. [#f1] courant maximal pour un contrat 6kVA, `souscrit par une grande majorité de consommateurs <http://www.fournisseurs-electricite.com/fournisseurs-etrangers/actu-des-producteurs/29413-que-veut-dire-kva-en-electricite->`_.

Relatives à l'installation
==========================

Le déroulement des différentes étapes de brassage **ne doit pas nécessiter de manipulation de charges lourdes ou de liquide en ébullition**. En conséquence, le transfert des liquides entre les cuves sera opéré par un ensemble de pompes et de tuyauterie.

Les **matériaux utilisés doivent être adaptés au transport et la conservation de liquide chaud** (>= à 100°c). La conception et le fonctionnement de la pico-brasserie doit permettre un nettoyage simple mais efficace afin de garantir le niveau d'hygiène indispensable au processus de brassage :

* les tuyauteries seront en silicone;
* les raccords et éléments métalliques seront en INOX de qualité alimentaire;

Dans son état opérationnelle, **l’encombrement de la pico-brasserie doit être restreint** aux dimensions suivantes :

* Hauteur max. : 1,70m
* Largeur max. : 2m
* Profondeur max. : 0,7m

Par ailleurs l'installation doit :

* être aussi mobile et que possible afin de permettre l'accès aux différents éléments ;
* faciliter le démontage des éléments lors des opérations de nettoyage et de maintenance ;
* être autonome et ne nécessiter que des raccordements aux réseaux électrique, eau froide et évacuation;

