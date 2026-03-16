# DeviseFront

Convertisseur de devises moderne avec le Franc CFA (XOF) au cœur de l'expérience.
Généré avec [Angular CLI](https://github.com/angular/angular-cli) version 21.1.5.

## Stack technique

- **Angular** 21.1.5
- **Bootstrap** 5
- **Bootstrap Icons**

## Installation des dépendances
```bash
npm install
```

## Lancer le serveur de développement
```bash
ng serve
```

Une fois le serveur lancé, ouvre ton navigateur sur `http://localhost:4200/`.
L'application se recharge automatiquement à chaque modification du code source.

## Génération de composants
```bash
ng generate component component-name
```

Pour voir tous les schémas disponibles :
```bash
ng generate --help
```

## Build
```bash
ng build
```

Les fichiers compilés seront dans le dossier `dist/`.
Le build de production optimise automatiquement les performances.

## Docker
```bash
# Builder l'image
docker build -t devise-front .

# Lancer le conteneur
docker run -p 8080:80 devise-front
```

L'app sera accessible sur `http://localhost:8080`.

## Tests unitaires
```bash
ng test
```

## Tests end-to-end
```bash
ng e2e
```

## Ressources

- [Angular CLI](https://angular.dev/tools/cli)
- [Bootstrap](https://getbootstrap.com)
- [Bootstrap Icons](https://icons.getbootstrap.com)
