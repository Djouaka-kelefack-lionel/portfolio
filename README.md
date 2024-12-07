# Portfolio 3D Moderne

Un portfolio professionnel avec des effets 3D, des animations fluides et un design moderne inspiré des couleurs arc-en-ciel sur fond sombre.

![Version](https://img.shields.io/badge/version-1.0.0-blue.svg)

## Caractéristiques Principales

### 🎨 Design & Thème
- **Palette de Couleurs**: 
  - Dégradé arc-en-ciel dynamique (`#ff00ff`, `#ff0000`, `#ff8800`, `#ffff00`, `#00ff00`, `#0000ff`)
  - Fond sombre avec nuances (`rgba(13, 13, 13, 1)` à `rgba(30, 15, 40, 1)`)
  - Effets de transparence avec `rgba(255, 255, 255, 0.05)`

- **Typographie**:
  - Police principale: 'Poppins' (légère 300, régulière 400, semi-bold 600)
  - Textes avec effets de dégradé et de brillance

### ✨ Effets Visuels

#### Effets 3D
- Perspective globale: 1500px
- Transform-style: preserve-3d sur les éléments interactifs
- Effets de profondeur sur les cartes et boutons
- Animation de flottement sur la section héro

#### Animations
1. **Effet de Flottement (float)**
   - Animation 6s en boucle
   - Rotation et translation combinées
   - Effet de respiration naturel

2. **Dégradés Animés (gradient)**
   - Défilement des couleurs arc-en-ciel
   - Durée: 3s en boucle infinie
   - Appliqué aux boutons et barres de progression

3. **Effet Brillant (shimmer)**
   - Animation de balayage lumineux
   - Durée: 2s en boucle infinie
   - Présent sur les barres de compétences

### 📱 Sections

#### 1. Hero Section
- Texte animé avec effet de flottement
- Arrière-plan avec motif de points animés
- Effet de brume colorée

#### 2. Projets
- Cartes avec effet de survol 3D
- Images avec zoom au survol
- Étiquettes technologiques
- Bouton "Voir le projet" animé
- Effet de glassmorphisme

#### 3. Compétences
- Disposition en grille responsive
- Barres de progression animées
- Effet de brillance
- Animation de remplissage fluide
- Pourcentages dynamiques

#### 4. Contact
- Formulaire avec effet glassmorphisme
- Inputs avec effet de profondeur au focus
- Bouton d'envoi avec animation de gradient
- Validation des champs requise

### 🛠 Aspects Techniques

#### Performance
- Utilisation de `transform-style: preserve-3d`
- Animations optimisées avec `will-change`
- Effets de flou avec `backdrop-filter`

#### Responsive Design
- Breakpoint principal: 768px
- Grilles adaptatives avec `grid-template-columns`
- Tailles de police ajustées pour mobile
- Images redimensionnées pour mobile

### 📦 Dépendances

- Vanilla Tilt.js pour les effets 3D
- Google Fonts (Poppins)

### 🔧 Installation

1. Clonez le repository
2. Ouvrez `index.html` dans votre navigateur
3. Ou déployez les fichiers sur votre serveur web

### 💻 Compatibilité

- Chrome (dernière version)
- Firefox (dernière version)
- Safari (dernière version)
- Edge (dernière version)

### 🎯 Utilisation

Pour personnaliser le portfolio :

1. Modifiez les textes dans `index.html`
2. Ajustez les couleurs dans `style.css`
3. Personnalisez les images des projets
4. Modifiez les pourcentages des compétences

### 🌟 Effets Spéciaux

- **Glassmorphisme**: Effet de verre sur les cartes et formulaires
- **Parallax**: Effet de profondeur sur les éléments
- **Hover Effects**: Animations au survol des éléments
- **Gradient Animations**: Dégradés de couleurs animés
- **Shimmer Effects**: Effets de brillance sur les barres de progression

### 📱 Responsive

Le site s'adapte automatiquement à toutes les tailles d'écran avec des ajustements spécifiques pour :
- Desktop (>768px)
- Tablette (768px)
- Mobile (<768px)

## 📝 License

MIT License - Libre d'utilisation et de modification
