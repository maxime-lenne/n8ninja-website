# N8Ninja Landing Page

Landing page moderne et responsive pour l'application mobile N8Ninja, une application iOS permettant de gérer et surveiller les workflows n8n depuis un iPhone.

## 🎯 Objectif

Cette landing page a été conçue pour :
- Expliquer ce qu'est N8Ninja et ses bénéfices
- Présenter les fonctionnalités principales de l'application
- Rassurer les utilisateurs techniques sur la compatibilité avec n8n
- Booster les installations sur l'App Store
- Améliorer le référencement SEO/ASO

## 🎨 Design

### Charte graphique
- **Couleurs principales** : Corail n8n (#FF6D6D), Noir (#1A1A1A), Gris foncé (#2B2B2B), Blanc (#FFFFFF)
- **Police** : Inter / SF Pro Display pour les titres, Inter Regular pour le texte
- **Style** : Fond sombre avec dégradés, icônes minimalistes, style flat/tech, lignes arrondies

### Fonctionnalités visuelles
- Design responsive (mobile-first)
- Animations fluides et interactions
- FAQ interactive avec accordéon
- Galerie de screenshots avec effets hover
- Navigation fluide avec scroll smooth

## 📁 Structure du projet

```
n8ninja-website/
├── N8Ninja Landing Page.html    # Page principale
├── style.css                    # Styles CSS
├── README.md                    # Documentation
├── docs/                        # Documentation du projet
│   ├── conventions.md           # Charte graphique et objectifs
│   ├── features.md              # Fonctionnalités de l'app
│   └── screen_flow.md           # Flux de navigation de l'app
└── images/                      # Assets visuels
    ├── logos/                   # Logos N8Ninja
    ├── screenshots/             # Captures d'écran de l'app
    └── app-store-previews/      # Images pour l'App Store
```

## 🚀 Déploiement

Cette landing page est conçue pour être hébergée sur des plateformes JAMstack :

### GitHub Pages
1. Poussez le code sur un repository GitHub
2. Activez GitHub Pages dans les paramètres du repository
3. Sélectionnez la branche principale comme source

### Vercel
1. Connectez votre repository GitHub à Vercel
2. Vercel détectera automatiquement qu'il s'agit d'un site statique
3. Le déploiement se fera automatiquement à chaque push

### Scaleway
1. Uploadez les fichiers sur un bucket Object Storage
2. Configurez un CDN pour servir les fichiers statiques
3. Configurez un domaine personnalisé si nécessaire

## 📱 Fonctionnalités de l'application N8Ninja

### Gestion des serveurs
- Connexion à plusieurs instances n8n (cloud et auto-hébergées)
- Gestion des tokens API de manière sécurisée
- Basculement facile entre différents serveurs

### Gestion des workflows
- Visualisation de tous les workflows avec leur statut
- Activation/désactivation en un tap
- Filtrage par statut et tags
- Statistiques et distribution par tags

### Suivi des exécutions
- Liste des exécutions récentes avec statut détaillé
- Filtrage par statut (succès, erreur, en cours, en attente)
- Graphiques et statistiques temporelles
- Informations détaillées sur la durée et les performances

### Gestion des déclencheurs
- Déclenchement manuel de webhooks
- Partage d'URLs de webhook
- Gestion des planifications
- Interaction avec les triggers de chat

### Intégrations
- Support complet des Raccourcis iOS
- Intégration Siri pour contrôle vocal
- Support multi-plateforme (iOS, macOS, tvOS)

## 🔧 Technologies utilisées

- **HTML5** : Structure sémantique et accessible
- **CSS3** : Styles modernes avec variables CSS, Grid, Flexbox
- **JavaScript vanilla** : Interactions et animations légères
- **Google Fonts** : Police Inter pour une typographie optimale

## 📊 SEO et Performance

### Optimisations SEO
- Meta tags complets (description, keywords, Open Graph)
- Structure HTML sémantique
- Images avec alt text descriptif
- URLs propres et navigation claire

### Performance
- Images optimisées et responsive
- CSS et JS minifiés
- Chargement asynchrone des polices
- Animations CSS optimisées

## 🎯 Public cible

- **Utilisateurs n8n** : Développeurs et équipes techniques utilisant n8n
- **Professionnels de l'automatisation** : Personnes cherchant à gérer leurs workflows à distance
- **Utilisateurs iOS** : Propriétaires d'iPhone/iPad cherchant des solutions mobiles

## 📞 Support

Pour toute question ou suggestion concernant cette landing page :
- Consultez la documentation dans le dossier `docs/`
- Vérifiez les conventions de design dans `docs/conventions.md`
- Examinez les fonctionnalités détaillées dans `docs/features.md`

---

**N8Ninja** - Simplifiez votre automatisation n8n depuis votre iPhone 📱 