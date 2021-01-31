Réalisation d'un puissance 4 en vanilla JS

1. création des différents fichier
  11. index.html --> contient la base d'un fichier html contenant une div avec un id pour venir y insérer le puissance 4

  12. style.css --> contient les classses css suivantes (vide pour l'instant) : 
    121. gameTable (la base du puissance 4)
    122. case (une case d'un puissance 4)
    123. player1 (classe que l'on va ajouter en + de case pour dire qu'un joueur a joué cette case)
    124. player2 (classe que l'on va ajouter en + de case pour dire qu'un joueur a joué cette case)

  13. script.js --> fichier où tu vas développer le puissance4
      création d'un class Puissance4 ou tu vas créer les différents attributs et les différentes méthodes (fonctions) du puissance 4
      chaque case de la grille est égal à 0 si il y a pas de pion, 1 si il y a le pion du joueur 1 et 2 si il y a un pion du joueur 2

  PS : Le fichier html sera vide, ca sera dans le .js que tu ajouter les éléments dans le html

  14. demande moi si cest bon quand tu as fini cette partie


2. Création de la classe Puissance 4 
  21. constructeur : initialise les différents attributs de ta classes (rows, column, firstPlayer etc ...)

  22. création de la méthode "void render()" permettant d'afficher le puissance 4 (à afficher dans le constructeur) 
    221. creation d'un element table et ajouter les lignes/colonnes et ajouter l'element table dans la div créée dans le html

  23. creation des classes css pour afficher le puissance 4

  23. test : quand on lance le .html on doit voir le puissance 4

3. creation des différentes méthodes de l'objet puissance 4 :
      handle_click (quand on clique sur la div crée dans le .html (récupération de la colonne dans l'objet event récupéré en paramètre de la fonction addEventListener))

      int : play(column: int) : récupération de la bonne ligne pour jouer le coup et placer le pion dans la colonne

      set(column: int, row: int) : place l'objet dans le tableau

      boolean : win(row, column, player) regarde si un coup est gagnant

      void : reset() reset de la grille

  



