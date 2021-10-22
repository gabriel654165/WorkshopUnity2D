# WorkShop Unity 2D <h1>
 In this workshop your going to make the begginin of a village manager game.
 Your game at the end is going to looks like a clash of clan or a sims like (with much more functionalities)

# Prerequieres : <h3>
  - Installer unity depuis UNITY HUB.
  - Telecharger la version UNITY 2020 (lts)

# Step 1 : Tilemap

 We are going to create a tilemap isometric (ISO).

Your objects in scene are on the left of your screen. You normaly starts with a MainCamera and thats all.

 - Create a tilemap with a ISO grid

 - Open your tile palet in : Window/2D/TilePalet, with this your going to create the base of the level

 - Create a new palette, and drag the assets Isometric sliced level in
 
 - lets create a simple map then
 
![alt text](https://github.com/gabriel654165/WorkshopUnity2D/blob/master/images/Screenshot%20from%202021-10-13%2020-51-11.png)



# Step3 : IU -> faire un inventaire d'objets a placer sur ta map

 - nouveau objet canvas IU

 - creer un enfant Image inventory

 - créer des objets dans cet inventaire


# Step4: Scripts

 - public

 - gameobject a fill via IDE ou fonction

 - start & update


# Step5 : Events IU

 - créer un script avec une fonction qui met en surbillance l'objet

 - dans l'inventory des objets créer ajouter un event (on survoling) et assigner la fonction créée

 - créer un objet ISO hors tilemap

 - créer un script qui fais disparaitre  l'objet IU & fait apparaitre a une position milieu ecran un objet ISO (assigner l'objet UI + objet ISO)

 - ajouter un event on drag sur l'objet IU & assigner le srcript créé

 - BONUS : son


# Step6 : Objet qui suis la souris

 - Instancier un objet et l'afficher une fois avoir cliqué sur l'object


# Step7 : SoundDesign

 - AudioSource p; p.Play()


# Step8 : Camera moves

 - ajouter un script a la camera et transform.position


# Step9: Clic on the object

 - detecter la position de la souris

 - selectionner l'object colide