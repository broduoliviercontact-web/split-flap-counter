# Split-Flap Counter

Compteur split-flap affichant le nombre de victimes de violences sexuelles enregistrées en France, basé sur les données officielles du SSMSI (Ministère de l'Intérieur).

**Démo :** [mineral-onyx-6zxa.here.now](https://mineral-onyx-6zxa.here.now/)

## Stack

- [`<hotfx-split-flap>`](https://fx.hot.page/split-flap) web component
- Web Audio API (sons mécaniques polyphoniques)
- Son unique en `index.html` (base64 inline)

## Données

- **Source :** SSMSI / Ministère de l'Intérieur
- **Total 2025 :** 132 300 victimes de violences sexuelles enregistrées
- **Projection :** répartie linéairement sur 365 jours, affichée proportionnellement à la date actuelle

## Déploiement

```bash
bash ~/.hermes/hermes-agent/optional-skills/productivity/here-now/scripts/publish.sh index.html --title "Violences sexuelles enregistrées en France"
```