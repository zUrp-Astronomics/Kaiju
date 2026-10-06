# 9_Assets

**Date** : 2026-10-06
**Dernière révision** : 2026-10-06 — affiche « or » en vitrine, l'originale rouge gardée à côté
**Statut** : actif
**Référencé par** : `README.md` (§ Repository layout), le site zurp-astronomics.github.io

Les ressources de Kaiju pour l'extérieur : images des README et de la doc, et la **vitrine** lue
par le site de l'org.

| fichier | rôle |
|---|---|
| `zurp.yml` | la fiche vitrine de Kaiju, lue par le site au build (commentée) |
| `kaiju-gold.png` | l'affiche (« or », série 2.2), nommée par le champ `poster:` de la fiche, 1254 × 1254 |
| `kaiju.webp` | l'affiche d'origine (rouge), gardée à côté ; non lue par le site, 1254 × 1254 |
| le reste | les images des README et de la doc, librement |

Le site ne lit **que** ce dossier, plus ce que GitHub sait du dépôt (releases, licence détectée dans
`LICENSE`). Tout push dans `9_Assets/` sur `main` reconstruit le site
(`.github/workflows/zurp-site.yml`).
