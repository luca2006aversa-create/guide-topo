# Guide « Topographie et bâti 3D » — consignes pour Claude

Site statique : tout le site est dans `index.html` (styles, mise en page,
schémas), avec les PDF FR/EN à côté. Publié par GitHub Pages depuis `main` :
https://luca2006aversa-create.github.io/guide-topo/ — chaque push sur `main`
met le site en ligne à jour en une minute environ.

## Git et GitHub (demandé par l'utilisateur le 02/10/2026)

Dépôt public : https://github.com/luca2006aversa-create/guide-topo.
L'utilisateur modifie depuis son PC **et** depuis son téléphone
(claude.ai/code). Il débute avec Git : expliquer simplement, en français.

- **Avant toute modification : `git pull --ff-only`.** Si le pull échoue,
  régler ça d'abord.
- **Petite modif** (texte, correction, style) : directement sur `main`,
  commit, puis `git push` (le site en ligne change aussitôt).
- **Grosse modif** (nouvelle partie, refonte, gros changement de mise en
  page) : branche `feature/<nom-court>`, poussée sur GitHub, fusionnée dans
  `main` seulement quand l'utilisateur a validé — car `main` = site public.
- Garder les PDF à côté de `index.html` : les liens en bas du site en dépendent.
- Dépôt public : n'y mettre aucune donnée personnelle ni secret.
- **À la fin de chaque gros changement**, montrer un arbre des fichiers
  (+ ajouté, ~ modifié, − supprimé, une ligne d'explication) et un petit
  schéma des branches, en texte/ASCII ou Mermaid `gitGraph`.
