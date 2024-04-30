# Projet  AGL
## Aloui Muhammed Amine/ Takwa Jlassi/ Wael Dridi

## 1. Introduction au Projet:

Le projet vise à développer un logiciel de peinture qui offre aux utilisateurs une plateforme intuitive pour créer des œuvres d'art numériques. Le projet inclut la conception et l'implémentation d'une interface utilisateur conviviale, la mise en place d'une boîte à outils complète pour la peinture, le support de différents styles artistiques tels que l'impressionnisme, ainsi que l'intégration d'une fonctionnalité d'intelligence artificielle pour transformer des tableaux existants en divers styles artistiques. Nous avons choisi ce projet car il offre une opportunité de combiner notre intérêt pour la programmation informatique avec notre passion pour les arts visuels.

## 2. Spécification du Projet:

### 2.1 Notions de Base et Contraintes:

- Le logiciel de peinture sera développé en utilisant des technologies avancées pour offrir des performances optimales et une expérience utilisateur fluide.
- Il doit être compatible avec les principaux systèmes d'exploitation tels que Windows, macOS et Linux, assurant une large accessibilité.
- Le logiciel doit prendre en charge les périphériques de dessin tels que les tablettes graphiques et les stylets, garantissant une utilisation intuitive et précise.
- Il doit inclure des fonctionnalités avancées telles que la transformation de style via l'intelligence artificielle et l'application de filtres et effets artistiques personnalisables.
- La sécurité et la stabilité du logiciel sont des priorités, avec une gestion efficace de la mémoire et des protections contre les vulnérabilités.

### 2.2 Acteurs:

- Utilisateur : L'acteur principal qui interagit avec le logiciel pour créer et manipuler des œuvres d'art numériques.
- Stylus : Un outil de dessin utilisé avec une tablette graphique pour dessiner et peindre avec précision.
- Tablet : Permet la connexion et la gestion du stylet pour faciliter le travail de l'utilisateur.
- AI System : Fournit des fonctionnalités d'intelligence artificielle pour transformer le style de l'œuvre et fournir des suggestions artistiques.

### 2.3 Fonctionnalités Attendues:

#### Créer un Nouvel Espace de Travail:
- L'utilisateur peut créer un nouvel espace de travail avec des dimensions personnalisées, un nom de fichier, des paramètres initiaux tels que la couleur d'arrière-plan, et la sélection d'un modèle de document si nécessaire.
- Le workspace est configuré selon les préférences de l'utilisateur et prêt à être utilisé.

#### Charger un Espace de Travail:
- L'utilisateur peut charger un espace de travail existant pour continuer à travailler sur une œuvre.

#### Utiliser un Outil:
- L'utilisateur peut sélectionner un outil parmi ceux disponibles dans la barre d'outils et l'utiliser sur un espace de travail ouvert.
- Le stylet est utilisé pour appliquer l'outil aux zones ou calques spécifiques.

#### Transformer le Style:
- L'utilisateur peut choisir un style parmi les options disponibles, y compris les styles basés sur l'IA, pour transformer l'œuvre.
- L'AI System applique le style choisi aux calques ou zones définies.

#### Gérer les Calques:
- L'utilisateur peut gérer les calques en les fusionnant, les dupliquant, les déplaçant ou les verrouillant selon les besoins.

#### Appliquer des Filtres et Effets:
- L'utilisateur peut choisir et appliquer des filtres et effets artistiques aux calques ou zones sélectionnées.
- Les paramètres des filtres et effets sont configurables selon les préférences de l'utilisateur.

#### Enregistrer et Exporter des Œuvres:
- L'utilisateur peut enregistrer et exporter les œuvres créées dans divers formats, résolution et qualité.
- Les fichiers sont enregistrés dans un emplacement spécifié ou exportés vers une destination externe.

#### Utiliser la Tablette et le Stylet:
- L'utilisateur peut connecter et utiliser la tablette et le stylet pour dessiner et peindre de manière plus précise et intuitive.


