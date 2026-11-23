# BrickVault Manager — PWA

## Installation
1. Héberge le contenu de ce dossier sur un hébergement HTTPS statique (par exemple GitHub Pages).
2. Ouvre l'adresse HTTPS dans Chrome sur Android.
3. Menu ⋮ > Installer l'application (ou Ajouter à l'écran d'accueil).

Le service worker permet de mettre en cache l'interface pour un usage hors ligne après le premier chargement.

## Utilisation
1. Crée un projet pour chaque MOC / Wanted List.
2. Dans Synchronisation, importe la Wanted List XML et l'export My Collection XML.
3. Lance la comparaison.
4. Vérifie et complète les noms de pièces et couleurs si nécessaire.
5. Télécharge le XML actualisé et le rapport Excel.

## Limites et précautions
- Les fichiers sont traités localement dans le navigateur.
- Les originaux ne sont pas modifiés.
- La comparaison s'effectue par ITEMTYPE + ITEMID + COLOR.
- La quantité de la Wanted List est lue dans MINQTY (ou QTY si MINQTY absent) ; la quantité de collection dans QTY (ou MINQTY si QTY absent).
- Les noms de pièces/couleurs ne sont pas systématiquement présents dans les XML BrickLink. Les champs sont éditables avant export Excel.
- Les projets et l'historique sont conservés dans le stockage local du navigateur : ils ne sont pas synchronisés entre appareils. Effacer les données du navigateur peut les supprimer.
- Cette version ne se connecte pas au compte BrickLink et ne téléverse rien automatiquement.
