# technicalTest

Entrant :

WS :
- https://etablissements-publics.api.gouv.fr/v1/organismes/59/mairie
- https://etablissements-publics.api.gouv.fr/v1/organismes/59/gendarmerie


Dans le projet joint, effectuer les tâches suivantes :

Récupérer et parser les données du WS en utilisant une classe « Poi » sans pour autant la modifier. 
Cette classe comportera les propriétés suivantes : 
- id 
- longitude
- latitude

Utiliser un des principes du langage objet.

On pourra utiliser une librairie pour l’appel au WS.

Développez une application Android (Kotlin) qui comportera deux partie :
Affichage par carte :

- Afficher les Poi précédemment récupérer et les afficher sur la carte.

- On Affichera la position de l’utilisateur

- Lors de la sélection d’une annotation, on calculera et on affichera le chemin entre l’utilisateur et l’annotation.

- On pourra filtrer les annotations par l’option d’accessibilité des données sur WS (via un switch)

- On pourra filtrer les annotations par distance (30 km autour de l’utilisateur)

- Ces deux filtres sont cumulables.

- Ajouter un bouton pour remettre a zéro les filtres

Affichage par liste :

- Afficher des cellules contenant
  - Nom  
  - Téléphone -> permet de lancer un appel (si disponible)
  - Email -> permet d’envoyer un email (si disponible)

- On pourra trier les Poi par ordre du WS (default) ou par distance par rapport à l’utilisateur (via un switch)

- On pourra filtrer les Poi via une recherche sur le nom ou le code postal
