# Brief modélisation de base de données

# ACTIONS EFFECTUÉES

# Modélisation

- Création d'un schéma MCD (Modèle conceptuel de données) avec la méthode Merise sur Excalidraw.
  - Mise en relation entre les entités "Potions" et "Ingredients" en définissant leurs cardinalités (intéractions possibles entre les entités).

- Création d'un schéma MLD (Modèle logique de données) avec la méthode Merise sur Excalidraw.
  - Suivant la relation Many To Many (comme nos deux entités ont une valeur maximale de N), création de la table "Ingredients_Potions" (Table intermédiaire ou de jointure) avec à l'intérieur les deux clés étrangères "ingredients_id" et "potions_id".

- Création des tables "potions", "ingredients" et "ingredients_potions" sur Supabase.
  - Assignation des clés primaires sur ingredients_id et potions_id dans la table ingredients_potions.
  - Assignation des clés étrangères sur ingredients_id et potions_id en relation avec l'id des deux autres tables.

# Atelier

- Création d'un schéma MCD (Modèle conceptuel de données) avec la méthode Merise sur Excalidraw.
  - Création des entités "Animal", "Species", "Breeds" et "Adopter".
  - Mise en relation entre les différentes entités avec leurs cardinalités

- Création d'un schéma MLD (Modèle logique de données) avec la méthode Merise sur Excalidraw.
  - Analyse des relations entre les différentes entités (N-1 dans ces cas précis).
  - Création des clés étrangères dans les entités concernées.
  - Création de la table intermédiaire "Adoption".
