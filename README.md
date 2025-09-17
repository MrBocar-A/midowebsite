# Mido Fortified Food - Site Web Vitrine

Site web vitrine responsive pour Mido Fortified Food, une entreprise burundaise spécialisée dans la production d'aliments enrichis pour lutter contre la malnutrition.

## 📋 Structure du Site

### Pages / Sections
- **Accueil** - Présentation générale avec statistiques d'impact
- **Qui sommes-nous** - Histoire, mission et équipe
- **Vision** - Objectifs stratégiques, valeurs et impact social
- **Partenariats** - Collaborations avec organisations et institutions
- **Développement Local** - Programmes de soutien aux communautés agricoles
- **Contact** - Informations de contact et formulaire

## 🎨 Design et Fonctionnalités

### Design Responsive
- **Mobile First** - Optimisé pour tous les appareils
- **Navigation mobile** avec menu hamburger
- **Grid System** flexible pour tous les écrans

### Palette de Couleurs
- Vert principal: `#196444`
- Vert clair: `#8ab33d`
- Fond clair: `#f8f9fa`
- Texte: `#333333`

### Typographie
- Police principale: **Ubuntu** (Google Fonts)
- Hiérarchie claire avec titres et sous-titres

## 💻 Fonctionnalités Techniques

### HTML5 Sémantique
- Structure sémantique avec balises appropriées
- Optimisation SEO avec meta descriptions
- Accessibilité avec skip links et navigation au clavier

### CSS3 Moderne
- **Flexbox** et **CSS Grid** pour la mise en page
- **Variables CSS** pour la cohérence des couleurs
- **Animations** et **transitions** fluides
- **Media queries** pour le responsive design

### JavaScript Interactif
- **Navigation smooth scroll**
- **Menu mobile** interactif
- **Formulaire de contact** avec validation
- **Système de notifications**
- **Compteurs animés** pour les statistiques
- **Scroll to top** button
- **Lazy loading** pour les images (prêt)

## 📁 Structure des Fichiers

```
MidoFortidiedFood/
├── index.html          # Page principale
├── styles.css          # Feuilles de style
├── script.js           # JavaScript interactif
└── README.md           # Documentation
```

## 🚀 Installation et Utilisation

1. **Ouvrir le site** : Double-cliquez sur `index.html` ou ouvrez-le dans votre navigateur
2. **Développement local** : Utilisez un serveur local (Live Server, XAMPP, etc.)
3. **Hébergement** : Uploadez tous les fichiers sur votre serveur web

## 🔧 Personnalisation

### Modifier le Contenu
- **Textes** : Éditez directement dans `index.html`
- **Images** : Remplacez les placeholders par vos images
- **Couleurs** : Modifiez les variables CSS dans `:root` dans `styles.css`
- **Contact** : Mettez à jour l'email et l'adresse dans la section contact

### Ajouter des Images
1. Créez un dossier `images/`
2. Remplacez les placeholders par vos images
3. Utilisez l'attribut `data-src` pour le lazy loading

### Intégrer Google Maps
Remplacez le placeholder de carte par une iframe Google Maps :
```html
<iframe
  src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d..."
  width="100%"
  height="300"
  style="border:0;"
  allowfullscreen>
</iframe>
```

## 📧 Formulaire de Contact

Le formulaire est actuellement configuré pour :
- Validation côté client
- Affichage de notifications
- Simulation d'envoi (à connecter à un backend)

Pour connecter à un vrai service :
1. Modifier la fonction de soumission dans `script.js`
2. Utiliser un service comme Formspree, EmailJS, ou votre propre API
3. Configurer l'endpoint dans le code

## 🌐 Compatibilité Navigateurs

- Chrome 60+
- Firefox 55+
- Safari 12+
- Edge 79+
- Mobile browsers (iOS Safari, Chrome Mobile)

## 📱 Points de Rupture Responsive

- **Mobile** : < 768px
- **Tablette** : 768px - 1024px
- **Desktop** : > 1024px
- **Mobile petit** : < 480px

## ⚡ Performance

### Optimisations Incluses
- Lazy loading des images
- CSS et JS optimisés
- Polices web optimisées (Google Fonts)
- Animations GPU-accelerated

### Suggestions d'Amélioration
- Compresser les images (WebP, AVIF)
- Minifier CSS/JS pour la production
- Configurer un CDN
- Implémenter le cache navigateur

## 🎯 Prochaines Étapes Suggérées

1. **Ajouter des images réelles** de l'entreprise et des produits
2. **Intégrer Google Maps** pour la localisation
3. **Connecter le formulaire** à un service d'envoi d'emails
4. **Configurer Google Analytics** pour le suivi
5. **Optimiser pour les moteurs de recherche** (Schema.org, Open Graph)
6. **Ajouter des témoignages** clients/partenaires
7. **Créer une page de blog** pour les actualités

## 📞 Contact Technique

Pour toute question technique concernant ce site web :
- Email : midofortifiedfood@gmail.com
- Localisation : Bujumbura, Burundi

---

*Site web créé avec HTML5, CSS3, et JavaScript vanilla. Optimisé pour la performance et l'accessibilité.*