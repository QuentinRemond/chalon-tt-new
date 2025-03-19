# Site Web du Chalon Tennis de Table

Site web moderne et responsive pour le club de tennis de table de Chalon.

## Structure du Site

- **Accueil**: Présentation du club et actualités importantes
- **Le Club**: Histoire, membres du bureau, horaires d'entraînement
- **Équipes**: Présentation des équipes et résultats
- **Actualités**: Événements récents et nouvelles du club
- **Adhésions**: Informations sur les inscriptions
- **Événements**: Calendrier des tournois et stages
- **Boutique**: Matériel et équipements du club
- **Contact**: Formulaire de contact et localisation

## Technologies Utilisées

- HTML5
- CSS3 avec variables CSS
- Bootstrap 5.3.2
- JavaScript (ES6+)
- Font Awesome pour les icônes
- Google Fonts (Montserrat, Roboto)

## Structure des Fichiers

```
test-chalon-tt/
├── index.html
└── assets/
    └── logo_chalon_tt.jpg
```

## Horaires d'Entraînement

- Mardi : 17h-20h
- Jeudi : 17h-20h
- Vendredi : 17h-20h

## Contact

- Adresse : 4 route de Demigny, 71530 CHAMPFORGEUIL
- Email : chalontt@hotmail.com

## Développement

Pour lancer le site en local :
```bash
python -m http.server 8000
```
Puis ouvrir http://localhost:8000 dans votre navigateur.

## Maintenance

Pour ajouter ou modifier des actualités et événements, éditer le fichier `js/main.js` dans les tableaux `newsItems` et `events`.
