<script>
   
</script>

<template>
<div class="container">
  <nav class="navbar">
      <div class="publicite">Bannière de publicité</div>
      <ul class="nav-item">
        <li class="list-item">
          Vendre sur Aliexpress 
          <ul class="sous-nav-item menuToggle" >
            <li class="sous-list-item"><a href="#" class="sous-nav-link">S'identifier</a></li>
            <li class="sous-list-item"><a href="#" class="sous-nav-link">Chinois</a></li>
            <li class="sous-list-item"><a href="#" class="sous-nav-link">Inscrivez-vous</a></li>
          </ul>
        </li>
        <li class="list-item">Paramètres de confidentialité</li>
        <li class="list-item">Aide
          <ul class="sous-nav-item menuToggle" >
            <li class="sous-list-item"><a href="#" class="sous-nav-link">Services client</a></li>
            <li class="sous-list-item"><a href="#" class="sous-nav-link">Litiges et rapports</a></li>
            <li class="sous-list-item"><a href="#" class="sous-nav-link">Signaler une infraction des DPI</a></li>
          </ul>
        </li>
        <li class="list-item">Protection de l'acheteur</li>
        <li class="list-item">App</li>
        <li class="list-item">/Français/EUR</li>
        <li class="list-item">Liste d'envie</li>
        <li class="list-item">Compte
          <ul class="sous-nav-item menuToggle" >
            <h4>Bienvenu sur Aliexpress.com</h4>
            <button id="inscrip" class="lesbuttons">S'inscrire</button>
            <button id="connect" class="lesbuttons">Se connecter</button>
            <li class="sous-list-item"><a href="#" class="sous-nav-link">Mes commandes</a></li>
            <li class="sous-list-item"><a href="#" class="sous-nav-link">Centre de messagerie</a></li>
            <li class="sous-list-item"><a href="#" class="sous-nav-link">Listes d'envie</a></li>
            <li class="sous-list-item"><a href="#" class="sous-nav-link">Mes Magasins favoris</a></li>
            <li class="sous-list-item"><a href="#" class="sous-nav-link">Mes Listes de réduction</a></li>
          </ul>
        </li>
      </ul>
    </nav>
    <div class="recherche">
      <h2>AliExpress</h2>
      <p>Acheter malin, vivez mieux !</p>
      <div class="barrederecherche">
        <input type="text">
      </div>
    </div>
</div>
    
</template>

<style scoped>

@import url('https://fonts.googleapis.com/css2?family=Open+Sans:wght@300&display=swap');
.publicite{
  height : 50px;
  width: 100%;
  background-color: lightgray;
}
.navbar{
  background-color : #FAFAFA;
  border-bottom: grey;
}

.nav-item{
  display: flex;
  justify-content: center;
  height: 30px;
  align-items: center;
}
.menuToggle{
  display: none;
}
.disptog{
  display: none;
}
.list-item{
  font-size: 9px;
  margin-right: 1.5%;
  list-style-type: none;
  cursor: pointer;
  font-family: 'Open Sans', sans-serif;
}

.sous-list-item{
  list-style-type: none;
}

.list-item:hover{
  color:red
}

.sous-nav-link{
  text-decoration: none;
  color:black;
}

.sous-nav-item{
  background-color: #FFF;
  border: 1px solid gray;

}

.sous-nav-link:visited{
  text-decoration: none;
}

.sous-nav-link:hover{
  color:gray;
  background-color: #CDCDCD;
}

.barrederecherche{
  border-bottom: 1px solid #000;
}

</style>