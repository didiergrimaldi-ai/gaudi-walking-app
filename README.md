# 🏛️ Gaudí Walking App - Découvrir Gaudí à Pied à Barcelone

Une application web interactive pour explorer les chefs-d'œuvre architecturaux de Gaudí et du modernisme catalan à Barcelone - 100% à pied !

## 🎯 Caractéristiques

✨ **Interface Interactive**
- 10 bâtiments architecturaux documentés
- Filtrage par circuit de visite
- Modal détaillé pour chaque bâtiment
- Système de favoris

🗺️ **Circuits de Visite**
1. **Circuit Eixample** - Les grands chefs-d'œuvre gaudiens
2. **Circuit Gràcia** - Casa Vicens et le quartier bohème
3. **Circuit Bonus** - Palau Güell et Sant Pau

💰 **Informations Pratiques**
- Durée de visite estimée
- Coût d'entrée
- Architecture et style
- Points clés à ne pas manquer

📱 **Responsive Design**
- Fonctionne parfaitement sur mobile, tablette et desktop
- Interface optimisée pour tous les appareils
- Idéal pour emporter en visite !

## 🚀 Déploiement Rapide

### Via Vercel (recommandé - 2 minutes)

1. **Fork ou clone ce repo**
   ```bash
   git clone https://github.com/YOUR_USERNAME/gaudi-walking-app.git
   ```

2. **Allez sur https://vercel.com/dashboard**
3. **Cliquez "Add New" → "Project"**
4. **Importez depuis GitHub**
5. **Déployez !**

C'est tout ! Votre app sera en ligne à `https://gaudi-walking-app.vercel.app`

### Localement (pour développer)

```bash
# Clone le repo
git clone https://github.com/YOUR_USERNAME/gaudi-walking-app.git
cd gaudi-walking-app

# Installez les dépendances
npm install

# Lancez le serveur de développement
npm run dev

# Ouvrez http://localhost:3000
```

## 📂 Structure du Projet

```
gaudi-walking-app/
├── app/
│   ├── page.js              # Composant React principal
│   ├── layout.js            # Layout Next.js
│   ├── globals.css          # Styles Tailwind
├── package.json             # Dépendances
├── next.config.js           # Configuration Next.js
├── tailwind.config.js       # Configuration Tailwind
├── README.md                # Ce fichier
└── VERCEL_DEPLOYMENT_GUIDE.md # Guide complet de déploiement
```

## 🏗️ Stack Technique

- **Framework**: Next.js 15
- **UI**: React 18
- **Styles**: Tailwind CSS
- **Icons**: Lucide React
- **Déploiement**: Vercel

## 📋 Bâtiments Inclus

### Eixample (Circuit 1)
1. **Casa Calvet** - Première œuvre sobre
2. **Casa Lléo Morera** - Motifs floraux
3. **Casa Amatller** - Néo-gothique meublée
4. **Casa Batlló** - Toit écailles de dragon
5. **Casa Milà** - Façade ondulée massive
6. **Casa Comalat** - Deux façades opposées

### Gràcia (Circuit 2)
7. **Casa Vicens** - Première grande œuvre Gaudí

### Bonus
8. **Palau Güell** - Palais sombre et élégant
9. **Sant Pau** - Hôpital Art Nouveau UNESCO

## 🎨 Personnalisation

### Ajouter un bâtiment

Modifiez le tableau `buildings` dans `app/page.js` :

```javascript
{
  id: 11,
  name: 'Votre Bâtiment',
  circuit: '1',
  address: 'Adresse',
  architect: 'Architecte',
  year: 'Année',
  style: 'Style',
  time: '30 min',
  cost: '15€',
  coords: { lat: 41.39, lng: 2.17 },
  description: 'Description complète...',
  highlights: ['Détail 1', 'Détail 2'],
  image: '🏛️',
  visitUrl: 'https://...'
}
```

### Changer les couleurs

Les couleurs utilisent Tailwind CSS. Modifiez les classes :
- `bg-amber-600` → `bg-blue-600`
- `text-amber-900` → `text-blue-900`
- Etc.

### Ajouter des images réelles

Remplacez les emoji par des images :
```javascript
// Au lieu de: image: '🏛️',
// Utilisez: image: '/images/casa-batllo.jpg',
```

## 💡 Idées d'Amélioration

- [ ] Intégrer Google Maps avec les localisations
- [ ] Ajouter des photos réelles de chaque bâtiment
- [ ] Créer un itinéraire optimisé (GPS)
- [ ] Sauvegarder les favoris dans la base de données
- [ ] Ajouter les horaires d'ouverture en temps réel
- [ ] Intégrer les avis TripAdvisor
- [ ] Créer une version offline (PWA)
- [ ] Ajouter des audio guides
- [ ] Système de notation utilisateurs

## 📱 Partage

### URL de partage
```
https://gaudi-walking-app.vercel.app
```

### Message de partage
```
🏛️ Découvrez Gaudí à pied à Barcelone !
10 bâtiments modernistes, 100% accessibles à pied
Gratuit, interactif et en français
https://gaudi-walking-app.vercel.app
```

### QR Code
Créez un QR code pointant vers votre URL déployée sur https://qr-code-generator.com

## 🔒 Confidentialité

- ✅ Pas de cookies
- ✅ Pas de tracking
- ✅ Pas de données personnelles collectées
- ✅ L'app fonctionne 100% côté client

## 📄 Licence

Libre d'utilisation pour un usage personnel et éducatif.

## 🤝 Contribution

Vous voulez améliorer l'app ? Les contributions sont bienvenues !

1. Fork le projet
2. Créez une branche (`git checkout -b feature/AmazingFeature`)
3. Commitez vos changements (`git commit -m 'Add some AmazingFeature'`)
4. Poussez la branche (`git push origin feature/AmazingFeature`)
5. Ouvrez une Pull Request

## ❤️ Crédits

Créée pour les amoureux d'architecture et de Barcelone.

Inspired by:
- Antoni Gaudí (1852-1926)
- Le modernisme catalan
- La beauté de Barcelone

## 📞 Support

Questions ou problèmes ?
- Consultez le `VERCEL_DEPLOYMENT_GUIDE.md`
- Ouvrez une issue sur GitHub
- Contactez-moi

## 🚀 Déploiement

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https%3A%2F%2Fgithub.com%2Fyour-username%2Fgaudi-walking-app)

---

**Bon voyage à travers l'architecture gaudienne ! 🏛️✨**