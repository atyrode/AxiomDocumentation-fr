# Pinceau a bruit

Le **Pinceau a bruit** est un outil de peinture extrêmement polyvalent qui permet à l'utilisateur d'utiliser des bruits procéduraux pour peindre dans le monde. Il existe une grande variété de bruits qui peuvent être sélectionnés et configurés, chacun ayant des options et des motifs uniques utiles dans différents scénarios.

La première option unique est le basculement pour le réglage '3D'. Cela permet de calculer le bruit en 3D, permettant de peindre les côtés des surfaces au lieu de simplement le dessus.

Ensuite, nous avons l'option d'échelle, qui ajuste la taille du bruit par rapport à la grille de blocs. Une échelle plus grande signifie que le motif de bruit est réparti sur une plus grande zone de blocs.

## Bruits

Il existe quelques paramètres partagés entre les différents bruits. Les options communes entre ces bruits sont listées ci-dessous, avec des paramètres spécifiques pour chaque bruit décrits dans leurs sections respectives.

- **Octaves :** Ce paramètre détermine le nombre de couches de bruit utilisées. Plus il y a d'octaves, plus les détails et la complexité sont grands, mais cela vient avec un coût de calcul plus élevé.
- **Lacunarité et Gain** peuvent être configurés uniquement lorsque vous avez plus d'une octave pour votre bruit.
- **Lacunarité :** Ceci influence la "fréquence" de chaque octave. Une valeur plus élevée augmente la fréquence, ce qui entraîne des caractéristiques plus petites dans le motif de bruit.
- **Gain :** Ceci contrôle l'amplitude de chaque octave. Une valeur plus élevée augmentera l'influence de chaque octave successive. Une valeur plus basse rendra l'effet de l'octavation plus subtil.
- **Seed :** La valeur de la graine est utilisée pour initialiser l'algorithme de génération de bruit, fournissant un point de départ. Différentes graines produisent différents motifs de bruit, mais la même graine produira toujours le même motif.
- **Instabilité :** Cette valeur contrôle à quel point le bruit cellulaire semble uniforme en limitant la quantité de mouvement des points de graine hors de leur arrangement de grille de départ.

### Simplexe
    
Le bruit Simplexe génère un motif lisse et continu qui ressemble souvent à un terrain vallonné ou ondulé lorsqu'il est visualisé.

### Worley

Le bruit Worley, également connu sous le nom de bruit cellulaire, crée un motif qui ressemble à des cellules irrégulières ou à des diagrammes de Voronoi.

### Voronoi Edges

Ce type de bruit accentue spécifiquement les bords ou les frontières entre les cellules formées dans les diagrammes de Voronoi.

### Métaballe

Le bruit Metaball crée un motif qui ressemble à des blobs ou des sphères se chevauchant.

### Blanc

Le bruit blanc génère un motif complètement aléatoire sans structure discernable.

## Blocs

La section sous la configuration du bruit vous permet de spécifier les blocs utilisés pour peindre, ainsi que de déterminer leur distribution au sein du motif de bruit.

## Aperçu

Enfin, sous les paramètres, il y a trois fenêtres pour aider à visualiser le motif de bruit, la distribution cumulative et la densité de probabilité.