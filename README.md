# WorkShop Unity 2D 
 In this workshop your going to make the begginin of a city manager game
 Your game at the end is going to be like a clash of clan or an sims like (whith much more functionalities)

# Prerequieres : <h3>
  Installer unity depuis UNITY HUB.
  Telecharger la version UNITY 2020 (lts)

Step 1 : Créer un hero avec sprite + scripts
     vous allez utilisez seulement des objets 2D dans ce projet
     Unity a des objets déjà créer avec des composants (aller voir leur inspector)
     - Créer un empty object
     - Selectionner l'objet, le nomer Hero, ajouter un sprite2d dans l'inspector

Step2 : Tilemap
      tilemap ISO
      - créer une tilemap, créer un grid ISO
      - Window/2D/TilePalet
      - créer une nouvelle palette
      - ajouter une tile a cet object (drag & drop les assets sliced dans la tile palet)
      - fait une map simple

Step3 : IU -> faire un inventaire d'objets a placer sur ta map
      - nouveau objet canvas IU
      - creer un enfant Image inventory
      - créer des objets dans cet inventaire

Step4: Scripts
       - public
       - gameobject a fill via IDE ou fonction
       - start & update

Step5 : Events IU
      - créer un script avec une fonction qui met en surbillance l'objet
      - dans l'inventory des objets créer ajouter un event (on survoling) et assigner la fonction créée
      - créer un objet ISO hors tilemap
      - créer un script qui fais disparaitre  l'objet IU & fait apparaitre a une position milieu ecran un objet ISO (assigner l'objet UI + objet ISO)
      - ajouter un event on drag sur l'objet IU & assigner le srcript créé
      - BONUS : son

Step6 : Objet qui suis la souris
      - Instancier un objet et l'afficher une fois avoir cliqué sur l'object

Step7 : SoundDesign
      - AudioSource p; p.Play()

Step8 : Camera moves
      - ajouter un script a la camera et transform.position

Step9: Clic on the object
       - detecter la position de la souris
       - selectionner l'object colide