# Diagramme de cas d'utilisation:
![Cat](https://github.com/Mamine-aloui/Peinture/blob/main/Diagrammes/usecase.png)

# Diagramme de sequence 1:
![Cat](https://github.com/Mamine-aloui/Peinture/blob/main/Diagrammes/sequence1.svg)

# Diagramme de sequence 2:
![Cat](https://github.com/Mamine-aloui/Peinture/blob/main/Diagrammes/sequence2.svg)

# Diagramme de sequence 3:
![Cat](https://github.com/Mamine-aloui/Peinture/blob/main/Diagrammes/sequence3.svg)

# Diagramme de Classe:
![Cat](https://github.com/Mamine-aloui/Peinture/blob/main/Diagrammes/Class.svg)

# Diagramme de conception detaillé:
![Cat](https://github.com/Mamine-aloui/Peinture/blob/main/Diagrammes/conception_detaillee.svg)

# Diagramme de machine d'etat:
![Cat](https://github.com/Mamine-aloui/Peinture/blob/main/Diagrammes/etat.svg)

# Diagramme de classe raffinée:
![Cat](https://github.com/Mamine-aloui/Peinture/blob/main/Diagrammes/Classe_Raffinee.svg)



## Cas d'Utilisation:

# 1 : Create new Workspace:

**Preconditions:**

- Choisir la dimension (Hauteur et largeur)
- Choisir un nom de fichier
- Espace de stockage suffisant

**Postconditions:**


|                                          | 1   | 2   | 3   | 4   | 5   | 6   | 7   | 8   |
| ---------------------------------------- | --- | --- | --- | --- | --- | --- | --- | --- |
| Choisir la dimension(Hauteur et Largeur) | T   | T   | T   | F   | T   | F   | F   | F   |
| Choisir un nom de fichier                | T   | T   | F   | T   | F   | T   | F   | F   |
| Espace de Stockage suffisant             | T   | F   | T   | T   | F   | F   | T   | F   |
| Postconditions                           |     |     |     |     |     |     |     |     |
| Le Workspace est créé                    | T   | F   | F   | F   | F   | F   | F   | F   |

# 2 : Use tool:

**Preconditions:**

- Un tool est choisi
- Un workspace est ouvert

**Postconditions:**

- Modifier le workspace (faire la peinture de tableau)

|                         | 1   | 2   | 3   | 4   |
| ----------------------- | --- | --- | --- | --- |
| Un tool est choisi      | T   | T   | F   | F   |
| Un Worskpace est ouvert | T   | F   | T   | F   |
| Postconditions          |     |     |     |     |
| Modifier le Workspace   | T   | F   | F   | F   |

# 3 : Transform Style:

**Preconditions:**

- Un Workspace est ouvert
- Un style est choisi

**Postconditions:**

- Le style de tableau est transformé

|                                    | 1   | 2   | 3   | 4   |
| ---------------------------------- | --- | --- | --- | --- |
| Un Workspace est ouvert            | T   | T   | F   | F   |
| Un style est choisi                | T   | F   | T   | F   |
| Postconditions                     |     |     |     |     |
| Le style de tableau est transformé | T   | F   | F   | F   |

### 4. Gérer les Calques:

Préconditions:
- Un espace de travail est ouvert.
- Un ou plusieurs calques existent dans l'espace de travail.
- Les calques à gérer sont sélectionnés.

Postconditions:
- Les calques sélectionnés sont modifiés selon l'action choisie (fusion, duplication, déplacement, verrouillage, etc.).

Table de décision:

| Workspace ouvert | Calques existants | Calques sélectionnés | Résultat                    |
|------------------|-------------------|----------------------|-----------------------------|
| Vrai             | Vrai              | Vrai                 | Calques gérés selon l'action choisie |
| Vrai             | Vrai              | Faux                 | Pas de gestion des calques |
| Faux             | Vrai              | N/A                  | Pas de gestion des calques |

### 5. Appliquer des Filtres et Effets:

Préconditions:
- Un espace de travail est ouvert.
- L'œuvre contient au moins un calque ou une zone sélectionnée.
- Le filtre ou effet souhaité est choisi.

Postconditions:
- Le filtre ou effet est appliqué aux calques ou zones sélectionnées.
- L'intensité et les paramètres du filtre ou effet sont configurés.

Table de décision:

| Workspace ouvert | Calques ou zones sélectionnées | Filtre ou effet choisi | Paramètres configurés | Résultat                                    |
|------------------|---------------------------------|-------------------------|-----------------------|---------------------------------------------|
| Vrai             | Vrai                            | Vrai                    | Vrai                  | Filtre ou effet appliqué selon les paramètres |
| Faux             | Vrai                            | N/A                     | N/A                   | Pas d'application de filtre ou effet        |
| Vrai             | Faux                            | Vrai                    | N/A                   | Pas d'application de filtre ou effet        |
| Vrai             | Vrai                            | Faux                    | N/A                   | Pas d'application de filtre ou effet        |
| Vrai             | Vrai                            | Vrai                    | Faux                  | Pas d'application de filtre ou effet        |

### 6. Enregistrer et Exporter des Œuvres:

Préconditions:
- Un espace de travail est ouvert et contient une œuvre à enregistrer ou exporter.
- Format et paramètres d'exportation choisis (résolution, type de fichier, qualité, etc.).

Postconditions:
- L'œuvre est enregistrée ou exportée selon les paramètres choisis.
- Les fichiers sont enregistrés dans le dossier spécifié ou exportés vers une destination externe.

Table de décision:

| Workspace ouvert | Œuvre à enregistrer ou exporter | Format et paramètres choisis | Destination spécifiée | Résultat                                      |
|------------------|----------------------------------|------------------------------|-----------------------|-----------------------------------------------|
| Vrai             | Vrai                             | Vrai                         | Vrai                  | Œuvre enregistrée ou exportée selon les paramètres |
| Faux             | Vrai                             | N/A                          | N/A                   | Pas d'enregistrement ou d'exportation         |
| Vrai             | Faux                             | Vrai                         | N/A                   | Pas d'enregistrement ou d'exportation         |
| Vrai             | Vrai                             | Faux                         | N/A                   | Pas d'enregistrement ou d'exportation         |
| Vrai             | Vrai                             | Vrai                         | Faux                  | Pas d'enregistrement ou d'exportation         |

## 7. Invariant pour la classe Calque:

L'invariant de la classe Calque peut être exprimé en logique propositionnelle de la manière suivante :

- Opacité : 0 <= opacité <= 1
- Visibilité : visible == True ou visible == False
- Contenu : contenu n'est pas None
- Initialisation correcte : nom n'est pas None et nom != ""

Ainsi, l'invariant pour la classe Calque peut être exprimé comme suit :

(0 <= opacité <= 1) ∧
(visible == True ∨ visible == False) ∧
(contenu n'est pas None) ∧
(nom n'est pas None ∧ nom != "")

Cet invariant garantit que la classe Calque maintient un état correct à tout moment.

## Tables de décision pour les tests unitaires

### Opération 1 : fusionner(autre: Calque)

Préconditions :
- Les calques this et autre doivent être visibles (visible == True).
- L'opacité des deux calques doit être dans la plage valide [0,1].

Postconditions :
- Un nouveau calque est renvoyé, représentant l'état fusionné de this et autre.
- L'opacité du nouveau calque est une valeur valide (moyenne de this.opacité et autre.opacité).
- Le nouveau calque est visible si this et autre sont visibles.

Voici la table de décision pour l'opération fusionner :

| Cas de test | this.visible | autre.visible | this.opacité | autre.opacité | Résultat     |
|-------------|--------------|---------------|--------------|---------------|--------------|
| 1           | True         | True          | 0.5          | 0.5           | Succès       |
| 2           | False        | True          | 0.5          | 0.5           | Exception    |
| 3           | True         | False         | 0.5          | 0.5           | Exception    |
| 4           | True         | True          |

### Opération 2 : dupliquer()

Préconditions :
- Le calque doit être visible (visible == True).
- L'opacité doit être dans la plage valide [0,1].

Postconditions :
- Un nouveau calque est renvoyé, représentant une copie identique du calque courant.
- L'opacité du nouveau calque est identique à this.opacité.
- La visibilité du nouveau calque est identique à this.visible.

Voici la table de décision pour l'opération dupliquer :

| Cas de test | this.visible | this.opacité | Résultat  |
|-------------|--------------|--------------|-----------|
| 1           | True         | 0.5          | Succès    |
| 2           | False        | 0.5          | Exception |
| 3           | True         | 1.1          | Exception |
| 4           | True         | -0.1         | Exception |


