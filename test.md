#html
<!DOCTYPE html>
<html>
    <head>
        <title>les formulaires en html</title>
        <meta charset="utf-8">
    </head>
    <body>
        <h1>Une formulaire</h1>
        <form method="post" action=" ">
            <fieldset>
                <label for="Prenom">Votre Prénom</label><br>
                <!--label permet de libéller un champ de formulaire-->
                <br><input type="text" id="Prenom" name="Prenom"><br>
                <label for="Nom">Votre Nom</label><br>
                <br><input type="text" id="Nom" name="Nom"><br>
                <label for="PWD">Mot de passe</label><br>
                <br><input type="password" id="PWD" name="PWD"><br>
                <label for="pays" id="pays">Quel est votre pays ?</label><br>
                <br><input type="radio" id="pays" name="pays" value="France">France<br>
                <br><input type="radio" id="pays" name="pays" value="Maroc">Maroc<br>
                <br><input type="radio" id="pays" name="pays" value="Espagne">Espagne<br>
                <br><label for="genre">Etes-vous un homme ou une femme ?</label><br>
                <select name="genre">
                    <option value="Homme">Homme</option>
                    <option value="Femme">Femme</option>
                </select><br>
                <!--name et id n'esi pas obligatoire d'avoir la même valeur -->
                <!--input permet de créer un champ de données pour user / type définit le type de champs crée-->
                    <!--type text : permet de rentrer un texte-->
                    <!--type password : permet de rentrer un password en mode caché-->
                    <!--type radio : permet de faire un choix-->
                    <!--type submit :permet d'envoyer la formulaire-->
                <!--select : permet de créer une liste-->
                    <!--option : choix dans la liste :Homme/Femme-->
                <!--fieldset : permet d'englober la formulaire dans un cadre-->
                <label for="decription">Commentaire</label><br>
                <br><textarea id="description" name="presentation"></textarea>
                <!--textarea permet de nous servir a créer un champ de texte multi lignes-->
                <br>
                <input type="submit" value="envoyer"><br>
            </fieldset>
        </form>
    </body>
</html>
