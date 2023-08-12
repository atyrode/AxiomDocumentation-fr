# Façonner

L'outil **Façonner** est un outil de sculpture basé sur le bruit, utile pour créer des terrains et des formes semblables à des rochers. Il peut être utilisé à la fois pour des roches et des blocs individuels ainsi que pour rendre les surfaces plus rocailleuses et rugueuses. Il utilise plusieurs paramètres qui modifient la façon dont les rochers se forment en général ainsi que par rapport à la surface sur laquelle ils sont placés. Il utilise le bloc actif pour déterminer la palette. Divers paramètres sont disponibles pour affiner le comportement de sculpture de l'outil :

## Paramètres du Bruit
Les paramètres du bruit permettent à l'utilisateur de configurer le degré d'aléatoire et de rugosité des roches créées par l'outil de sculpture. Il existe plusieurs paramètres qui peuvent être ajustés pour modifier le comportement du bruit.

Le rayon du bruit est un paramètre qui détermine l'"échelle" des modifications induites par le bruit. Un rayon de bruit plus grand implique une zone d'impact plus large, affectant plus de blocs, ce qui forme de plus grandes configurations semblables à des taches, généralement plus arrondies et lissées en raison de la plus grande distribution des changements. À l'inverse, un rayon de bruit plus petit, qui affecte moins de blocs, entraînera des modifications plus précises et dentelées, contraintes par la taille de la grille de voxel.

Le curseur "Bruit" affecte le degré d'irrégularité ou d'aléatoire des blocs sculptés. Un niveau d'intensité du bruit plus élevé donne des roches au look plus aléatoire et informe. Un niveau de bruit plus faible produit des roches plus lisses et sphériques. Combiné au rayon du bruit et à d'autres facteurs, cela peut influencer l'aspect final rugueux des roches.

Le champ Seed du champ de bruit vous permet d'entrer une seed si vous souhaitez continuer un motif que vous avez précédemment utilisé ou réutiliser après avoir joué avec les paramètres, par défaut il est aléatoire à chaque coup.

## Paramètres de Lissage
Les paramètres de lissage affectent le degré de lissage des roches produites par les paramètres précédents afin de créer une forme de roche plus cohérente et unifiée plutôt que d'être des taches flottantes.

Les paramètres d'écart-type du lissage vous permettent de définir la force du flou gaussien appliqué à l'outil. La plage par défaut va de 0 à 5 mais peut être étendue au-delà de la limite. 0 étant équivalent à n'avoir aucun lissage appliqué, 2 - le réglage standard - étant équivalent à avoir environ ~4 blocs de plage de lissage et 5 étant très lisse avec une plage d'environ ~10 blocs de lissage.

L'intensité de fusion est une caractéristique qui vous permet de déterminer la force avec laquelle une roche doit être fusionnée ou mélangée avec les blocs existants du monde. Cela amène les roches à s'adoucir davantage près des bords de la brosse afin d'atténuer les bords dentelés qu'une roche pourrait autrement avoir. La plage par défaut va de 0 à 3 mais peut être étendue au-delà de la limite, 0 n'ayant aucune fusion appliquée et étant simplement placée à la surface, 3 ayant un fort effet de fusion. La force de fusion est également affectée par le lissage, un lissage plus important causant des "bords fusionnés" plus finement intégrés aux blocs existants.