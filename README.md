# Brief modélisation de base de données

# ACTIONS EFFECTUÉES

        - Création d'un schéma MCD (Modèle conceptuel de données) avec la méthode Merise sur Excalidraw.
            - Mise en relation entre les entités "Potions" et "Ingredients" en définissant leurs cardinalités (intéractions possibles entre les entités).

        - Création d'un schéma MLD (Modèle logique de données) avec la méthode Merise sur Excalidraw.
            - Suivant la relation Many To Many (comme nos deux entités ont une valeur maximale de N), création de la table "Ingredients_Potions" (Table intermédiaire ou de jointure) avec à l'intérieur les deux clés étrangères "ingredients_id" et "potions_id".
