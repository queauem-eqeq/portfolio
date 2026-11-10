# Portfolio Emmanuel Quéau — mise en ligne sur GitHub Pages

Contenu : index.html (le site), img/ (434 photos), robots.txt (demande aux moteurs de ne pas indexer), .nojekyll.

## Avec GitHub Desktop (le plus simple, pas de ligne de commande)
1. Installer GitHub Desktop et se connecter à son compte GitHub.
2. File > New repository : nom `portfolio`, dossier local = le dossier qui contient ces fichiers.
   Cocher « Initialize with README » : NON.
3. Commit to main, puis « Publish repository ». Visibilité : Public (obligatoire pour Pages en gratuit).
4. Sur github.com : dépôt > Settings > Pages > Source « Deploy from a branch » > branche `main`, dossier `/ (root)` > Save.
5. Après 1 à 2 minutes, le site est à : https://VOTRE-IDENTIFIANT.github.io/portfolio/

## En ligne de commande
    cd dossier-du-site
    git init -b main && git add -A && git commit -m "Portfolio"
    git remote add origin https://github.com/VOTRE-IDENTIFIANT/portfolio.git
    git push -u origin main
Puis l'étape 4 ci-dessus.

## Attention
- Le dépôt est PUBLIC : les photos sont téléchargeables par quiconque trouve l'adresse du dépôt.
- Ne pas déposer par glisser-déposer sur le site github.com : limite de 100 fichiers par envoi.
