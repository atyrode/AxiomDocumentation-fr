# Bioaltérer

L'outil **Bioaltérer** est un ensemble d'outils de peinture prédéfinis qui ont généralement un ensemble complexe de règles de placement prédéfinies qui ne relèvent pas d'autres catégories. À cause de cela, ils utilisent souvent des algorithmes avancés pour produire des motifs intéressants mais sont plus spécifiques dans les cas où ils peuvent être utilisés.

L'outil **Bioaltérer** vous permet de configurer le pinceau pour définir le chemin du trait, comme les autres outils. Il dispose également de deux autres options qui peuvent être activées et configurées : **Terrain** et **Décorations**. Ils peuvent être combinés pour offrir une large gamme de personnalisation.

## Terrain

Ces préréglages affectent les blocs solides dans votre trait de pinceau.

### Pierre

Le préréglage Terrain Pierre est un outil de terrain très simple, ne fixant que la base en pierre.

### Herbe

Le préréglage Terrain Herbe naturalise le terrain en faisant de la couche supérieure des blocs d'herbe suivis de 3-4 couches de terre et tout terrain en dessous de cela étant mis en pierre.

### Sable

Le préréglage Terrain Sable crée un terrain désertique en faisant les 4-5 couches supérieures en sable et les blocs en dessous en grès.

### Sol de Terre

Le préréglage Terrain Sol en Terre utilise un algorithme de collapse de fonction d'onde pour créer un motif de terre mélangé à des taches de boue sèche et de terre grossière pour réaliser rapidement un sol pour les sols de forêts, les chemins, etc.

### Sol de Gravier

Le préréglage Terrain Sol en Gravier utilise un algorithme de collapse de fonction d'onde pour créer un motif de pierre mélangé avec des taches de gravier et de pierre taillée pour obtenir rapidement un motif rocheux rugueux, utile pour les éboulis de montagne, les chemins, etc.

### Fond d'Océan Fertile

Le préréglage Terrain Fond d'Océan Fertile utilise un mélange de voronoi en couches ainsi que des motifs de bruit cellulaire pour créer un aspect varié d'un fond d'océan, de marais ou de lit de rivière dans des zones d'eau "fertiles" telles que les mangroves près des océans, les marais, les embouchures/deltas de rivières, etc.

## Décorations

Ces préréglages affectent les blocs non solides, souvent destinés à être placés sur un terrain existant pour améliorer l'esthétique.

### Supprimer

Le préréglage Décoration Supprimer n'est pas un pinceau "vide", il peut être utilisé pour effacer d'autres décorations trouvées dans la génération naturelle ou placées par d'autres préréglages. Utile pour créer par exemple une clairière dans une forêt.

### Herbe

Le préréglage Décoration Herbe utilise un bruit de Perlin pour disperser aléatoirement des parcelles denses d'herbe selon un motif plaisant afin de décorer rapidement un biome de plaines, les bords à côté des chemins, etc. Lors de la sélection du préréglage décoration herbe, deux nouveaux sous-paramètres apparaissent :

- Un curseur d'herbivorie allant de 0 à 1 (non limité mais aller au-dessus de 1 n'a aucun effet) pour indiquer à quel point une zone doit être "herbeuse". Plus il est proche de 1, plus il y a d'herbe.
- Une bascule "Permettre l'herbe haute" qui permet aux zones les plus denses du bruit de Perlin d'utiliser de l'herbe haute. Cela donne l'impression que l'herbe devient plus dense à mesure que l'on avance, ce qui peut être utile pour des zones plus sauvages.