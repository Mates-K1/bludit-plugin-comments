# Changelog

Toutes les evolutions notables de ce plugin sont documentees ici.

## 1.2.1 - 2026-04-17

### Corrections

- Corrige la persistance runtime des reglages admin pour appliquer correctement `rateLimitSeconds` et `commentsPerPage`.
- Corrige un cas de fatal error sur des hebergements sans extension `mbstring` (fallbacks de compatibilite).
- Corrige la detection de locale Bludit avec fallbacks robustes pour appliquer correctement FR/EN.
- Corrige l'onglet moderation pour n'afficher que les pages ou les commentaires sont actives.

### Ameliorations

- Ajoute une couche i18n complete (anglais par defaut, surcharge francaise selon la langue du site).
- Localise les messages front/admin, y compris les retours JS (etats, erreurs, sauvegarde).

## 1.2.0 - 2026-04-17

### Documentation et publication

- Ajoute un `README.md` bilingue FR/EN.
- Ajoute des badges de version, compatibilite Bludit et licence.
- Ajoute `SECURITY.md` et `CONTRIBUTING.md`.
- Met a jour les informations mainteneur (auteur, email, site).

## 1.1.0 - 2026-04-17

### Corrections

- Corrige les soumissions involontaires du formulaire d'administration (toast "modifications sauvegardees" lors du changement d'onglet).
- Corrige le rate limiting pour respecter la valeur de `rateLimitSeconds`.
- Ajoute le comportement `0 = limitation desactivee` pour le delai entre commentaires.

### Nouvelles fonctionnalites

- Implemente le parametre `commentsPerPage` dans la pagination des commentaires front.

### Publication

- Ajoute `README.md`.
- Ajoute `LICENSE` en CC BY-SA 4.0.
- Met a jour les metadonnees (`version`, `releaseDate`, `license`).
