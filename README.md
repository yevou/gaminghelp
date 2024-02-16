<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>GamingHelp! - Ton guide ultime pour le monde des jeux vidéo</title>
    <style>
        /* Styles pour les boutons */
        .bouton {
            display: inline-block;
            padding: 10px 20px;
            font-size: 16px;
            text-align: center;
            text-decoration: none;
            background-color: #FFA500;  /* Utilisation de la couleur orange */
            color: black;  /* Couleur du texte en noir */
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }

        /* Style supplémentaire pour espacer les boutons */
        .espace {
            margin-right: 10px;
        }
    </style>

    <script>
        function afficherTexte(texte) {
            document.getElementById("contenu").innerHTML = texte;
        }

        function afficherAccueil() {
            document.getElementById("contenu").innerHTML = `
                <p>Bienvenue sur GamingHelp!, ton guide ultime pour le monde des jeux vidéo.</p>
                <p>J'ai créé ce site pour aider les gens à utiliser certains jeux vidéo.</p>
                <p>Si tu souhaites rajouter des aides ou des vidéos de jeux, n'ésite pas à me l'adresse mail suivante : <a href="mailto:yevousalu18@gmail.com">yevousalu18@gmail.com</a>.</p>
            `;
        }
    </script>
</head>
<body>

    <!-- Boutons avec liens -->
    <a href="#" class="bouton espace" onclick="afficherAccueil()">Accueil</a>
    <a href="#" class="bouton espace" onclick="afficherTexte('Steam est une plateforme de jeu en ligne, c\'est-à-dire une application qui te permet d\'installer des jeux, de discuter avec des amis en chat vocal en partie, et bien plus encore !<br>\
De plus, Valve Corporation, qui est la société de développement qui a sorti Steam, propose des accessoires comme la Steam Deck qui est une console conçue spécialement pour accueillir Steam, car les autres consoles telles que Nintendo, PlayStation ou Xbox peuvent ne pas être compatibles avec la plateforme.<br>\
La Steam Deck offre une expérience de jeu portable puissante avec des fonctionnalités telles que des contrôleurs intégrés, un écran tactile de 7 pouces, et la possibilité de jouer à une grande variété de jeux PC.<br>\
La Steam Deck est disponible en différentes configurations avec des variations de stockage, de performances, et de prix, offrant ainsi une flexibilité aux joueurs.<br>\
Steam, véritable géant du gaming en ligne, ne se limite pas à être une simple plateforme d'achat de jeux.<br>\
Avec ses fonctionnalités sociales, son Workshop pour la création de contenu personnalisé, ses soldes attractives, une bibliothèque de jeux organisée, le streaming, un support technique fiable, et même une immersion en réalité virtuelle via SteamVR,<br>\
cette plateforme offre une expérience complète aux passionnés de jeux vidéo.')">Steam, c'est quoi ?</a>
    <a href="#" class="bouton espace" onclick="afficherTexte('Alors, pour installer Steam, il faut déjà aller sur un site de confiance, en l\'occurrence, le site officiel.<br>Voici le lien vers la page de téléchargement officiel de Steam : <a href=\'https://store.steampowered.com/about/\'>https://store.steampowered.com/about/</a>')">Comment installer Steam</a>
    <a href="https://discord.gg/T3Ayks6P" class="bouton" target="_blank">La Famille</a>

    <!-- Contenu de la page -->
    <div id="contenu">
        <p>Bienvenue sur GamingHelp!, ton guide ultime pour le monde des jeux vidéo.</p>
        <p>J'ai créé ce site pour aider les gens à utiliser certains jeux vidéo.</p>
        <p>Si tu souhaites rajouter des aides ou des vidéos de jeux, contacte-moi à l'adresse mail suivante : <a href="mailto:yevousalu18@gmail.com">yevousalu18@gmail.com</a>.</p>
    </div>

</body>
</html>
