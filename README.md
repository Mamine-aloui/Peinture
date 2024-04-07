# 1 : Create new Workspace:

**Preconditions:**

- Choisir la dimension (Hauteur et largeur)
- Choisir un nom de fichier
- Espace de stockage suffisant

**Postconditions:**

- Le Workspace est créé

|                |                              | 1   | 2   | 3   | 4   | 5   |
| -------------- | ---------------------------- | --- | --- | --- | --- | --- |
| Préconditions  | choisir dimension            | F   | F   | T   | T   | T   |
| Préconditions  | choisir nom du fichier       | F   | T   | F   | T   | T   |
| Préconditions  | espace de stockage suffisant | F   | T   | T   | F   | T   |
| Postconditions | Le workspace est crée        | F   | F   | F   | F   | T   |

# 2 : Use tool:

**Preconditions:**

- Un tool est choisi
- Un workspace est ouvert

**Postconditions:**

- Modifier le workspace (faire la peinture de tableau)

|                |                         | 1   | 2   | 3   | 4   |
| -------------- | ----------------------- | --- | --- | --- | --- |
| Préconditions  | un tool est choisi      | F   | F   | T   | T   |
| Préconditions  | un workspace est ouvert | F   | T   | F   | T   |
| Postconditions | modifier le workspace   | F   | F   | F   | T   |

# 3 : Transform Style:

**Preconditions:**

- Un Workspace est ouvert
- Un style est choisi

**Postconditions:**

- Le style de tableau est transformé

|                |                                    | 1   | 2   | 3   | 4   |
| -------------- | ---------------------------------- | --- | --- | --- | --- |
| Préconditions  | un workspace est ouvert            | F   | F   | T   | T   |
| Préconditions  | un style est choisi                | F   | T   | F   | T   |
| Postconditions | le style de tableau est transformé | F   | F   | F   | T   |
