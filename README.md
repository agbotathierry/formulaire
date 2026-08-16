# Sign-up Form — The Odin Project

Formulaire d'inscription réalisé dans le cadre du parcours **Full Stack JavaScript** de [The Odin Project](https://www.theodinproject.com/), projet *Intermediate HTML and CSS*.

##  Démo


[Voir la démo en ligne](TODO: lien GitHub Pages)

##  Objectif du projet

Reproduire une maquette fournie et mettre en pratique les form controls, les validations HTML5 natives et le CSS avancé (flexbox imbriqué, positionnement, pseudo-classes).

##  Technologies utilisées

- HTML5 (formulaire sémantique, `fieldset`/`legend`, types d'input adaptés)
- CSS3 (Flexbox à deux niveaux, `position`, `@font-face`, `box-shadow`, `clamp()`)
- Aucun framework, aucune dépendance externe

##  Fonctionnalités

- Structure responsive-ready en deux colonnes (image + formulaire)
- 6 champs avec les bons `type` (`email`, `tel`, `password`...) et validations HTML5 natives (`required`, `minlength`, `maxlength`)
- Retour visuel sur les champs invalides (`:user-invalid`) et sur le focus (`:focus`)
- Logo custom (police externe `@font-face`) sur overlay semi-transparent
- Micro-interactions au survol du bouton (`:hover`, `transition`)

## Ce que j'ai pratiqué / appris

- Imbrication de deux niveaux de Flexbox (`column` puis `row`) pour organiser des paires de champs
- Différence entre validation côté client (HTML5) et validation côté serveur (indispensable, jamais suffisante seule)
- `background-image` + `background-size: cover` vs `<img>` + `object-fit: cover` (image décorative vs informative)
- Débogage via les DevTools (onglets Éléments, Console, Réseau)

##  Crédits

Photo de fond : **TODO — nom du photographe** ([lien vers son profil Unsplash](TODO)) sur [Unsplash](https://unsplash.com/)
