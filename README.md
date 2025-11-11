# Android-Studio-Manipuler-composants
https://drive.google.com/drive/u/1/folders/1mPQ0fTYIMPDgFkb8z7TYix_1aV-EqhP7
#📱 Application Android – Formulaire Utilisateur

Application simple en Android permettant de saisir des informations utilisateur (nom, prénom, ville, genre) et d’afficher le résultat.

#✅ 1. Objectifs du projet

Le but de cette application est de :

Créer une interface utilisateur Android simple et intuitive

Manipuler les principaux composants graphiques :
✅ EditText (saisie de texte)
✅ Spinner (liste déroulante)
✅ RadioGroup / RadioButton (sélection du genre)
✅ Button
✅ Toast (afficher un message à l’utilisateur)

Apprendre à récupérer les valeurs saisies et les traiter dans le code Java

Afficher un résumé des informations via un Toast

Comprendre la structure d’une Activity Android (XML + Java)

L'application constitue une introduction à la programmation Android, au design XML et à la communication entre interface et code Java.

#✅ 2. Architecture technique
🔸 2.1. Technologies utilisées

Android Studio : environnement de développement utilisé pour créer l’application.

Java : langage principal utilisé pour la logique métier.

XML : utilisé pour la conception de l’interface graphique (layouts).

Android SDK : fournit les composants nécessaires au fonctionnement de l’application.

🔸 2.2. Structure du projet

Le projet est organisé de la manière suivante :

app/
 ├── manifests/
 │     └── AndroidManifest.xml           → Déclare l’activité principale
 ├── java/
 │     └── ma.agadir.app/
 │           └── MainActivity.java       → Logique de l’application
 └── res/
       ├── layout/
       │     └── activity_main.xml       → Interface utilisateur
       ├── values/
       │     ├── strings.xml             → Textes et libellés
       │     └── colors.xml (optionnel)  → Palette de couleurs
       └── mipmap/
             └── ic_launcher.png         → Icône de l’application

🔸 2.3. Description des composants UI

L’interface graphique de l’application utilise les éléments suivants :

TextView : affiche les titres des champs (Nom, Prénom, Ville, Genre).

EditText : permet à l’utilisateur de saisir son nom et son prénom.

Spinner : fournit une liste déroulante contenant les villes : Agadir, Marrakech, Rabat, Casa.

RadioGroup et RadioButton : permettent de sélectionner le genre (F ou M).

Button : déclenche la validation du formulaire.

Toast : affiche un message récapitulatif avec les informations saisies.

🔸 2.4. Fonctionnement du code Java (MainActivity)

Le fonctionnement interne de l'application se déroule en plusieurs étapes :

Récupération des composants de l’interface via findViewById().

Création d’un adapter pour remplir automatiquement le Spinner avec la liste des villes.

Récupération des valeurs saisies par l’utilisateur :

le nom et le prénom depuis les champs EditText,

la ville sélectionnée depuis le Spinner,

le genre choisi dans le RadioGroup.

Construction d’un message formaté en combinant toutes les données.

Affichage du résultat dans un Toast pour donner un retour immédiat à l’utilisateur.

Exemple de résultat affiché :

hassaoui aya – Marrakech – Genre : F
#✅ 3. Résultats obtenus
![WhatsApp Image 2025-11-11 à 19 10 37_31779892](https://github.com/user-attachments/assets/18c359f8-1860-434f-b342-2ddd3e4145cb)
![WhatsApp Image 2025-11-11 à 19 10 38_48721027](https://github.com/user-attachments/assets/10ba893d-e4c2-4615-aee1-4642a68d473c)

