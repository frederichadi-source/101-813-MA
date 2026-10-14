# Site du cours 101-813-MA

Notes de cours, activités interactives et fiches de laboratoire (HTML autonome ; seules les polices Google sont chargées si internet est disponible).

## Utiliser sans internet
Double-cliquer sur `index.html` : toutes les pages se trouvent dans ce dossier et les liens sont relatifs.
Chaque activité (`coursN/activite_coursN.K_….html`) est aussi un fichier **autonome** : on peut l'envoyer seule
par courriel ou la déposer dans un LMS, sans le reste du site.

## Publier sur GitHub Pages
1. Créer un dépôt (par exemple `101-813`) et y téléverser **le contenu** de ce dossier (`index.html` à la racine).
2. Dans le dépôt : *Settings → Pages → Build and deployment → Deploy from a branch → `main` / `(root)`*.
3. Le site apparaît à `https://<compte>.github.io/<dépôt>/` après une minute ou deux.
Le fichier `.nojekyll` évite que GitHub transforme les fichiers.

## Bandeau de navigation
Dans le site, chaque activité a un bandeau en haut (accueil, notes du cours, menu « Tout le site »). Ce bandeau utilise des liens
relatifs : il ne sert que dans le site. Pour envoyer ou projeter une activité seule, utiliser la copie du dossier
`fichiers-autonomes/` (mêmes fichiers, sans bandeau).

## Ajouter une activité à la main
1. Copier le fichier HTML dans le dossier du cours (`cours6/`, par exemple).
2. Dans `index.html`, copier une ligne `<li>…</li>` de la liste `acts` du cours et adapter le lien et le titre.

## À savoir
- Les corrigés des activités sont protégés par un mot de passe écrit dans le code de la page : un élève qui affiche
  le code source (Ctrl+U) peut le retrouver. Sur un dépôt public, tout le monde peut le lire.
- Chaque activité mémorise le déverrouillage sous une clé qui lui est propre : déverrouiller un corrigé n'en déverrouille pas un autre.
