# Application interface avec un formulaire permettant de consommer une API

![1fdff2ee1ee41e2b800e2328b5160104.png](:/944e19986ad543d488871b0f260651da)

<!-- TOC -->
* [Application interface avec un formulaire permettant de consommer une API](#application-interface-avec-un-formulaire-permettant-de-consommer-une-api)
* [Enoncé](#enoncé)
* [!! Important !!](#--important--)
* [Objectifs / Compétences](#objectifs--compétences)
* [Langages utilisés](#langages-utilisés)
* [Service à utiliser](#service-à-utiliser)
* [Bibliothèque utilisée](#bibliothèque-utilisée)
* [Travail à rendre](#travail-à-rendre)
  * [Points de vigilance](#points-de-vigilance)
* [Barême](#barême)
* [Bonus](#bonus)
  * [Proposition de solution](#proposition-de-solution)
<!-- TOC -->

v 0.3

# Enoncé

En utilisant l'API [JokeAPi](https://sv443.net/jokeapi/v2/), vous allez afficher son contenu dans un tableau.

L'application attendue est une page **mise en forme** (avec le framework CSS que vous voulez).

Elle contiendra un **formulaire** avec un simple **bouton** et un tableau vide.

![63ae10d1e9167f731dd0c352c22fcb0f.png](:/b3ba76eab0514650882cbea3be3b18ac)

Ce bouton fera un appel à l'API et le contenu récupéré sera **ajoutée à un tableau de résultats**.

Ce tableau pourra être, dans son intégralité, **vidé à l'aide d'un bouton**.

Chaque ligne de blague pourra être retirée **individuellement**.

![378c38615bd57a44c5d8363397c4504a.png](:/bddd1c3ad7524132ad0030cdf5c862ce)

> **BONUS**  Ce tableau pourra être sauvegardé en **LocalStorage** afin qu'il soit réaffiché lors d'une visite ultérieure de l'utilisateur.

# !! Important !!

Les données récupérées doivent impérativement:
> Etre en français
> Ne pas être à caractère sexuel, sexiste, politique, raciste, religieux, explicite

# Objectifs / Compétences

> Savoir parcourir un tableau d'objets
	> https://developer.mozilla.org/fr/docs/Learn/JavaScript/Objects/JSON
> Découverte et utilisation de JSON
	> https://developer.mozilla.org/fr/docs/Learn/JavaScript/Objects/JSON
> Maîtriser le protocole HTTP
> Comprendre le mécanisme de requête / réponse
> Utilisation de console.log console.table
> Utilisation des événéments Javascript

# Langages utilisés

> HTML
> Javascript
> CSS

# Service à utiliser

Vous allez utiliser le service **JokeAPI**.
https://jokeapi.dev/

![eed0380afd5d3f25badff00300b64efb.png](:/0841e57d2cd04d70855491d872773ca5)

Ce service (totalement en anglais) vous permet de partir à la recherche de la prochaine **boutade** que vous pourrez sortir auprès de vos amis, et ainsi briller en société.

> **Attention:** ce service propose des calembours dans plusieurs langues. Mais, il propose également de l'humour qui n'aura **absolument** pas sa place dans ce TP. Ainsi, vous serez sanctionné si vous laissez apparraître des galigeades ayant trait sur des sujets _sexistes_, _racistes_ ou autres thèmes controversés.

# Bibliothèque utilisée

> Bootstrap, TailWind, Foundation, Bulma, Material...

# Travail à rendre

> Votre application devra être disponible sur votre VM avec le chemin:
	> http://**VOTRE_IP**/B2/TP_API
	> Vous m'enverrez cette adresse par Discord en message privé.
> Envoyer son code via un dépôt GitHub
> L'application DOIT utiliser une librairie CSS (au choix) pour embellir vos formulaires
> Votre dépôt DOIT préciser et expliquer vos choix techniques
> Respecter les consignes demandées

## Points de vigilance

- Organisation du code et des fichiers
- Présentation du projet
- Clarté _(indentation, noms des variables et fonctions)_ et commentaires dans le code

# Barême

* Présentation / Design
    > Vous soignez l'apparence du rendu final
    > 2 points

* Qualité du code / Organisation du dépôt
    > Des commentaires, des indentations
    > 4 points

* Accès sur le serveur
    > Respect des consignes sur la mise en ligne
    > 2 points

* Fonctionnalité
    > Les fonctionnalités demandées sont TOUTES réalisées
    > 2 points

* Non respect du délai: Vous perdez tous les points
---

# Bonus

> Ajouter dans le formulaire la possibilité de sélectionner la catégorie de la blague.
> ![0299967054a0f1ee9711cb923b91e717.png](:/9d7f3bc644304d3f83fc354cd985b38c)
> Sauvegarde des informations dans le LocalStorage

## Proposition de solution

https://github.com/LiliwoL/Javascript-Joke-Generator
