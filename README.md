

@font-face {
	font-family: "Gotham Medium";
	src: url('Gotham Medium.otf');
}

body {
    font-family: "Gotham Medium", Helvetica, Arial, sans-serif;
}

body, div, section, h1, h2, p {
    margin:0;
    padding:0;
}

section.page {
    height:100vh;
    background-position: center;
    background-repeat: no-repeat;
    background-size: cover;
    background-image: url("images/model3.jpg");
}

.page {
    position: relative;
}

.bas-section {
    left: 50%;
    transform: translateX(-50%);
    position: absolute;
    bottom: 50px;
}


:hover 




svg {
    display: flex;
    position: absolute;
}

.navbar {
    display: flex;
    justify-content: center; 

    
}

h1 {
    font-size: 40px;
    font-weight: 100;
    padding-top: 100px;
}

#footer-tesla{
    text-align: center;
    bottom: 0px;
    left: 0;
    right: 0;
    position: absolute;
}

#footer-tesla ul {
    text-align: center;
}

#footer-tesla li {
    display: inline-block;
    margin: 0 10px;

}

#footer-tesla a {
    color: #393c41;
    text-decoration: none;
    font-size: 10px;
    text-transform: uppercase;
    cursor: pointer;
}

#grid-container {
    display: grid;
    grid-template-columns: 33.33% 33.33% 33.33%;
    padding: 10px;
    margin: 0 5%;
    justify-items: center;
}

.grid-item {
    margin: 0 30px;
    max-width: 320px;
    height: 530px;
    position: relative;
}

.grid-item img{
    width: 100%;
}

.inner {
    padding: 30px;
    font-size: 0.9em;
}

.inner p {
    margin-bottom: 30px;
    color: #171a20;
    font-size: 12px;
    text-align: justify;
}

.inner h2 {
    color: #171a20;
    padding-top: 0px;
    margin: 0 0 10px 0;
    text-transform: uppercase;
}

