# Site de Muriel Colangelo — Guide de mise en ligne

## Étape 1 — GitHub (5 min)
1. Créez un compte sur https://github.com
2. Cliquez sur « New repository » → nom : `site-muriel-colangelo` → Public → Create
3. Cliquez sur « uploading an existing file » et glissez-y TOUT le contenu de ce dossier
   (index.html, admin/, content/, static/) → « Commit changes »

## Étape 2 — Netlify (5 min)
1. Créez un compte sur https://app.netlify.com (connexion via GitHub)
2. « Add new site » → « Import an existing project » → GitHub → choisissez votre dépôt
3. Build command : (laisser vide) — Publish directory : `/` → « Deploy »
4. Votre site est en ligne : https://votre-site.netlify.app

## Étape 3 — Activer le panneau d'administration (5 min)
1. Dans Netlify : Site settings → Identity → « Enable Identity »
2. Identity → « Invite users » → entrez votre email → envoyez
3. Services → Git Gateway → « Enable Git Gateway »
4. Ouvrez https://votre-site.netlify.app/admin
5. Cliquez le lien dans l'email d'invitation, choisissez un mot de passe

## Au quotidien
- Ajouter une œuvre : admin → Galerie → Œuvres → « + » → téléversez l'image,
  remplissez titre/technique/année/dimensions → « Publish » → en ligne en ~30 sec.
- Modifier bio, contact ou portrait : admin → « Informations du site ».
- La « Photo portrait — Accueil et À propos » apparaît à côté du nom sur l’accueil et dans la biographie. Téléversez votre photo dans ce champ, puis cliquez sur « Publish » ; ses proportions sont conservées.
- L'ordre des œuvres se change en glissant les entrées.
