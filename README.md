# Permis bateau moteur Suisse (catégorie A) — Fiches & Quiz

Page web autonome de révision pour l'**examen théorique du permis bateau à moteur catégorie A** en Suisse.

- **10 fiches de révision** thématiques (règles de route, feux & signalisation, signaux acoustiques, balisage, météo, sécurité & équipement, matelotage, environnement, vitesses, cadre légal).
- **Schémas vectoriels (SVG) intégrés** : secteurs des feux, feux par type de bateau et marques de jour, règles de route (croisement / face-à-face / dépassement), signaux sonores, familles de panneaux de balisage, feux d'écluse, zones riveraines et avis météo clignotants. Originaux, sans dépendance réseau ni image externe.
- **126 questions de quiz** à choix multiple, avec explications et référence d'article.
- Modes : 10 questions aléatoires, 20 questions, examen blanc (60 q.), ou toutes les questions, filtrables par thème.
- Options de réponse mélangées à chaque session.
- **Programme adaptatif** : un test de niveau (2 questions/thème, avec une option « Je ne sais pas » pour ne pas fausser l'évaluation en devinant) évalue l'utilisateur, met de côté les thèmes déjà maîtrisés et construit un parcours ciblé sur ce qu'il reste à apprendre. Suivi de complétion par « notion » (chaque question = une notion à valider), barres de progression par thème et anneau global, le tout persisté en `localStorage`. Contrôle manuel « Je connais déjà » / « À revoir », et réinitialisation possible.

## Lancer

Aucune dépendance, aucun build. Ouvrez simplement `index.html` dans un navigateur, ou servez le dossier :

```bash
python3 -m http.server 8777
```

`index.html` charge les données depuis `data.js`.

## Sources

Ordonnance sur la navigation dans les eaux suisses (ONI, RS 747.201.1), OCN, SCAN-NE, MétéoSuisse, boatdriver.ch, schiffsfuehrerausweis.ch.

⚠️ Contenu pédagogique paraphrasé à but de révision — il ne remplace pas le texte officiel ni un cours agréé. Vérifiez toujours la réglementation en vigueur auprès de votre service cantonal de la navigation.