.grid-item a {
    border-radius: 50px;
    opacity: 0.75;
    padding-top: 10px;
    padding-right: 20px;
    padding-bottom: 10px;
    padding-left: 20px;
    border: none;
    background-color: #171a20;
    color: white;
    cursor: pointer;
    position: absolute;
    bottom: 0;
    left: 50%;
    transform: translate(-50%, 0);
    white-space: nowrap;
    
    
    
    
    -------------------------------------------------------------
    
    
    
    <!DOCTYPE html>
<html lang="fr">

<head>
    <meta charset="UTF-8">
    <link rel="icon" type="image/png" href="images/favicon.png" />
    <title>Voitures électriques, énergie solaire et propre | Telsa France</title>
    <link rel="stylesheet" href="style-1.css">
    <script src="script-0.js"></script>
</head>

<body>
    <!-- Insérer votre code HTML *en-dessous* de cette ligne -->

    <header>
        <svg xmlns="http://www.w3.org/2000/svg" height="50" width="120" viewBox="-41.8008 -9.08425 362.2736 54.5055">
            <path d="M238.077 14.382v21.912h7.027V21.705h25.575v14.589h7.022V14.42l-39.624-.038m6.244-7.088h27.02c3.753-.746 6.544-4.058 7.331-7.262h-41.681c.779 3.205 3.611 6.516 7.33 7.262m-27.526 29.014c3.543-1.502 5.449-4.1 6.179-7.14h-31.517l.02-29.118-7.065.02v36.238h32.383M131.874 7.196h24.954c3.762-1.093 6.921-3.959 7.691-7.136h-39.64v21.415h32.444v7.515l-25.449.02c-3.988 1.112-7.37 3.79-9.057 7.327l2.062-.038h39.415V14.355h-32.42V7.196m-61.603.069h27.011c3.758-.749 6.551-4.058 7.334-7.265H62.937c.778 3.207 3.612 6.516 7.334 7.265m0 14.322h27.011c3.758-.741 6.551-4.053 7.334-7.262H62.937c.778 3.21 3.612 6.521 7.334 7.262m0 14.717h27.011c3.758-.747 6.551-4.058 7.334-7.263H62.937c.778 3.206 3.612 6.516 7.334 7.263M0 .088c.812 3.167 3.554 6.404 7.316 7.215h11.37l.58.229v28.691h7.1V7.532l.645-.229h11.38c3.804-.98 6.487-4.048 7.285-7.215v-.07H0v.07"/>
        </svg>
        <nav class="navbar">
            <ul>
                <li>
                    <a href="#model3">Model 3</a>
                </li>
                <li>
                    <a href="#modelS">Model S</a>
                </li>
                <li>
                    <a href="#powerwall">Powerwall</a>
                </li>
                <li>
                    <a href="#accessoires">Accessoires</a>
                </li>
            </ul>
        </nav>
    </header>

    <section id="model3" class="page">
        <h1>Model 3</h1>
        <a id="reserver" href="https://www.tesla.com/fr_fr/drive">Réservez un essai sans contact</a>
        <div class="bas-section">
            <a class="btn-config" href="https://www.tesla.com/fr_fr/model3/design">
                Configuration personnalisée
            </a>
            <a class="btn-vehicules" href="https://www.tesla.com/fr_fr/inventory/new/m3">
                Véhicules disponibles
            </a>
            <p>A reçu la note maximale de 5 étoiles par Euro NCAP</p>
            <img id="model3-img" src="images/fleche.gif" alt="suivant">
        </div>
    </section>

    <section id="modelS" class="page">
        <h1>Model S</h1>
        <div class="bas-section">
            <a class="btn-config" href="https://www.tesla.com/fr_fr/models/design">
                Configuration personnalisée
            </a>
            <a class="btn-vehicules" href="https://www.tesla.com/fr_fr/inventory/new/m3">
                Véhicules disponibles
            </a>
        </div>
    </section>

    <section id="powerwall" class="page">
        <h1>Systèmes d'énergie solaire et Powerwalls</h1>
        <h2>De l’énergie pour tous vos besoins</h2>
        <div class="bas-section">
            <a class="btn-config" href="https://www.tesla.com/fr_fr/powerwall">En savoir plus</a>
        </div>
    </section>

    <section id="accessoires" class="page">
        <h1>Accessoires</h1>
        <div id="grid-container">
        </div>
        <footer>
            <ul>
                <li>
                    <a href="https://www.tesla.com/fr_fr/about">Tesla © 2021</a>
                </li>
                <li>
                    <a href="https://www.tesla.com/fr_fr/about/legal">Mentions légales</a>
                </li>
                <li>
                    <a href="https://www.tesla.com/fr_fr/contact">Contact</a>
                </li>
                <li>
                    <a href="https://www.tesla.com/fr_fr/careers">Carrières</a>
                </li>
                <li>
                    <a href="https://www.tesla.com/fr_fr/updates">Newsletter</a>
                </li>
                <li>
                    <a href="https://www.tesla.com/fr_fr/blog">Actualités</a>
                </li>
                <li>
                    <a href="https://www.tesla.com/fr_fr/findus/list">Localisations</a>
                </li>
            </ul>
        </footer>
    </section>

    <!-- Insérer votre code HTML *au-dessus* de cette ligne -->

    <template id="template_accessoires">
        <div class="grid-item">
            <img src="images/{{accessoires-image}}.jpg">
            <div class="inner">
                <h2>{{accessoires-titre}}</h2>
                <p>
                    {{accessoires-texte}}
                </p>
            </div>
            <a href="www.tesla.com/fr_fr">En savoir plus</a>
        </div>
    </template>

</body>

</html>


--------------------------------------------------------------------------------------------------

function recup() {
    fetch("../javascript/perso.json")
    .then(function(response){
    let returnedValue = response.json();
    console.log(returnedValue)
    return returnedValue;
    })



    
    
    
