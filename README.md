# Site cadeau

Fichiers : index.html (tout le site), img/ (photos), audio/ (sons).

## Modifier les textes
Ouvre index.html, tout en haut du <script> : l'objet CONTENU. Change les phrases, le mot secret, les dates.

## Fichiers à déposer
img/cadeaux.jpg, img/souvenir1.jpg ... , img/moment1.jpg ..., img/fin.jpg
audio/musique.mp3 (extrait), audio/vocal.mp3 (message vocal)
Ajoute/retire des photos en éditant les listes souvenirs.photos et moments.liste.

## Déployer sur Render (gratuit)
1. Mets le dossier sur GitHub (garde bien img/ et audio/ avec tes fichiers dedans).
2. Render > New > Static Site > choisis le repo.
3. Build Command : vide. Publish Directory : .
4. Deploy. Pas de base de données nécessaire.

## Tester en local
python3 -m http.server 8000  puis ouvre http://localhost:8000
