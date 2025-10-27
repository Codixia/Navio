# Conception d'une application de navigation sécurisée (auto et moto)

## Interface et cartographie

### Fonctionnalités principales
- Cartographie riche et détaillée
  - Guidage centré sur le véhicule
    - Vue rapprochée par défaut
    - Vue haute disponible selon le contexte
  - Adaptation aux contraintes routières
    - Affichage des voies multiples
    - Position recommandée sur la voie
    - Signalisation (feux, stops, priorités)
  - Fonctionnalités communautaires
    - Signalement des dangers
    - Information trafic en temps réel
    - Itinéraires adaptés par type de véhicule
    - Alertes événements temporaires (travaux, blocages)
  - Interface optimisée pour la conduite
    - Design moderne et épuré
    - Boutons larges et visibles
    - Mode jour/nuit automatique
    - Vues 3D et réalité augmentée
- Navigation vocale optimisée pour la conduite
- Signalement communautaire des dangers
- Fonctionnalités adaptées au véhicule
- Interface map-based claire

### Interface utilisateur
- Gros boutons et couleurs contrastées 
- Mode jour/nuit
- Vues alternatives (3D, réalité augmentée)
- Mode passager et guidage vocal

## Système de signalement des dangers

### Fonctionnalités de base
- Signalement collaboratif des dangers
- Catégories pré-définies d'obstacles
- Géolocalisation en temps réel
- Base de données partagée

### Innovations proposées
- Reconnaissance vocale et IA pour le reporting
- Commandes vocales pour signalement mains-libres
- Détection de zones scolaires comme danger permanent
- Alertes intelligentes basées sur l'accélération/adhérence

## Personnalisation selon le véhicule
- Choix du type de véhicule (auto/moto) dès le profil utilisateur
- Ajustements de l'interface et des préférences de guidage
- Intégration des spécificités du véhicule (niveau d’essence, tension de la batterie)
- Couplage avec des accessoires connectés (casque audio-mains libres, caméras embarquées)
- Personnalisation esthétique (choix d’icônes, couleurs, avatar de véhicule)

## Aspects légaux et sécurité routière
- Usage du téléphone « mains libres » imposé par la législation française
- Interdiction de détecteurs de radars mobiles
- Autorisation des « assistants d’aide à la conduite » coopératifs
- Respect du RGPD et des bonnes pratiques d’ergonomie automobile

## Modération et fiabilité des utilisateurs
- Système de confiance progressif basé sur des points et niveaux
- Accès à certaines actions conditionné par un kilométrage et des signalements validés
- Affichage d’un niveau ou badge (novice, expert, vétéran) en fonction du score

## Fonctionnalités innovantes pour se démarquer
- Interaction vocale/IA pour annoncer les dangers à voix haute
- Réalité augmentée pour superposer des flèches de direction ou pictogrammes
- IA embarquée pour prédire les comportements dangereux
- Routage écologique pour optimiser la consommation de carburant
- Partage de « guide local » pour publier des conseils ou anecdotes de route
- Gamification avancée avec défis et trophées
- Intégration eCall/Urgenţe en cas de crash détecté
- Compatibilité multiplateformes (Android Auto/Apple CarPlay, iOS/Android standard)

Chaque fonctionnalité devra être pensée pour la sécurité. Par exemple, la navigation et le signalement seront désactivés à haute vitesse ou gérés vocalement (sur moto surtout). Le design visuel doit respecter les normes (police lisible, pas d’éléments clignotants, etc.). Enfin, le projet technique s’appuiera sur des technologies éprouvées : applis natives ou cross-platform (React Native/Flutter), backend cloud (Firebase ou serveurs AWS gratuitement, base de données géospatiale comme PostGIS ou MongoDB), et APIs de cartographie libres (OSM, Mapbox). Aucune contrainte budgétaire forte n’impose à ce stade de solution payante, on privilégiera les outils open source ou free-tier, l’objectif restant d’obtenir un prototype fonctionnel en mode startup légère.

## Sources et références
> - Motobit : Base de données de dangers routiers
> - Waze : Innovations en reporting vocal et zones scolaires
> - data.gouv.fr : Données officielles des feux de signalisation
> - legifrance.gouv.fr : Réglementation sur les avertisseurs

