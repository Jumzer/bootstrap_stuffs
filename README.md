Salut !

Voici mon Bootstrap ! J'ai malheureusement manqué de temps pour le terminer ...

-------

Petite remarque :

Le jumbotron met le bazar ! Dès lors qu'il est ajouté au CSS (voir plus bas), la police est altérée et ne correspond plus au thème Bootstrap.

Voici le bout de code CSS qui permet aux bannières d'avoir une image mais qui remplace la police :



.jumbotron {
  height: 500px;
  background-image: url("party.jpg");
  background-position: center;
  background-repeat: no-repeat;
  background-size: cover;
}

.jumbotron-little {
  height: 300px;
  background-image: url("party.jpg");
  background-position: center;
  background-repeat: no-repeat;
  background-size: cover;
}