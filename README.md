# 🎮 Parcours TND - Les Clés de l'Inclusion

## 📋 Description du Projet

**Parcours TND** est un serious game interactif destiné aux formateurs et formatrices pour sensibiliser et former aux Troubles du Neurodéveloppement (TND). Ce jeu éducatif permet de comprendre les différents TND et d'acquérir des compétences pratiques pour créer des environnements inclusifs.

### 🎯 Contexte de Création
- **Date de développement** : Juin 2025
- **Cible** : Formateurs/formatrices en éducation, santé et inclusion
- **Durée estimée** : 45 minutes à 1h30 selon les modules
- **Format** : Application web interactive (HTML/CSS/JavaScript)

## 🎓 Objectifs Pédagogiques

1. **Identifier** les différents types de TND et leurs manifestations
2. **Comprendre** l'impact des TND sur le quotidien des personnes concernées
3. **Développer** des stratégies d'accompagnement adaptées
4. **Déconstruire** les préjugés et idées reçues
5. **Acquérir** des outils pratiques d'inclusion

## 🏗️ Structure du Jeu

### Modules Disponibles

#### 1. 🏠 **La Maison des Découvertes** ✅
Exploration interactive des différents TND à travers les pièces d'une maison virtuelle :
- **Salon** → TSA (Trouble du Spectre de l'Autisme)
- **Cuisine** → TDAH (Trouble Déficit de l'Attention avec/sans Hyperactivité)
- **Bureau** → Troubles DYS (dyslexie, dyspraxie, dyscalculie...)
- **Chambre** → Déficience intellectuelle
- **Jardin** → Troubles du développement moteur

#### 2. 🎒 **L'École Inclusive** ✅
5 scénarios pratiques d'adaptation en milieu scolaire :
- Emma (8 ans, dyslexique) - Adaptation de la lecture
- Théo (10 ans, TDAH) - Gestion de l'attention et des pauses
- Léa (11 ans, TSA) - Transition et changements
- Mathis (9 ans, dyspraxique) - Adaptation des activités manuelles
- Sarah (12 ans, déficience intellectuelle) - Inclusion dans les projets

#### 3. ☕ **Le Café des Parents** 🚧
*Module en développement* - Espace d'échange et de déconstruction des préjugés

#### 4. 🛠️ **L'Atelier des Solutions** 🚧
*Module en développement* - Boîte à outils interactive avec ressources pratiques

## 🎮 Mécaniques de Gamification

### Système de Progression
- **Points XP** : Gagnés à chaque action positive (50-500 XP)
- **Barres de progression** : Suivi visuel par module
- **Feedback immédiat** : Messages pédagogiques après chaque action

### Badges à Débloquer
- 🌟 **Observateur attentif** : Visiter toutes les pièces de la Maison
- 🤝 **Médiateur bienveillant** : Compléter l'École Inclusive
- 🛠️ **Architecte de l'inclusion** : Proposer des adaptations pertinentes
- 💡 **Innovateur pédagogique** : *À venir*

### Animations et Interactions
- Transitions fluides entre les écrans
- Effets visuels sur les interactions
- Notifications de réussite animées
- Design responsive et accessible

## 💻 Aspects Techniques

### Technologies Utilisées
- **HTML5** : Structure et contenu
- **CSS3** : Styles et animations (gradients, transitions, keyframes)
- **JavaScript Vanilla** : Logique du jeu et interactions
- **Pas de dépendances externes** : Fonctionne en autonomie

### Architecture du Code
```
serious-game-tnd/
│
├── index.html          # Fichier principal unique
├── README.md          # Documentation (ce fichier)
└── assets/            # Dossier optionnel pour futures ressources
    ├── images/
    └── documents/
```

### Variables Globales Principales
```javascript
let score = 0;                    // Score total du joueur
let roomsVisited = [];           // Pièces visitées dans la Maison
let currentRoom = '';            // Pièce actuellement affichée
let unlockedBadges = [];         // Badges débloqués
let currentScenarioIndex = 0;    // Scénario actuel (École)
let correctAnswersCount = 0;     // Réponses correctes (École)
```

## 🚀 Installation et Utilisation

### Pour les Formateurs/Formatrices

1. **Option 1 - Utilisation directe**
   - Ouvrir le fichier `index.html` dans un navigateur moderne
   - Aucune installation requise

2. **Option 2 - Hébergement web**
   - Déposer le fichier sur un serveur web
   - Partager le lien aux apprenants

### Pour les Développeurs

```bash
# Cloner le repository
git clone https://github.com/[votre-username]/serious-game-tnd.git

# Ouvrir le projet
cd serious-game-tnd

# Lancer avec un serveur local (optionnel)
python -m http.server 8000
# ou
npx http-server
```

## 📊 Guide d'Animation (pour les Formateurs)

### Utilisation en Présentiel
1. **Introduction collective** (10 min)
   - Présenter les objectifs
   - Expliquer la navigation
   
2. **Exploration individuelle** (30-40 min)
   - Chaque apprenant joue à son rythme
   - Le formateur circule et accompagne
   
3. **Débriefing en groupe** (20 min)
   - Partage des découvertes
   - Questions/réponses
   - Mise en pratique

### Utilisation en Distanciel
- Partager le lien du jeu
- Prévoir des points de rencontre virtuels
- Utiliser les badges comme jalons de progression
- Forum de discussion pour les échanges

## 🔄 État d'Avancement

### ✅ Fonctionnalités Implémentées
- [x] Écran d'accueil animé
- [x] Système de score et badges
- [x] Module "Maison des Découvertes" complet
- [x] Module "École Inclusive" avec 5 scénarios
- [x] Animations et transitions fluides
- [x] Design responsive
- [x] Feedback pédagogique détaillé

### 🚧 Fonctionnalités en Développement
- [ ] Module "Café des Parents"
- [ ] Module "Atelier des Solutions"
- [ ] Système de sauvegarde locale
- [ ] Mode multijoueur/collaboratif
- [ ] Certificat de fin de parcours
- [ ] Statistiques détaillées pour formateurs
- [ ] Version multilingue

### 💡 Idées Futures
- [ ] Intégration d'audio et vidéo
- [ ] Mode "Création de scénarios" pour formateurs
- [ ] Application mobile native
- [ ] API pour suivi des progressions
- [ ] Contenus adaptés par niveaux (débutant/avancé)

## 📝 Notes Pédagogiques

### Principes Clés
1. **Bienveillance** : Approche positive et non-stigmatisante
2. **Pratique** : Situations concrètes et applicables
3. **Inclusivité** : Le jeu lui-même est accessible
4. **Évolutivité** : Contenu adaptable selon les besoins

### Points d'Attention
- Toujours contextualiser avec des exemples locaux
- Adapter le vocabulaire selon le public
- Encourager le partage d'expériences
- Valoriser toutes les formes de progression

## 🤝 Contribution

### Comment Contribuer
1. Fork le projet
2. Créer une branche (`git checkout -b feature/nouvelle-fonctionnalite`)
3. Commit les changements (`git commit -m 'Ajout nouvelle fonctionnalité'`)
4. Push vers la branche (`git push origin feature/nouvelle-fonctionnalite`)
5. Ouvrir une Pull Request

### Guidelines
- Respecter la structure existante
- Commenter le code complexe
- Tester sur différents navigateurs
- Maintenir l'accessibilité

## 📄 Licence

Ce projet est distribué sous licence [MIT](LICENSE) - voir le fichier LICENSE pour plus de détails.

## 🙏 Remerciements

- Aux professionnels de l'inclusion pour leurs retours
- Aux personnes concernées par les TND pour leur expertise
- À la communauté éducative pour son engagement

## 📞 Contact

Pour toute question ou suggestion :
- Email : [votre-email]
- Issues GitHub : [lien vers issues]
- Site web : [votre-site]

---

*"L'inclusion n'est pas une destination, c'est un voyage que nous faisons ensemble."*
