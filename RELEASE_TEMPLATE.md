# Release v1.2.1

## FR - Resume

- Correction de la persistance runtime des reglages (`rateLimitSeconds`, `commentsPerPage`) pour appliquer les valeurs du back-office.
- Correction de compatibilite pour les environnements sans extension `mbstring`.
- Ajout d'une couche i18n complete: anglais par defaut, francais selon la langue du site.
- Correction de la detection de langue Bludit avec fallbacks robustes.
- Filtrage de l'onglet moderation: seules les pages avec commentaires actives sont affichees.

## EN - Summary

- Fixed runtime settings persistence (`rateLimitSeconds`, `commentsPerPage`) so back-office values are applied correctly.
- Added compatibility fallback for environments without `mbstring`.
- Added complete i18n layer: English default, French override based on site language.
- Improved Bludit locale detection with robust fallbacks.
- Updated moderation tab filtering to show only pages with comments enabled.

## Upgrade notes

- Aucun changement de migration requis.
- No migration is required.

## Maintainer

- Author: Green Effect
- Contact: contact@green-effect.fr
- Website: https://www.green-effect.fr
