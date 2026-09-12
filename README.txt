ZERO — wearezero.fr
Fichiers du site

CONTENU
-------
index.html          Le site complet (template, logique, polices, animations inclus).
assets/             Les portraits utilises par la section Constellation.
                      p-david.jpg, p-frederik.jpg, p-sandrine.jpg,
                      p-sophie.jpg, p-thierry.jpg
vercel.json         Configuration d'hebergement (URLs sans extension).

MISE EN LIGNE (Vercel, deja en place)
-------------------------------------
Pousser sur la branche main du depot GitHub : le deploiement est automatique.

MISE EN LIGNE (hebergeur classique : OVH, o2switch, Infomaniak...)
------------------------------------------------------------------
Envoyer index.html et le dossier assets/ a la racine de l'espace web
(souvent /www ou /public_html) via FTP. Aucune base de donnees, aucun
serveur particulier requis.

POUR UN DEVELOPPEUR
-------------------
Le site est une page unique, sans dependance externe ni build : index.html
contient le markup, la logique et les ressources embarquees en base64.
Les modifications se font directement dans index.html.
Palette : blanc casse #F9F7EF, vermillon #E94E1B, gris perle #CFDDE2, jaune #FFED00.
Polices : Bodoni Moda, Archivo, JetBrains Mono (Google Fonts, deja embarquees).

RESTE A FOURNIR
---------------
- Photo et bio de Ronald Akili (carte retiree en attendant).
- Version portrait de la photo de David Tuchbant (l'actuelle est un recadrage
  d'une image paysage, passee en noir et blanc).
