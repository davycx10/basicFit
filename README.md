
---

#  BasicFit

### Projet CFA INSTA – Client Léger

---

##  Basic-Fit – Plateforme de Formation Sportive

###  Description du projet

Ce projet étudiant a pour objectif de concevoir un **site web de formation sportive** dédié aux adhérents **Basic-Fit**.
La plateforme permet aux utilisateurs de **suivre des programmes d’entraînement en ligne**, adaptés à leurs objectifs personnels :

*  Perte de poids 
*  Prise de masse
*  Remise en forme
*  Maintien d’une activité physique régulière

Le site propose une expérience interactive et motivante grâce à :

* des **exercices illustrés** étape par étape,
* des **vidéos explicatives** réalisées par des coachs,
* des **conseils personnalisés** selon le profil et les objectifs de l’utilisateur,
* un **suivi de progression** pour mesurer les résultats dans le temps.

L’objectif principal est d’aider les membres Basic-Fit à **optimiser leurs entraînements**, même en dehors de la salle, grâce à un **accompagnement digital simple, accessible et motivant**.

---
## Design et ergonomie

Le design du site repose sur le framework Bootstrap
, afin d’assurer :

une interface moderne et responsive,

une cohérence visuelle sur tous les supports (ordinateur, tablette, mobile),

et un développement rapide et structuré des composants graphiques.

L’utilisation de Bootstrap permet de garantir une expérience utilisateur fluide et conforme aux standards du web actuel (et surtout pour gagner du temps).

##  Objectif pédagogique

Ce projet s’inscrit dans le cadre d’un **projet étudiant du CFA INSTA**, visant à mettre en pratique les compétences en :

* développement web,
* conception et modélisation de base de données,
* architecture MVC,
* UX/UI design,
* et gestion de projet numérique.

Il illustre la conception d’une plateforme complète alliant **sport, technologie et expérience utilisateur**.

---

##  Structure du projet

Le projet est organisé selon une **architecture MVC (Modèle – Vue – Contrôleur)**, qui permet une meilleure séparation du code et une maintenance facilitée.
Chaque dossier a un rôle précis :

###  **/bdd/**

Contient tous les fichiers liés à la **base de données** (scripts SQL, fichiers de connexion, etc.).

>  **Important :**
> Lors de la connexion à votre base de données en local, **ajoutez un commentaire** dans le code indiquant **l’ancien lien de connexion** et, si possible, **le nom de la personne à qui il appartenait**.
> Si vous modifiez le fichier, **stashé le** avant de pousser vos commits sur le dépôt Git pour **éviter de publier des informations sensibles** (identifiants, adresses locales, etc.).

---

###  **/controller/**

Contient les **contrôleurs** gérant la logique entre le modèle (données) et la vue (interface utilisateur).

> Exemple :
> Vous pouvez rencontrer une URL du type :
> `http://localhost/chauffeurs/index.php?page=accueil`(ceci n'est qu'un exemple)
>
> Cette ligne peut varier selon les environnements locaux.
> Pensez donc à **commenter l’ancien lien** ou à **stashé le fichier** avant de le pousser sur le dépôt afin d’éviter tout conflit ou mauvaise redirection entre développeurs.

---

###  **/model/**

Contient les **modèles** : la couche responsable de la gestion des données (connexion à la base, requêtes SQL, etc.).

Les modèles communiquent avec les contrôleurs pour envoyer ou récupérer les informations nécessaires à l’application.

---

###  **/view/**

Regroupe les **vues**, c’est-à-dire les pages visibles par l’utilisateur (HTML, CSS, JS, etc.).
Elles affichent les données transmises par les contrôleurs.

---

###  **/docs/**

Dossier réservé à la **documentation du projet**.
Vous pouvez y placer :

* des fichiers expliquant le fonctionnement de certaines parties du code,
* le MCD ou le schéma de la base de données,
* des notes techniques ou consignes de développement.

---

##  À propos du MCD

Le **MCD (Modèle Conceptuel de Données)** est une représentation schématique des données utilisées dans le projet.
Il permet de définir :

* les **entités** (ex. : Utilisateur, Programme, Exercice, Objectif…),
* leurs **attributs** (ex. : nom, âge, email…),
* et les **relations** entre elles (ex. : un utilisateur peut suivre plusieurs programmes).

Le MCD est une étape essentielle pour structurer la base de données avant sa mise en œuvre technique.
le faire et le mettre de le dossier MCD

---

##  Bonnes pratiques de collaboration

* Ne **poussez jamais vos fichiers de configuration locale** (base de données, chemins spécifiques…).
* Utilisez les **commentaires** pour indiquer vos modifications locales.
* **Stashez** les fichiers sensibles avant de faire un commit.
* Respectez la structure MVC pour garder le projet clair et maintenable.

