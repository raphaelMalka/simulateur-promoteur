# Simulateur promoteur — Surface à construire

Petit outil web (une seule page, sans dépendances) qui résout la surface SBP à
construire pour atteindre un rendement annuel cible sur les fonds propres d'une
promotion immobilière.

## Fonctionnalités

- Calcul en temps réel de la surface nécessaire
- Curseurs pour les taux et le financement (rendement cible, TVA, IS, crédit…)
- Onglet **Vérification** (décomposition du coût, résultat net, rendement obtenu)
- Onglet **Hypothèses** (limites du modèle)
- **Sauvegarde nommée** des calculs dans le navigateur (`localStorage`)
- Liste des calculs enregistrés : charger / supprimer

## Utilisation locale

Ouvre simplement `index.html` dans un navigateur — aucune installation.
Les calculs sauvegardés sont stockés dans le `localStorage` du navigateur
(propre à chaque appareil/navigateur, pas de serveur).

## Structure

```
simulateur-promoteur/
├── index.html      ← toute l'application (HTML + CSS + JS)
├── README.md
└── .gitignore
```

## Déploiement

Site 100 % statique : Vercel sert `index.html` à la racine automatiquement,
aucune configuration nécessaire. Voir les étapes GitHub + Vercel plus bas.
