# SME Agadir

Prototype d’un système de monitoring énergétique (SME) des six postes électriques du Port d’Agadir (marché 12/DEPA/2026, Marsa Maroc).

Pages : tableau de bord, compteurs Modbus TCP/IP, IPE, SER, alertes, rapports, accès et audit, recette.

**Les mesures sont simulées.** Aucun compteur réel n’est connecté. Les noms des postes, les registres Modbus, les formules d’IPE, la méthode de la SER et les seuils sont à valider avec la DEPA.

## Structure

- `index.html` : le site et l’application (HTML, CSS et JavaScript dans un seul fichier)
- `vercel.json` : réglages d’hébergement
- `.gitignore`

Aucune installation ni compilation n’est nécessaire : c’est un site statique.

## Tester en local

Ouvrez `index.html` dans un navigateur.

## Déployer sur Vercel

1. Déposez ce dossier sur GitHub.
2. Sur vercel.com : Add New, Project, choisissez le dépôt, puis Deploy.
3. Laissez les réglages par défaut (Framework Preset : Other, aucune commande de build).
