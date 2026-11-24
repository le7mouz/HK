# Rassw9ida — portfolio

Portfolio de Hamza Kabori, alias Rassw9ida.
Musique, image et installation. Master 2 Création contemporaine et nouvelles technologies, option art numérique, Université Jean Monnet, Saint-Étienne.

Contact : kaborihamza@gmail.com

## Contenu

Le site se lit comme l'EP *Rattrapage* : chaque section porte le nom d'une piste.

| Piste | Projet |
|---|---|
| Départ | Présentation |
| Apocalypse | EP *Rattrapage*, pochette, clip, tracklist |
| Obstacles | *Maison funéraire*, mini-documentaire sur Saint-Étienne |
| Mazal | *Allumette*, installation interactive TouchDesigner et Kinect |
| Dakira | Exposition au Cyclorama, Saint-Étienne, 12 mai 2026 |
| Clear | Contenu Reels et TikTok pour des commerces |
| Volet II | *Soufre / The Floor is Lava*, projet de Master 2 |

## Structure

```
index.html          la page (HTML, CSS et JS dans un seul fichier)
assets/             photos, vidéos, affiches
assets/cv/          les trois CV en PDF (sans adresse postale)
.nojekyll           indique à GitHub Pages de servir les fichiers tels quels
```

Aucune dépendance, aucun build. Les polices viennent de Google Fonts.

## Mettre en ligne avec GitHub Pages

1. Crée un dépôt sur GitHub, par exemple `rassw9ida`.
2. Envoie tout le contenu de ce dossier à la racine du dépôt (glisser-déposer dans « Add file > Upload files », ou `git push`).
3. Dans le dépôt : **Settings > Pages**, source **Deploy from a branch**, branche `main`, dossier `/ (root)`, puis **Save**.
4. Après une minute, le site est en ligne à l'adresse `https://<ton-pseudo>.github.io/rassw9ida/`.

Pour avoir l'adresse courte `https://<ton-pseudo>.github.io/`, nomme le dépôt `<ton-pseudo>.github.io`.

## Voir le site en local

Ouvre `index.html` dans un navigateur, ou lance un petit serveur dans ce dossier :

```
python -m http.server 8000
```

puis va sur http://localhost:8000.
