# 🚴 GPX Temperature Forecast

Permet de visualiser les températures prévues le long d'un itinéraire à partir d'un fichier GPX.

Les prévisions sont données pour les 16 jours à venir.

Voir la version en ligne : https://sebington.github.io/gpx-forecast/

## Fonctionnalités

- **Ouvrez n'importe quel fichier `.gpx`** — glissez-déposez ou cliquez sur le bouton. Toute l'analyse se fait dans votre navigateur.
- **Prévisions sur 16 jours** — API gratuite [Open-Meteo](https://open-meteo.com), mise en cache localement
- **Coloration en direct** — segments de l'itinéraire colorés selon la température, animables heure par heure
- **Jour et nuit** — le panneau ciel permet d'avoir un aperçu rapide du moment de la journée ou de la nuit
- **Profil d'élévation** — graphique interactif, survolez pour voir l'élévation à n'importe quel point
- **Étiquettes de température** — 10 étiquettes réparties uniformément sur l'itinéraire, colorées et en direct
- **Raccourcis clavier** — `Espace` pour lecture/pause, `←` / `→` pour avancer pas à pas
- **Passer la souris au dessus de la trace** — donne un aperçu de la température à cet endroit
- **Statistiques** — Sur les températures maxi et mini et sur les meilleures conditions (fenêtres) possibles

## Limitations

- **Nombre maximum de points** — le fichier GPX doit faire 1500 points maximum

## Technos utilisées

Leaflet · OpenStreetMap · Open-Meteo · JS vanilla · sans outil de build
