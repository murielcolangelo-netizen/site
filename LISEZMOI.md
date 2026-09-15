# Site de Muriel Colangelo — Guide de mise en ligne

## Photo de fond de l’accueil
Dans l’administration → « Informations du site » → « Photos, biographie, contact et expositions », importez une image dans « Photo de fond de l’accueil ». Réglez « Transparence du fond (%) » (80 conseillé pour une image discrète), puis cliquez sur « Publish ». La photo reste entière derrière le nom et le portrait. Supprimez ce champ image pour retrouver le fond uni.

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
- Modifier les expositions : admin → « Informations du site » → « Photos, biographie, contact et expositions » → « Expositions ». Ajoutez, modifiez ou supprimez une entrée (année, exposition, lieu), glissez les entrées pour changer leur ordre, puis cliquez sur « Publish ».
- Les champs « Photo d’accueil » et « Photo À propos » permettent de choisir deux photos indépendantes. Téléversez une image dans chaque champ, puis cliquez sur « Publish » ; leurs proportions sont conservées.
- L'ordre des œuvres se change en glissant les entrées.
- Ajouter des œuvres à une exposition : ouvrez l’exposition dans « Informations du site », puis « Œuvres de cette exposition » → « + ». Choisissez une image depuis votre ordinateur ou la médiathèque et renseignez le titre (technique, année et dimensions facultatives). Cliquez sur « Publish ». Les œuvres s’affichent sous cette exposition, sans recadrage ; cette liste est indépendante de la galerie principale.

- Modifier les textes fixes : admin → « Textes du site » → « Tous les textes et libellés ». Nom, menus, titres, citation, pied de page et messages sont personnalisables. Les biographies, expositions et titres d’œuvres restent dans leurs rubriques habituelles. Cliquez sur « Publish » pour publier.
