# byArno Configurator

Configurateur 3D et boutique en ligne pour produits artisanaux en bois et résine époxy.

## Installation

1. Cloner le repository
```bash
git clone https://github.com/GeneSis101010/byArno-configurator.git
```

2. Installer les dépendances
```bash
composer install
npm install
```

3. Configurer la base de données
```bash
php bin/console doctrine:database:create
php bin/console doctrine:migrations:migrate
```

4. Lancer le serveur de développement
```bash
symfony server:start
npm run watch
```

## Structure du projet

- `src/Controller/` - Contrôleurs de l'application
- `src/Entity/` - Entités Doctrine
- `src/Repository/` - Repositories Doctrine
- `templates/` - Templates Twig
- `assets/` - Fichiers JavaScript, CSS et autres assets