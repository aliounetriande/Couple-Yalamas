# 🎵 Instructions pour le lecteur de musique

## 📁 Fichier audio requis

Pour que le lecteur fonctionne, vous devez ajouter un fichier audio nommé `music.mp3` à la racine de votre projet.

### Formats supportés :
- MP3 (recommandé)
- WAV
- OGG

### Comment ajouter votre musique :

1. Renommez votre fichier audio en `music.mp3`
2. Placez-le dans le dossier racine (même niveau que index.html)
3. Ou modifiez le chemin dans main.html ligne : `src="music.mp3"`

### Exemple de structure :
```
/Couple Yalamas/
  ├── index.html
  ├── main.html
  ├── music.mp3  ← Votre fichier audio ici
  ├── css/
  └── js/
```

## 🎮 Fonctionnalités du lecteur

✅ **Auto-start** : La musique démarre automatiquement après avoir cliqué sur l'enveloppe
✅ **Contrôles** : Play/Pause, barre de progression, temps
✅ **Responsive** : S'adapte à tous les écrans
✅ **Design harmonieux** : Couleurs assorties au thème du mariage

## 🎨 Personnalisation possible

Pour changer le titre affiché : 
- Modifiez `"Musique de mariage"` dans main.html

Pour changer la position :
- Ajustez les propriétés CSS `.audioBar` (bottom, left, etc.)