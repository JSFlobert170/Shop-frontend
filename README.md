- Grille d'articles : 
    -> Composant PostItem (intégration html / css)
    -> À checker composant GridPosts (grid)
    -> Load more : 
        -> Backend 
            - Modifier query getArticles (passer des arguments / typer dans les schémas l'argument à passer)
            - Tester avec le playground graphql
        -> Frontend
            - Utiliser les paramètres de la route pour relancer la query : ?limit=6 / 12 / etc...
            - À faire ensemble : Créer une page /articles 
                - Fetch tous les articles (en SSR)
                - Utiliser le composant GridPosts 
                - Passer filtres load more en Serverside 
                - Repasser la homepage en Client side (le bouton loadmore va être déclenché c)