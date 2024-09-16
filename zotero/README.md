Voici un modèle « model_zotero.tar » permettant d’exploiter l’export du catalogue d’une bibliothèque Zotero au format BibTex. Une source de données « data_zotero.bib » est fournie à titre d’exemple. L’instance obtenue permet d’explorer le corpus issu de Zotero grâce à un enrichissement par doi via OpenAlex et offre ainsi l’accès à différentes visualisations Lodex facilement reproductibles et adaptables. En effet, l’instance ainsi créée n’utilise ni vega-lite ni aucune séquence de code js/lodash/ezs et peut servir pour des démonstrations à de nouveaux utilisateurs.
1)	Charger le fichier *.bib ou *.txt à l’aide du loader « TXT – BibTeX lists of references »
2)	Importer le modèle « model_zotero.tar »
3)	Lancer l’enrichissement « OpenAlex »
4)	Publier les données
