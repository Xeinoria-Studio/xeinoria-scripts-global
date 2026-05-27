# xeinoria-scripts-global

Scripts Skript partages sur l'ensemble du reseau Xeinoria:
- crea
- hub
- nwland
- survie
- test

English summary: shared Skript scripts used across all Xeinoria servers.

## Structure

- `*.sk`: scripts publics communs a tous les serveurs.
- `lib/`: fonctions utilitaires communes (ex: helper d'environnement).
- Les scripts sensibles ou reserves staff sont deplaces hors de ce depot public, dans des depots prives deploiables par webhook.

## Addons requis

Versions actuellement cibles dans l'environnement de dev:

| Addon | Version | Source |
|---|---:|---|
| Skript | 2.15.2 | https://github.com/SkriptLang/Skript/releases |
| skript-reflect | 2.6.3 | https://github.com/SkriptLang/skript-reflect/releases |
| SkBee | 3.22.0 | https://modrinth.com/plugin/skbee |
| skript-db | 1.3.9 | https://github.com/Sashie/skript-db |
| Lusk | 1.3.13 | https://modrinth.com/plugin/lusk |
| SkRedis | 2.3.1 | https://modrinth.com/plugin/skredis |
| SkProxy | 2.4 | https://modrinth.com/plugin/skproxy |
| PlaceholderAPI | 2.12.2 | https://github.com/PlaceholderAPI/PlaceholderAPI/releases |
| VaultUnlocked | 2.17.0+ | https://hangar.papermc.io/TNE/VaultUnlocked |
| skRayFall | 1.9.30 | https://www.spigotmc.org/resources/skrayfall.10012/ |
| PermSk | 2.0.0 | https://www.spigotmc.org/resources/permsk.117962/ |
| skript-placeholders | 1.7.1 | https://www.spigotmc.org/resources/skript-placeholders.103723/ |
| skUtilities | latest compatible | https://www.spigotmc.org/resources/skutilities.70203/ |
| skript-worldguard | 1.0.1 | https://github.com/SkriptLang/skript-worldguard/releases |
| Skript-Translate | 1.2 | (interne reseau) |

## Contribution

Voir [CONTRIBUTING.md](CONTRIBUTING.md).

Resume rapide:
- ouvrir une branche claire (`fix/...`, `feat/...`, `chore/...`)
- tester sur un serveur de dev avant PR
- eviter toute fuite de secrets (token, mot de passe, endpoint interne)
- documenter toute dependance addon nouvelle

## Securite

- Aucun secret ne doit etre commite dans ce repo.
- Les variables sensibles passent via environnement (`.env.shared`) hors depot.
- Les scripts staff/sensibles vont dans les depots prives dedies.

## Licence

Ce projet est sous licence **CC BY-NC-SA 4.0**.
Voir [LICENSE](LICENSE).
