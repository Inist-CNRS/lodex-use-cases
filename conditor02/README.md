# Conditor 02

## Données corpus_Demo_revue.json

37 ressources Conditor (notices unifiées) avec des cas pour tester des web services

- crossref : éditeur à partir de la racine DOI
- unpaywall 1 : is_oa
- unpaywall 2 : type d'accès ...
- attribution d'un code RNSR
- attribution instituts cnrs
- homogénéisation des sources
- homogénéisation des éditeurs
- homogénéisation des types de documents 

## Loader json-conditor.ini

Loader pour importer des notices unifiées Conditor (sans aucun appel à des web services).
Loader à déposer dans l'instance créée (potentiellement différent du loader en production), dans le répertoire `loaders`.
