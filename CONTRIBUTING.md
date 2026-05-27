# Contribuer a xeinoria-scripts-global

Merci de contribuer au reseau Xeinoria.

## Workflow recommande

1. Fork ou branche locale depuis `main`.
2. Nommer la branche clairement:
   - `fix/nom-court`
   - `feat/nom-court`
   - `chore/nom-court`
3. Faire des commits atomiques avec message explicite.
4. Ouvrir une Pull Request avec:
   - contexte du changement
   - impact gameplay attendu
   - addons ou prerequis touches
   - captures/logs utiles si necessaire

## Regles de code Skript

- Garder un style simple et lisible.
- Eviter les effets de bord globaux non documentes.
- Centraliser les helpers communs dans `lib/`.
- Ne pas dupliquer un script deja present dans un repo serveur.
- Commenter seulement les blocs complexes (pas les evidences).

## Validation minimale avant PR

- Le script se recharge sans erreur (`/sk reload <script>`).
- Le comportement est teste en jeu (cas nominal + cas limite principal).
- Aucun secret ni donnee sensible dans le diff.
- La doc est mise a jour si le comportement utilisateur change.

## Securite

Ne jamais commiter:
- mots de passe
- tokens/API keys
- endpoints internes sensibles
- donnees personnelles non anonymisees

Si vous detectez une faille, contactez les mainteneurs en prive.
