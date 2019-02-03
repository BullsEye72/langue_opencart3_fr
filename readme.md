# opencart-fr-3.0.3.1

## Introduction

Pack de langue française pour opencart 3.0.3.1 (admin/catalog) [OpenCart](https://github.com/opencart/opencart/releases/tag/3.0.3.1) 

## Installation 

Extraire les répertoires `/admin/language/fr-FR` et `/admin/catalog/fr-FR` dans le répertoire `upload` de votre site.

__A partir de l'installation par défaut (en langue anglaise)__

1. `Navigation` : Aller dans la rubrique `System -> Localisation -> Languages`
2. Cliquer sur le bouton `Add New`
3. Renseigner les valeurs suivantes :
  - _Language Name_ : `Français`
  - _Code_ : `fr-FR`
  - _Locale_ : `fr,fr-FR,fr_FR.UTF-8,french`
  - _Status_ : `Enabled`
  - _Sort Order_: `1`
4. Enregistrer les changements

5. `Navigation` : Aller à la rubrique `System -> Settings`
6. Sur votre boutique `Store Name` , `Edit` puis cliquer sur l'onglet `Local` et changer les paramètres du `Language` et `Administration Language` pour `Français`
7. Enregistrer les changements
8. Installation terminée

## Nouvelle Installation

Extraire les répertoires `/admin/language/fr-FR`, `/admin/catalog/fr-FR` et `install` dans le répertoire `upload` de votre site.

1. Suivre la procédure d'installation classique (Language Francais disponible sur la procédure d'installation)
2. L'étape 4/4 de l'installation exécute les requêtes de `opencart.sql` et installe l'environnement français par défaut ainsi que les données (catégories, produits ...)

## License

MIT

**Free Software, Hell Yeah!**

