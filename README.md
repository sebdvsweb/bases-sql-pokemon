# Pokémon
Attrapez-les tous ! 

## Création de la base de données Pokémon

```sql
CREATE TABLE pokemon (
    id INT PRIMARY KEY AUTO_INCREMENT,
    nom VARCHAR(50) NOT NULL,
    type VARCHAR(50) NOT NULL,
    numero INT NOT NULL UNIQUE,
    attaque INT NOT NULL,
    defense INT NOT NULL,
    pv INT NOT NULL,
    faiblesse VARCHAR(255) NOT NULL
);
```

## Insertion des valeurs

```sql
INSERT INTO pokemon (nom, type, numero, attaque, defense, pv, faiblesse)
VALUES
('Pikachu', 'Électrique', 25, 43, 39, 35, 'Eau'),
('Dracaufeu', 'Feu/Vol', 6, 80, 59, 78, 'Eau'),
('Carapuce', 'Eau', 7, 48, 50, 44, 'Plante'),
('Bulbizarre', 'Plante/Poison', 1, 49, 49, 41, 'Feu'),
('Herbizarre', 'Plante/Poison', 2, 62, 63, 48, 'Feu'),
('Florizarre', 'Plante/Poison', 3, 80, 82, 80, 'Feu'),
('Salamèche', 'Feu', 4, 52, 43, 39, 'Eau'),
('Carabaffe', 'Eau', 8, 59, 63, 58, 'Plante'),
('Tortank', 'Eau', 9, 83, 80, 78, 'Plante'),
('Chenipan', 'Insecte', 10, 30, 35, 35, 'Feu'),
('Chrysacier', 'Insecte', 11, 20, 55, 30, 'Feu'),
('Papilusion', 'Insecte/Vol', 12, 40, 35, 35, 'Feu'),
('Aspicot', 'Insecte', 13, 35, 35, 40, 'Feu'),
('Coconfort', 'Insecte/Poison', 14, 20, 60, 30, 'Feu'),
('Dardargnan', 'Insecte/Vol', 15, 65, 45, 40, 'Feu'),
('Roucool', 'Normal/Vol', 16, 48, 48, 40, 'Combat'),
('Roucoups', 'Normal/Vol', 17, 60, 55, 50, 'Combat'),
('Roucarnage', 'Normal/Vol', 18, 80, 75, 70, 'Combat'),
('Rattata', 'Normal', 19, 30, 35, 30, 'Combat'),
('Rattatac', 'Normal', 20, 55, 80, 50, 'Combat'),
('Piafabec', 'Normal', 21, 35, 35, 30, 'Combat'),
('Rapasdepic', 'Normal/Poison', 22, 60, 40, 60, 'Combat');
```

## Questions

Trouver et notez sur un document Word ou Openoffice les requêtes SQL permettant de répondre aux questions suivantes.


1. Quels sont les noms, les types et les numéros de tous les Pokémon ?
2. Quels sont les noms et les types des Pokémon de type Feu ?
3. Quels sont les noms et les points d'attaque des Pokémon avec plus de 60 points d'attaque ?
4. Quel est le nom du Pokémon qui a le plus de points de vie ?
5. Quels sont les noms des Pokémon dont le nom commence par "Ca" ?
6. Combien de Pokémon y a-t-il de chaque type ?
7. Quels sont les noms des Pokémon faibles au type Eau ?
8. Quels sont les noms et les types des Pokémon dont le nom et le type ne sont pas vides ?
9. Quels sont les noms uniques des Pokémon ?
10. Quels sont les noms des Pokémon classés par numéro ?
11. Comment mettre à jour les points d'attaque de Pikachu à 50 ?
12. Quels sont les noms et les PV des Pokémon avec des PV compris entre 30 et 40 ?
13. Quels sont les noms des Pokémon dont le nom contient au moins 5 caractères ?
14. Quels sont les noms des Pokémon dont le nom commence par une voyelle ?
15. Quels sont les noms et les types des Pokémon dont le type secondaire est Poison ?
16. Comment insérer un nouveau Pokémon dans la table avec les informations souhaitées ?
17. Comment modifier le type de Carapuce en Eau/Acier ?
18. Quels sont les noms des Pokémon contenant la chaîne de caractères "sa" ?
19. Quelle est la faiblesse principale la plus fréquente parmi tous les Pokémon ?
20. Quel est le Pokémon avec le plus haut nombre de points de défense ?
21. Quels sont les noms et les types des Pokémon dont le nom et le type ne sont pas vides et le numéro est supérieur à 100 ?
22. Comment augmenter de 10 les points d'attaque et de défense de tous les Pokémon de type Feu ?
23.	Quels sont les Pokémon dont la somme des points d’attaque et de défense est supérieure à 100 ?
24.	Quels sont les Pokémon dont la faiblesse est contre le type Feu et dont le nombre de points de vie est supérieur à 50 ?
25.	Comment supprimer les Pokémon de type Normal/Vol ?

