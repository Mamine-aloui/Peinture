# RENDU 1 PROJET DE LOGICIEL DE PEINTURE

**Auteurs:**
- Aloui Muhammed Amine
- Jlassi Takwa
- Dridi Wael

## 1. Introduction au Projet:
Le projet vise à développer un logiciel de peinture qui offre aux utilisateurs une plateforme intuitive pour créer des œuvres d'art numériques. Le projet inclut la conception et l'implémentation d'une interface utilisateur conviviale, la mise en place d'une boîte à outils complète pour la peinture, le support de différents styles artistiques tels que l'impressionnisme, ainsi que l'intégration d'une fonctionnalité d'intelligence artificielle pour transformer des tableaux existants en divers styles artistiques. Nous avons choisi ce projet car il offre une opportunité de combiner notre intérêt pour la programmation informatique avec notre passion pour les arts visuels.

## 2. Spécification du Projet:
### 2.1 Notions de Base et Contraintes:
- Le logiciel de peinture sera développé en utilisant des technologies adaptées au développement d'applications graphiques.
- Il doit être compatible avec les principaux systèmes d'exploitation tels que Windows, macOS et Linux.
- Il doit être compatible avec les tablettes graphiques et le stylus pen.
- Le logiciel devra également intégrer des fonctionnalités avancées telles que la sélection de styles de peinture et la transformation d'images à l'aide d'intelligence artificielle.

### 2.2 Acteurs et Fonctionnalités Attendues:
**Acteurs:**
- Utilisateur
- Stylus pen: stylo de tablette graphique
- Système d'intelligence artificielle

**Besoins fonctionnels:**
1. Interface Utilisateur:
   - Interface intuitive avec une barre d'outils pour la sélection d'outils de peinture, de couleurs, etc.
   - Zone de travail pour dessiner et peindre.
   - Options d'importation et d'exportation d'images.


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
