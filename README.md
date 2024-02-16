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
                <p>Si tu souhaites rajouter des aides ou des vidéos de jeux, n'ésite pas à me contacter à l'adresse mail suivante : <a href="mailto:yevousalu18@gmail.com">yevousalu18@gmail.com</a>.</p>
            `;
        }
    </script>
</head>
<body>

    <!-- Boutons avec liens -->
    <a href="#" class="bouton espace" onclick="afficherAccueil()">Accueil</a>
    <a href="#" class="bouton espace" onclick="afficherTexte('Bienvenue sur la page d\'installation de Steam !')">Comment installer Steam ?</a>
    <a href="#" class="bouton espace" onclick="afficherTexte('Bienvenue sur la page Steam, c\'est quoi !')">Steam, c'est quoi ?</a>
    <a href="https://discord.gg/T3Ayks6P" class="bouton" target="_blank">La Famille</a>

    <!-- Contenu de la page -->
    <div id="contenu">
        <p>Bienvenue sur GamingHelp!, ton guide ultime pour le monde des jeux vidéo.</p>
        <p>J'ai créé ce site pour aider les gens à utiliser certains jeux vidéo.</p>
        <p>Si tu souhaites rajouter des aides ou des vidéos de jeux, contacte-moi à l'adresse mail suivante : <a href="mailto:yevousalu18@gmail.com">yevousalu18@gmail.com</a>.</p>
    </div>

</body>
</html>
