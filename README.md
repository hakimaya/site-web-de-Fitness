# Élan Fitness – Site multipage

Projet réalisé dans le cadre de ma formation à YouCode : migrer le site one pager d'Élan Fitness vers un site de plusieurs pages reliées entre elles.

## Lien du site
https://hakimaya.github.io/site-web-de-Fitness/

## Présentation du projet
Élan Fitness est une salle de sport à Casablanca. Son site était à l'origine une seule page. Je l'ai transformé en un site de 4 pages avec un menu commun, pour que les visiteurs trouvent plus facilement ce qu'ils cherchent.

## Pages réalisées
- **Accueil** : présentation de la salle et chiffres clés.
- **À propos** : histoire, valeurs et avantages de la salle.
- **Programmes** : les cours et les formules d'abonnement.
- **Contact** : coordonnées, formulaire de message et plan d'accès.

## Technologies utilisées
- HTML5
- CSS3
- Git et GitHub
- GitHub Pages (hébergement)

## Structure du projet
```
index.html
apropos.html
programmes.html
contact.html
style.css
img/
README.md
```

## Déroulement du travail

### Jour 1
- J'ai créé le dépôt GitHub.
- J'ai créé les fichiers du projet.
- J'ai commencé à relier les pages entre elles.

### Jour 2
- J'ai fini de relier les pages.
- J'ai déplacé le contenu de l'ancienne page unique vers la bonne page.
- J'ai écrit un titre et une description différents pour chaque page.

### Jour 3
- J'ai copié l'en-tête et le pied de page sur les pages.
- J'ai ajouté un 4e lien « Contact » dans le menu.

### Jour 4
- J'ai terminé la page Contact.
- J'ai stylisé le formulaire pour qu'il corresponde au reste du site.
- J'ai vérifié que tous les liens fonctionnent sur toutes les pages.
- J'ai mis le site en ligne avec GitHub Pages.

## Ce que j'ai appris
- Comment transformer une seule page en plusieurs pages reliées entre elles.
- Comment utiliser un seul fichier CSS pour toutes les pages, afin que le site garde le même style partout.
- Pourquoi l'en-tête et le pied de page doivent être identiques sur chaque page, et pourquoi le titre et la description, eux, doivent changer.
- Comment utiliser Git et GitHub : `git add`, `git commit` et `git push`, avec des messages clairs.
- Comment mettre un site en ligne avec GitHub Pages.
- Comment construire un formulaire : les champs, leurs étiquettes, et le bouton d'envoi.

## Difficultés rencontrées et solutions
- **Connexion à GitHub sur l'ordinateur de l'école :** mes envois échouaient avec l'erreur « Repository not found ». Le problème venait de la connexion enregistrée sur l'ordinateur, qui appartenait à quelqu'un d'autre. J'ai compris que Git garde en mémoire un compte, et j'ai dû vérifier le compte utilisé pour envoyer mon travail.
- **Liens entre les pages :** au début, mes liens menaient vers des sections de la même page (`#accueil`). J'ai appris à les remplacer par les noms des fichiers (`index.html`, `programmes.html`...), pour que la navigation fonctionne entre les pages.
- **Structure des pages :** j'avais d'abord mis l'en-tête à l'intérieur de la balise `<main>`. J'ai appris qu'il doit être placé avant, avec le pied de page après.

## Auteure
Aya – étudiante à YouCode
