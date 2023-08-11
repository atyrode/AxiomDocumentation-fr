# Sélection Magique

L'outil **Sélection Magique** est un outil de sélection puissant qui améliore considérablement le processus de construction s'il est utilisé correctement. Avec un simple clic sur un type de bloc, l'outil Sélection Magique sélectionne rapidement tous les blocs adjacents du même type, simplifiant le processus de sélection.

L'outil propose les options suivantes :
Le mode d'option **Comparer à** vous permet de sélectionner les types de blocs qu'il peut sélectionner adjacents au bloc d'origine. Le mode par défaut est "Bloc".

| Type de Comparaison | Description |
| --- | --- |
| Bloc | Tous les blocs du même type, y compris tous les états de bloc. |
| État des Blocs (BlockState) | Tous les blocs ayant exactement le même état que le bloc cible. |
| Solide | Tout bloc à travers lequel vous ne pouvez pas passer. Par exemple la pierre, les vitres, etc. Pas de fleurs, d'eau, etc. |
| N'importe | Tous les blocs directement adjacents, y compris les blocs non solides, sauf l'air. Cela le fait "s'arrêter" dès qu'il atteint l'air. |

L'option **Limite** est un curseur qui peut être configuré pour définir combien de blocs il doit sélectionner au total. L'algorithme de sélection magique fonctionne en s'étendant vers l'extérieur depuis le bloc central pour former un octaèdre. Augmenter la limite vous permet simplement de sélectionner plus de blocs. La limite par défaut est fixée à 100 000 blocs, mais peut être fixée à n'importe quelle limite arbitraire.

L'option **Portée** est un curseur qui vous permet de définir à quelle distance l'algorithme doit rechercher des blocs adjacents. Cela permet à l'outil de "sauter l'écart" entre deux blocs. La portée représente simplement la distance qu'il peut parcourir avant de s'arrêter. Par exemple, un arbre buissonnant peut avoir deux blocs d'air ou plus entre ses feuilles et ses bûches. Cela vous permet de sélectionner toutes les feuilles qui sont sur l'arbre, indépendamment du fait qu'il y ait des blocs d'air entre deux branches avec des feuilles.

L'option **Seulement la surface** est une bascule qui fait que l'outil ne sélectionne que les blocs à la surface de la sélection ou, de manière équivalente, tous les blocs adjacents à l'air ou à "l'extérieur".