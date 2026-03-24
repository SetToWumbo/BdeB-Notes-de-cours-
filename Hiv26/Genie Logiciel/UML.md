Unified Modelling Language

Norme de représentation graphique pour logiciels
Booch, Jacobson et Rumbaugh

Modélisation de l'intéraction entre usager et système: Cas Utilisation(use case)

Classes, Structure, liens entre logiciels

comportements (machines à état, interactions entre les classes et objets quand on donne un ordre)

## Diagramme de Classes (Structure)

Diagramme Statique montrant la structure et les relations entre les objets.
Référence de livre: UML distilled Martin Fowler

![[diagramme-classe.png]]

![[legende-diagramme-classe.png]]
## Diagramme des Cas d'Utilisation
Montre les fonctions offertes par le système aux usagers

Acteur: utilisateur ou système externe qui interagit avec le système. Peut avoir plusieurs acteurs internes ou externes.

Cas d'Utilisation: fonction offerte par le système, interaction possible, raconte comment l'utilisation d'une fonction se déroule.

Flèche entre acteur et fonction indique déclenchement de l'action par l'acteur.

Flèche pars du cas d'utilisation vers autre acteur externe: appel/utilisation de l'acteur externe dans la fonction.

Flèche d'un acteur à l'autre: Héritage entre acteurs, généralisation/spécialisation

![[diagramme-cas-util.png]]

## Diagramme de Communication

Montre les objets qui se parlent entre eux (appels de méthode entre objets)
## Diagramme de Séquence
 
Conversations entre plusieurs systèmes-acteurs à haut niveau
![[diagramme-sequence.png]]


![[diagramme-sequence-condition.png]]
Si on veut exprimer le dialogue entre 2 objets au lieu d'un user et du système, on indiquerait les classes sur les deux extrémités a la place.

**![[diagramme-sequence-labels-noms.png]]

Le choix a faire est ce qui est important a communiquer au lecteur, pas de faire le map complet approfondi du système. Éliminer le bruit.