# Geocoding Api

## GeocodingService

### https://adresse.data.gouv.fr/api-doc/adresse

Les attributs retournés sont :

- __id__ : identifiant de l’adresse (clef d’interopérabilité)
- type : type de résultat trouvé
- housenumber : numéro « à la plaque »
- street : position « à la voie », placé approximativement au centre de celle-ci
- locality : lieu-dit
- municipality : numéro « à la commune »
- score : valeur de 0 à 1 indiquant la pertinence du résultat
- housenumber : numéro avec indice de répétition éventuel (bis, ter, A, B)
- street : nom de la voie
- name : numéro éventuel et nom de voie ou lieu dit
- postcode : code postal
- citycode : code INSEE de la commune
- city : nom de la commune
- district : nom de l’arrondissement (Paris/Lyon/Marseille)
- oldcitycode : code INSEE de la commune ancienne (le cas échéant)
- oldcity : nom de la commune ancienne (le cas échéant)
- context : n° de département, nom de département et de région
- label : libellé complet de l’adresse
- x : coordonnées géographique en projection légale
- y : coordonnées géographique en projection légale
- importance : indicateur d’importance (champ technique)