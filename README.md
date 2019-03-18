http://www.julie-nginn.com/about-me

##Optimisation de la performance:
- Utiliser des images WebP (facultatif)
- Réduire le nombre de liens ou scripts bloquant le rendu en identifiant ce qui est critique ou non (avec Coverage)
- Compresser et réduire la taille des images
- Lazy loader les images (ne les faire apparaître que si elles sont à l'écran)
- Optimiser l'encodage et la taille de transfert des éléments de texte (avec GZip ?)

##Optimisation de l'accessibilité:
- Ajouter l'attribut `alt` aux images
- Ajouter un nom explicite aux liens (aussi pour les images-liens et les boutons)

##Optimisation des bonnes pratiques:
- Utiliser des urls sécurisées
- Utiliser HTTP / 2 à la place de HTTP / 1.1
- Utiliser `rel="noopener"` pour les liens avec `target="_blank"`
- Utiliser un short name (moins de 12 caractères) pour qu'il ne soit pas tronqué sur l'écran d'accueil

##Optimisation pour le PWA:
- Enregistrer un service worker (pour gérer l'offline, les notifications)
- Renvoi une 200 quand on passe en hors ligne
- Utiliser HTTPS pour sécuriser les urls
