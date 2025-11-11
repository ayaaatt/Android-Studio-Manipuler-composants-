# Android-Studio-Manipuler-composants
https://drive.google.com/drive/u/1/folders/1mPQ0fTYIMPDgFkb8z7TYix_1aV-EqhP7

# 📱 Application Android – Formulaire Utilisateur

Application Android permettant de saisir des informations utilisateur (**nom**, **prénom**, **ville**, **genre**) et d’afficher un résumé sous forme de **Toast**.

---

## ✅ 1. Objectifs du projet

Ce projet a pour objectifs :

* Créer une **interface simple et intuitive** en Android.
* Manipuler les principaux composants :

  * `EditText` — saisie du nom et du prénom
  * `Spinner` — choix de la ville
  * `RadioGroup` & `RadioButton` — choix du genre
  * `Button` — validation
  * `Toast` — affichage du résultat
* Apprendre à **récupérer et traiter les valeurs saisies**.
* Comprendre la relation entre **XML (UI)** et **Java (logique)**.
* Introduire les bases d’une `Activity` Android.

Ce projet constitue une introduction pratique au développement mobile.

---

## ✅ 2. Architecture technique

### 🔸 2.1. Technologies utilisées

* **Android Studio** – IDE principal
* **Java** – Langage de programmation
* **XML** – Conception de l’interface
* **Android SDK** – Composants système

---

### 🔸 2.2. Structure du projet

```
app/
 ├── manifests/
 │     └── AndroidManifest.xml
 ├── java/
 │     └── ma.agadir.app/
 │           └── MainActivity.java
 └── res/
       ├── layout/
       │     └── activity_main.xml
       ├── values/
       │     ├── strings.xml
       │     └── colors.xml
       └── mipmap/
             └── ic_launcher.png
```

---

### 🔸 2.3. Description des composants UI

* **TextView** — labels : Nom, Prénom, Ville, Genre
* **EditText** — champs de saisie pour nom et prénom
* **Spinner** — liste déroulante des villes : *Agadir, Marrakech, Rabat, Casa*
* **RadioGroup / RadioButton** — sélection du genre (F ou M)
* **Button** — bouton de validation
* **Toast** — affiche le résumé des informations saisies

---

### 🔸 2.4. Fonctionnement du code (MainActivity)

1. Récupération des composants via `findViewById()`
2. Création d’un **ArrayAdapter** pour remplir le Spinner
3. Lecture des valeurs saisies :

   * Nom & Prénom (EditText)
   * Ville (Spinner)
   * Genre (RadioGroup)
4. Construction d’un message formaté
5. Affichage du résultat dans un **Toast**

**Exemple affiché :**

```
hassaoui aya – Marrakech – Genre : F
```

---

## ✅ 3. Résultats obtenus

L'application permet :

* La **saisie du nom et du prénom**
* La **sélection d’une ville**
* Le **choix du genre**
* L'affichage d’un message récapitulatif clair via un Toast

L’interface est simple, moderne, fluide et entièrement fonctionnelle.

---


![WhatsApp Image 2025-11-11 à 19 10 37_31779892](https://github.com/user-attachments/assets/18c359f8-1860-434f-b342-2ddd3e4145cb)
![WhatsApp Image 2025-11-11 à 19 10 38_48721027](https://github.com/user-attachments/assets/10ba893d-e4c2-4615-aee1-4642a68d473c)

