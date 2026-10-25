# JNM 2027 – Site web

Site vitrine des **Journées Nationales MIAGE 2027** (JNM 2027), du **26 au 28 mai 2027**
à **Polytech, Université Lyon 1** (campus LyonTech – La Doua, Villeurbanne).

## Contraintes du projet

- Une seule page, entièrement en **français**.
- **HTML et CSS simples** uniquement : pas de framework, pas de JavaScript obligatoire,
  aucun outil à installer, aucune étape de compilation.
- Le site doit rester **lisible sur mobile** (mise en page responsive en CSS).
- Le site est publié tel quel avec **GitHub Pages** depuis la racine du dépôt.
- La personne qui maintient le site débute en programmation : garder un code clair,
  commenté en français, et expliquer simplement les changements.

## Fichiers

- `index.html` : la page unique. Sections dans l'ordre : `#accueil`, `#presentation`,
  `#equipe`, `#programme`, `#inscription`, `#lieu`, `#partenaires`, `#contact`.
- `style.css` : toute la mise en forme. Les couleurs sont définies dans les variables
  `:root` en haut du fichier.
- `images/equipe/` : photos des membres de l'équipe organisatrice (de préférence carrées,
  affichées en rond). `photo-a-venir.svg` est l'image provisoire.
- `images/partenaires/` : logos des partenaires, affichés à gauche de leur nom.
  `logo-a-venir.svg` est l'image provisoire.
- `.nojekyll` : fichier vide qui indique à GitHub Pages de servir les fichiers tels quels.
- `README.md` : présentation rapide du dépôt et de la publication.

## Textes provisoires

Les informations manquantes sont marquées **`[À COMPLÉTER]`** (et `[Heure]` dans le
programme), dans des encadrés jaunes (classe CSS `a-completer`). Pour retrouver ce qu'il
reste à faire, rechercher `À COMPLÉTER` dans `index.html`. Une fois un texte rempli,
retirer aussi la classe `a-completer` du paragraphe.

Les noms et rôles de l'équipe, les tarifs et le lien du bouton « S'inscrire » (`href="#"`)
sont aussi provisoires. L'inscription se fait sur une plateforme externe : GitHub Pages ne
peut pas recevoir de formulaire.

L'adresse et les informations d'accès (tram T1/T4, Part-Dieu, Rhônexpress) sont à
vérifier auprès des organisateurs. L'adresse e-mail `contact@exemple.fr` est factice.

## Tester en local

Ouvrir `index.html` directement dans un navigateur (double-clic). Aucun serveur n'est
nécessaire.

## Publication (GitHub Pages)

Dans le dépôt GitHub : **Settings → Pages → Build and deployment**, source
« Deploy from a branch », branche `main`, dossier `/ (root)`.
