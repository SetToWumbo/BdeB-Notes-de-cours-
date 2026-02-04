
Au dela de l'efficatité, on cherche aussi à âtre efficient dans la gestion de projet (utiliser le moins de ressources possibles pour achever le projet)

Gérer la complexité >> minimiser incertitude/anxiété face au projet
zone incertitude: montant de ressources nécessaires pour compléter le projet-logiciel

Retour sur investissement - ROI est attendu du projet.

### Cone de l'incertitude

plus le temps avance, plus incertitude diminue, plus risques diminuent, mais ne sera jamais exacte jusqu'à la fin du projet

Les gens cherchent à se rassurer: n'importe quel chiffre donné devient une bouée. Gens vont s'y accrocher et ne plus remettre en question la donnée soumise.

## Dépôt de données

Dépot interne: Données gérées par l'application (fichiers, BD, backups, tables validation etc.. )
Dépôt externe: Données reçues ou transmises par une autre application ou partagées avec elle (BD partagée, constante commune etc..)

ces informations sont comptées.

En fonction du type d'enregistrement dans le dépôt et de l'élément de donnée enregistré (tout ce qui serait une colonne dans une BD), combien d'éléments dans l'enregistrement on détermine la taille/l'envergure relative du dépôt

Points de fonction non ajustés/brut: n'existe pas - correspond pas directement à ligne de code, requete swl etc.., mesure artificielle de la complexité du dépôt.

### Transactions

**Intrants:** Demande de traitement qui arrive dans le système (Ajouter, modifier, détruire - CRUD)
**Extrants:** Reproduction des données internes vers des dépôts externes (fichiers, BD externe ou partagée, autre logiciel etc..) Chaque format d'output distincte est compté comme un extrant

**Interrogation:** Accès direct aux données dans le dépôt. Prendre le plus complexe entre l'intrant et l'extrant pour mesurer la complexité. Chaque format d'interrogation distinct est compté


Une fois tous les points comptés et sommés pour les transactions, intrants et extrants, il faut ajuster les points de fonction.

Sigma PFdepots + transactions ->UFP (points de fonction non ajustés)

Les estimations doivent refléter les sources de complexité supplémantaires.

### Facteurs d'envergure

Facteurs qui font augmenter ou diminuer complexité du système. 

Il y en a 14.
chaque facteur prend valeur entre 0 et 5.
0: pas d'effet
5: importance incontournable dans le système

