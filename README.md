# Chrono Fitness RC - PWA 💓⏱️

## 🎯 Qu'est-ce que c'est ?

Application web progressive (PWA) de chronomètre fitness avec monitoring cardiaque Bluetooth en temps réel.

## 📦 Fichiers inclus

- `chrono-fitness-hr.html` - Application principale
- `manifest.json` - Métadonnées de l'app (nom, icônes, couleurs)
- `sw.js` - Service Worker (cache et mode offline)
- `icon-192.png` - Icône 192x192
- `icon-512.png` - Icône 512x512

## 📱 Installer sur mobile

### Android (Vivaldi / Chrome)

1. Ouvre [l'appli](https://parksto.github.io/chrono-fitness/chrono-fitness-hr.html)
2. Menu (⋮) > **"Ajouter à l'écran d'accueil"** ou **"Installer l'application"**
3. Confirme l'installation
4. L'app apparaît sur ton écran d'accueil comme une vraie app !

### iOS (Safari)

1. Ouvre [l'appli](https://parksto.github.io/chrono-fitness/chrono-fitness-hr.html)
2. Bouton Partage (carré avec flèche) > **"Sur l'écran d'accueil"**
3. Ajoute
4. L'app est installée !

## ✨ Fonctionnalités PWA

- ✅ **Installation** : Icône sur l'écran d'accueil
- ✅ **Mode standalone** : Plein écran sans barre de navigateur
- ✅ **Mode offline** : L'app fonctionne sans connexion Internet (après 1ère visite)
- ✅ **Cache intelligent** : Mises à jour automatiques
- ✅ **Bluetooth** : Connexion aux capteurs cardiaques

## 🔧 Utilisation

1. **Ouvre l'app** depuis ton écran d'accueil
2. **Menu (☰)** : Connecte ta montre Bluetooth
3. **Tap sur le RC** : Reset le chronomètre
4. **Personnalise** : Zones de FC et couleurs dans les paramètres

## 🎨 Personnalisation

- Toutes les zones de fréquence cardiaque sont modifiables
- Couleurs personnalisables avec color picker
- Sauvegarde automatique en localStorage
- Transitions de couleur progressives

## 🔄 Mise à jour

Pour mettre à jour l'app :
1. Modifie les fichiers sur GitHub
2. Change la version dans `sw.js` : `const CACHE_NAME = 'chrono-fitness-v2';`
3. Les utilisateurs recevront automatiquement la mise à jour

## 🐛 Dépannage

**Bluetooth ne fonctionne pas**
- Vérifie que tu es en HTTPS (pas HTTP)
- Active le Bluetooth sur ton téléphone
- Autorise l'accès Bluetooth dans les permissions du navigateur

**L'app ne s'installe pas**
- Vérifie que tu es en HTTPS
- Sur iOS : utilise Safari (pas Chrome)
- Vide le cache et réessaie

**Mode offline ne fonctionne pas**
- Visite l'app une première fois avec Internet
- Le Service Worker se met en cache automatiquement
- Ensuite ça marche offline !

## 📊 Zones de FC par défaut

- ⚪ Repos : 0-85 bpm (blanc)
- 🔵 Échauffement : 86-101 bpm (bleu)
- 🟢 Brûlage graisses : 102-118 bpm (vert)
- 🟡 Aérobie : 119-134 bpm (jaune)
- 🟠 Anaérobie : 135-152 bpm (orange)
- 🔴 Extrême : 153-170 bpm (rouge)
- 🔴 Danger : 170+ bpm (rouge intense)

---

**Profite de tes sessions fitness ! 💪**
