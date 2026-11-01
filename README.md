# CS Network Rennes

Site vitrine et plaquette partenaires 2026-2027 de CS Network Rennes, l'association qui relie les étudiants du campus de Rennes de CentraleSupélec aux alumni.

- `site/` : le site web (accueil `index.html`, page `stages.html`, styles `style.css`). Publié sur https://cs-network-rennes.rezo-rm.fr, une VM fournie par Rézo : nginx sert `/var/www/csnetworks/site`, un clone de ce dépôt.
- `index.html` (racine) : source A4 de la plaquette, imprimée en `CS_Network_Rennes_plaquette.pdf` avec Edge en mode headless.

Mettre le site en ligne après une modification de `site/` : commiter, pousser sur `main`, puis

```
ssh csnetworks@cs-network-rennes.rezo-rm.fr "cd /var/www/csnetworks && git pull"
```
