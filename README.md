# 🚗 Prospectus Auto-École Vertueux

Un prospectus commercial moderne et professionnel pour auto-école, optimisé pour l'impression et la présentation digitale.

## 📋 Description du Projet

Ce projet contient un prospectus HTML interactif conçu spécifiquement pour l'auto-école Vertueux. Le document présente la "Formule Sérénité Permis" avec un design moderne qui reflète l'identité visuelle de l'entreprise.

## ✨ Fonctionnalités

### 🎨 Design & Identité Visuelle
- **Palette de couleurs** cohérente avec les véhicules floqués (rouge #dc2626 et gris métallique #6b7280)
- **Logo intégré** avec placeholder intelligent et système de détection automatique
- **Icônes SVG professionnelles** remplaçant tous les emojis pour un rendu optimal
- **Design responsive** s'adaptant à tous les écrans

### 📄 Structure du Document
1. **En-tête compact** avec logo et informations principales
2. **Section philosophie** - Présentation de la mission
3. **Formule détaillée** - 5 étapes clairement définies
4. **Avantages exclusifs** - 4 points différenciants
5. **Investissement** - Prix et facilités de paiement
6. **Témoignages clients** - Preuves sociales
7. **Appel à l'action** - Coordonnées et contact

### 🖨️ Optimisation Impression
- **Format condensé** sur maximum 2 pages
- **Styles d'impression** dédiés avec gestion des sauts de page
- **Bouton d'export PDF** intégré
- **Typographie optimisée** pour la lisibilité papier

### 🔧 Fonctionnalités Techniques
- **Diagnostic automatique** du logo avec test de plusieurs chemins
- **Fallback intelligent** en cas d'erreur de chargement
- **Console de débogage** pour faciliter l'intégration
- **CSS print-ready** avec classes spécialisées

## 🛠️ Technologies Utilisées

- **HTML5** - Structure sémantique
- **Tailwind CSS** - Framework CSS utilitaire via CDN
- **JavaScript Vanilla** - Gestion du logo et diagnostics
- **SVG** - Icônes vectorielles haute qualité
- **Google Fonts** - Typographies Inter et Open Sans

## 📁 Structure du Projet

```
📦 docs/
├── 📄 prospectus-auto-ecole.html     # Document principal
├── 📁 img/
│   └── 🖼️ logo_red.png              # Logo de l'auto-école
├── 📋 README.md                      # Documentation du projet
└── 📄 cursor_cr_er_un_prospectus_efficace_pou.md  # Documentation détaillée
```

## 🚀 Utilisation

### Installation
1. Clonez le repository :
```bash
git clone https://github.com/twenty0603/docs.git
cd docs
```

2. Ouvrez le fichier dans votre navigateur :
```bash
open prospectus-auto-ecole.html
```

### Personnalisation

#### Logo
Le système détecte automatiquement le logo dans plusieurs emplacements :
- `img/logo_red.png` (recommandé)
- `logo_red.png` (racine)
- `./img/logo_red.png`
- `../img/logo_red.png`
- `assets/logo_red.png`

#### Informations à personnaliser
Remplacez les placeholders suivants dans le HTML :
- `[NOM AUTO-ÉCOLE]` - Nom de votre auto-école
- `[PRIX]` - Prix de votre formule
- `[Votre Adresse]` - Adresse complète
- `[Votre Numéro]` - Numéro de téléphone
- `[Votre Email]` - Adresse email
- `[Votre Site]` - Site web

#### Couleurs
Modifiez la palette dans la configuration Tailwind :
```javascript
colors: {
    primary: '#dc2626',    // Rouge principal
    secondary: '#6b7280',  // Gris métallique
    accent: '#f8fafc',     // Blanc cassé
    dark: '#374151',       // Gris foncé
    light: '#e5e7eb'       // Gris clair
}
```

## 📱 Export PDF

1. Ouvrez le document dans votre navigateur
2. Cliquez sur le bouton "🖨️ Imprimer PDF"
3. Sélectionnez "Enregistrer au format PDF"
4. Choisissez les paramètres d'impression optimaux

## 🎯 Stratégie Marketing

Le prospectus suit une approche de vente structurée :
- **Accroche émotionnelle** - Compréhension des difficultés
- **Solution structurée** - Processus en 5 étapes claires
- **Différenciation** - Avantages exclusifs mis en avant
- **Preuve sociale** - Témoignages clients authentiques
- **Appel à l'action** - Contact facilité

## 🔍 Diagnostic et Débogage

Le document inclut un système de diagnostic automatique :
- Vérification du chargement du logo
- Messages de console détaillés
- Instructions d'intégration automatiques
- Fallback en cas d'erreur

Ouvrez la console développeur (F12) pour voir les messages de diagnostic.

## 📈 Optimisations SEO et Performance

- **Sémantique HTML5** pour l'accessibilité
- **Images optimisées** avec attributs alt
- **Chargement rapide** via CDN Tailwind
- **Responsive design** mobile-first

## 🤝 Contribution

Pour contribuer au projet :
1. Forkez le repository
2. Créez une branche feature (`git checkout -b feature/amelioration`)
3. Commitez vos changements (`git commit -m 'Ajout fonctionnalité'`)
4. Poussez vers la branche (`git push origin feature/amelioration`)
5. Ouvrez une Pull Request

## 📄 Licence

Ce projet est sous licence MIT. Voir le fichier `LICENSE` pour plus de détails.

## 📞 Contact

Pour toute question concernant ce projet :
- **Repository** : [https://github.com/twenty0603/docs](https://github.com/twenty0603/docs)
- **Issues** : [https://github.com/twenty0603/docs/issues](https://github.com/twenty0603/docs/issues)

---

*Développé avec ❤️ pour l'Auto-École Vertueux* 