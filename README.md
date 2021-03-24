## Installation 

Vous devez au préalable disposer de docker / docker-compose / npm sur votre machine. 

Veuillez ouvrir un terminal. Rendez vous à la racine du projet puis effectuer : 

- `npm i`
- `cd docker`
- `docker-compose build`
- `docker-compose up`

A cette étape votre docker est lancé. 

Dans un autre onglet de terminal veuillez lancer à la racine du projet un `ǹpm run dev`

Vous pouvez maintenant disposer de votre site directement sur votre localhost. 

## Exercice

Veuillez réaliser une liste de film sur la partie gauche de l'écran et une liste de film favoris sur la droite. 

Lorsque je clique sur l'un des films de la liste de gauche, il rejoint la liste des favoris. 

Chaque ligne de la liste des favoris disposent d'une croix permettant de le supprimer de la liste des favoris. IL rejoint alors la liste des films de gauche. 
