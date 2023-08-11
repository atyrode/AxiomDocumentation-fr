# Distordre

L'outil **Distordre** utilise un concept appelé « Distorsion de Domaine » avec un bruit Simplex pour déformer une zone donnée. En pratique, cela rend les zones plus accidentées. Cela peut aider à donner plus de profondeur et de texture aux zones plates ou à ajouter des bosses et des creux dans un terrain plus fini. Il fait cela à l'intérieur du chemin de coup de brosse qui peut être défini par les paramètres de la brosse.

La distorsion peut être configurée davantage pour affiner la manière dont vous souhaitez déformer le terrain. L'échelle détermine l'échelle du bruit Simplex utilisé pour effectuer la distorsion de domaine. Elle peut être configurée pour des tailles plus grandes si l'échelle n'est pas assez grande. Elle peut également être configurée avec la graine pour utiliser différentes graines ou des graines aléatoires.

La distance de la distorsion augmente la portée dans laquelle le bruit déforme. Une distance de 2 étant en moyenne à 2 blocs de distance de la position cible. Étant donné que le bruit est continu, la portée peut être réglée sur des nombres non entiers pour affiner la portée, ce qui fait parfois apparaître de plus grands creux ou bosses en résultat. Une grande distance lui donnera un aspect plus « sévère ». Ces distances peuvent être séparées par axe en activant le bouton ***Axe distinct**.

L'option des bords lisses fusionne les bords du bruit avec le terrain existant pour éviter l'apparition de bords irréguliers et de forts contrastes entre les zones déformées.