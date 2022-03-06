<script setup>

</script>

<template>
    <div class="footer">
        <div class=" footer-1">
            <div class="sous-block1">
                <div class="sous-sous-block">
                    <p class="icone">Icone</p>
                    <h4 class="titre4">Qualité et prix</h4>
                    <p class="texte-footer">Prix compétitifs sur plus de<br>100 millions de produits</p>
                </div>
                <div class="sous-sous-block">
                    <p class="icone">Icone</p>
                    <h4 class="titre4">Livraison internationale</h4>
                    <p class="texte-footer">Avec un site en 12 langues <br> nous livrons dans plus de 200 <br>pays et régions</p>
                </div>
                <div class="sous-sous-block">
                    <p class="icone">Icone</p>
                    <h4 class="titre4">Paiement sécurisé</h4>
                    <p class="texte-footer">Payer avec les méthodes les <br>plus populaires et les plus <br> sûres au monde</p>
                </div>
                <div class="sous-sous-block">
                    <p class="icone">Icone</p>
                    <h4 class="titre4">Acheter en toute confiance</h4>
                    <p class="texte-footer">Notre protection de l'acheteur <br> vous protège du premier clic à <br> la livraison</p>
                </div>
                <div class="sous-sous-block">
                    <p class="icone">Icone</p>
                    <h4 class="titre4">Centre d'aide</h4>
                    <p class="texte-footer">Assistance 24/7 pour <br> répondre à toutes vos <br> questions</p>
                </div>
                <div class="sous-sous-block">
                    <p class="icone">Icone</p>
                    <h4 class="titre4">Acheter Malin</h4>
                    <p class="texte-footer">Télécharger l'application pour <br> des options exculsives comme <br> la recherche par images et les <br>jeux</p>
                </div>
            </div>
            <div class="bc sous-block2">
                sous-block 2
            </div>
        </div>
        <div class="bc footer-2">Block2</div>
        <div class="bc footer-3">Block3</div>
        <div class="bc footer-4">Block 4</div>
    </div>
</template>

<style scoped>

.footer{

    width: 100%;
    background-color: #E8E8E8;
    font-family: 'Open Sans', sans-serif;
}

.sous-block1{
    background-color: #FFF;
    display: flex;
    justify-content: center;

}
.icone, .titre4, .texte-footer{
    margin-bottom: 2%;
}

.border {
    border-right: 1px solid lightgray;
}
.icone{
    font-size: 9px;
}
.titre4{
    font-size: 10px;
    font-weight: bold;
    font-family: open-sans;
    
}

.texte-footer{
    color: gray;
    font-size: 8px;
    text-align: center;
}

.sous-sous-block{
     
     padding: 1% 2%;
     display: flex;
     flex-direction: column;
     justify-content: center;
     align-items: center;
}


</style>