ZERO — wearezero.fr
Fichiers sources du site

CONTENU
-------
index.html          Le site complet, autonome (photos, polices, animations incluses).
                    C'est le SEUL fichier nécessaire pour mettre le site en ligne.

sources/            Les fichiers d'origine, pour toute modification ultérieure.
  ZERO Site v2.dc.html          Le site (template + logique) — le fichier à éditer.
  ZERO Coordinates - jeu alt.dc.html   Variante du jeu de contact (non utilisée).
  support.js                    Runtime nécessaire aux fichiers .dc.html.
  assets/                       Logos, doubles contours, portraits recadrés 1200x1600.

MISE EN LIGNE (le plus simple)
------------------------------
1. Mettre index.html seul dans un dossier.
2. Aller sur netlify.com, créer un compte gratuit.
3. "Add new site" > "Deploy manually" > glisser le dossier.
4. Le site est en ligne sur une adresse .netlify.app.
5. "Domain management" > "Add a domain" > wearezero.fr, puis recopier les
   informations données par Netlify chez le fournisseur du domaine.

MISE EN LIGNE (hébergeur classique : OVH, o2switch, Infomaniak...)
------------------------------------------------------------------
Envoyer index.html à la racine de l'espace web (souvent /www ou /public_html)
via FTP. Aucune base de données, aucun serveur particulier requis.

POUR UN DEVELOPPEUR
-------------------
Le site est une page unique, sans dependance externe ni build.
Les sources .dc.html contiennent le markup et la logique separement ;
index.html est la version compilee et inlinee (tout embarque en base64).
Palette : blanc casse #F9F7EF, vermillon #E94E1B, gris perle #CFDDE2, jaune #FFED00.
Polices : Bodoni Moda, Archivo, JetBrains Mono (Google Fonts, deja embarquees).

RESTE A FOURNIR
---------------
- Photo et bio de Ronald Akili (carte retiree en attendant).
- Version portrait de la photo de David Tuchbant (l'actuelle est un recadrage
  d'une image paysage, passee en noir et blanc).
