# Booki

Projet de formation OpenClassrooms — intégration HTML/CSS d'une maquette Figma pour un site de recherche d'hébergements et d'activités à Marseille.

## Installation

1. Téléchargez le code (bouton **Code > Download ZIP**) ou clonez le dépôt : `git clone https://github.com/Nicognito23/Booki-.git`
2. Ouvrez le dossier dans votre éditeur de code (VS Code recommandé).
3. Ouvrez `index.html` dans votre navigateur, idéalement via un serveur local (ex : extension Live Server), pour éviter les soucis de chemins relatifs.

## Étapes d'intégration

1. **Environnement** — Installation de l'éditeur, import de la police Raleway via Google Fonts.
2. **Découpage de la maquette** — Identification des blocs, balises HTML associées, sens d'agencement horizontal/vertical.
3. **En-tête** — Logo et navigation alignés en Flexbox, bordure bleue au survol.
4. **Formulaire de recherche** — Champ et bouton, texte/icône adaptés selon le format d'écran.
5. **Filtres** — Pastilles alignées en Flexbox, changement de couleur au survol.
6. **Première carte hébergement** — Structure de carte réutilisable (image, titre, prix, notation).
7. **Sections Hébergements & Populaires** — Duplication des cartes, mise en page complète des deux blocs.
8. **Activités à Marseille** — Grille de 4 cartes de hauteur identique.
9. **Pied de page** — 3 colonnes de liens de largeur égale.
10. **Responsive desktop** — Comportement stable de 1024px à 1440px.
11. **Responsive tablette & mobile** — Media queries à 1024px et 768px, adaptation complète sur tous les formats.

## Validation

Code testé aux validateurs W3C (HTML et CSS).

## Technologies

- HTML5 sémantique
- CSS3 (Flexbox, Grid)
- Google Fonts (Raleway)
- Font Awesome (icônes)