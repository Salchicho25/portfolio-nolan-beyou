# Portfolio de Nolan Beyou

Portfolio interactif d'un étudiant ingénieur en génie mécanique à l'UTC Compiègne.

**Site en ligne : https://salchicho25.github.io/portfolio-nolan-beyou/**

## Projets présentés

- **Drone à voilure fixe** (Dassault UAV Challenge 2026, association AIR UTC) : visionneuse 3D de la CAO, captures et dossiers de calcul (aérodynamique, structure, centrage, mission).
- **Robot suiveur de ligne** : schéma interactif du fonctionnement.
- **Pédalier de vélo** (projet TN20) : captures CAO, éclaté et schéma animé.
- **Parcours** : formation, expériences et projets sur un plan de métro interactif.

## Technique

Une seule page HTML statique, sans étape de build : HTML, CSS et JavaScript, avec [three.js](https://threejs.org/) r128 pour la visionneuse 3D. Les schémas du robot et du pédalier sont dessinés avec le kit [anatomy](https://github.com/wheresryan22/anatomy) (licence MIT).

Pour l'ouvrir en local, servir le dossier avec un petit serveur (le modèle 3D est chargé en `fetch`) :

```bash
python -m http.server 8000
```

puis ouvrir http://localhost:8000.
