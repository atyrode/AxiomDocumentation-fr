# Outils de Sélection

Cette section couvre les outils de sélection et leurs options. Une option qui est générique à tous les outils de sélection est un concept connu sous le nom d'**opérations booléennes**. L'option par défaut est "ajouter".

| Opération Booléenne | Description |
| --- | --- |
| Ajouter | Ajoute la zone sélectionnée à la sélection actuelle |
| Soustraire | Soustrait la zone sélectionnée de la sélection actuelle |
| Remplacer | Remplace la sélection actuelle par la zone sélectionnée |
| Intersection | Sélectionne uniquement la zone qui chevauche la sélection actuelle |

> Note : À très grande échelle, les sélections non parallélépipédiques deviennent moins performantes en raison de la complexité de la prise en compte de toute la région. Si vous devez effectuer une opération sur une très grande zone, il est recommandé d'utiliser une sélection en forme de parallélépipède et d'englober toute la construction.