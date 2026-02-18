# 🌍 Sélecteur de Zone UTM

Un outil interactif pour déterminer les zones UTM et codes EPSG à partir de n'importe quel point sur la carte mondiale.

![UTM Zone Selector](https://img.shields.io/badge/Status-Active-success)
![License](https://img.shields.io/badge/License-MIT-blue)

## 🎯 Fonctionnalités

- **🗺️ Carte interactive mondiale** : Cliquez n'importe où pour obtenir la zone UTM
- **🔍 Recherche d'adresse** : Trouvez automatiquement n'importe quel lieu avec autocomplétion
- **📊 Code EPSG** : Obtention automatique du code EPSG correspondant (format WGS84 UTM)
- **📍 Informations détaillées** :
  - Coordonnées géographiques (latitude/longitude)
  - Zone UTM complète (numéro + lettre de bande)
  - Hémisphère (Nord/Sud)
  - Méridien central
  - Code EPSG standardisé

## 🚀 Utilisation

### En ligne
Visitez : https://aplumacker.github.io/utm-zone-selector/

### En local
1. Téléchargez le fichier `index.html`
2. Ouvrez-le dans votre navigateur web
3. C'est tout ! Aucune installation nécessaire

## 💡 Comment ça marche ?

### Recherche par adresse
1. Tapez une adresse dans la barre de recherche
2. Sélectionnez parmi les suggestions
3. La carte se centre automatiquement et affiche les informations UTM

### Clic sur la carte
1. Cliquez n'importe où sur la carte
2. Un marqueur apparaît avec toutes les informations
3. Le panneau latéral affiche les détails complets

## 📐 À propos des zones UTM

Le système UTM (Universal Transverse Mercator) divise le monde en :
- **60 fuseaux** numérotés de 1 à 60 (6° de longitude chacun)
- **20 bandes** lettrées de C à X (8° de latitude chacune)
- **2 hémisphères** : Nord (EPSG:326XX) et Sud (EPSG:327XX)

## 🛠️ Technologies utilisées

- **HTML5** : Structure
- **CSS3** : Design moderne avec animations
- **JavaScript** : Logique et calculs
- **Leaflet.js** : Carte interactive
- **Nominatim API** : Géocodage d'adresses (OpenStreetMap)

## 📋 Format des codes EPSG

- **Hémisphère Nord** : `EPSG:326XX` où XX = numéro de zone (01-60)
  - Exemple : Paris → EPSG:32631 (Zone 31N)
- **Hémisphère Sud** : `EPSG:327XX` où XX = numéro de zone (01-60)
  - Exemple : Sydney → EPSG:32756 (Zone 56S)

## 🎨 Design

Interface moderne avec :
- Palette de couleurs bleu/cyan sur fond sombre
- Typographies : JetBrains Mono & Work Sans
- Animations fluides
- Design responsive (mobile et desktop)

## 📄 Licence

MIT License - Libre d'utilisation

## 🤝 Contribution

Les contributions sont les bienvenues ! N'hésitez pas à ouvrir une issue ou soumettre une pull request.

## 📧 Contact

Pour toute question ou suggestion, n'hésitez pas à ouvrir une issue sur GitHub.

---

Créé avec ❤️ pour faciliter la sélection de zones UTM
