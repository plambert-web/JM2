# L-UNIVERS-DES-SERVICES-DE-JM

service d'aides à la personne

Site statique pour service d’entretien et maintenance à domicile, travaux de jardinage/bricolage et soins d’animaux.

## Structure du projet

- `index.html` : page principale (3 sections clefs + contact)
- `styles.css` : styles visuels, responsive mobile

## Lancer localement

1. Ouvrir `index.html` dans un navigateur (cas le plus simple).
2. Ou via un serveur local (recommandé) :

```bash
cd "/Users/paullambert/Desktop/site JM/site VS"
python3 -m http.server 8000
```

Puis visiter http://localhost:8000.

## Déploiement rapide

- GitHub Pages : déposer dans un repo, activer Pages sur `main` / `gh-pages`.
- Netlify : glisser-déposer le dossier ou connecter le dépôt Git.

## Évolutions suggérées

- Formulaire de contact + traitement via Formspree / Netlify forms.
- Ajout d’icônes (Font Awesome / SVG inline).
- Ajout d’un script JS pour navigation fluide et feedback de bouton.
- Améliorer accessibilité (labels explicites, état `aria-expanded`).
