# Masques d'Outils

Les Masques d'Outils permettent aux utilisateurs de définir des règles pour les outils, en appliquant leurs effets uniquement lorsque certaines conditions sont remplies. Utilisant la logique booléenne, les Masques d'Outils permettent aux utilisateurs de spécifier des conditions de blocs dans une variété de scénarios, tels qu'affecter seulement les blocs ayant de l'air au-dessus d'eux ou un type de bloc particulier en dessous. Ces configurations de règles, appelées 'Blocs de Règles', peuvent être facilement arrangées dans le menu des outils via une interface glisser-déposer, offrant une alternative conviviale aux langages de script. La configuration de votre masque est affichée sous forme de chaîne en haut du menu pour faciliter la copie, le partage et la sauvegarde. La logique du masque génère une sortie booléenne, signifiant soit 'vrai' soit 'faux'.

Les conditions sont regroupées en deux catégories principales : Logique et Masques.

## Conditions logiques

- **N'importe lequel (Any)**
La condition 'N'importe lequel' permet à toutes les règles à l'intérieur de ce bloc de prendre effet. Par exemple, lors de la sélection de plusieurs blocs pour le masquage, sélectionnez 'n'importe quel' bloc qui correspond à grass_block ou stone.

- **Tous (All)**
La condition 'Tous' nécessite que toutes les règles de ce bloc s'appliquent. Par exemple, si vous voulez sélectionner un bloc qui a de l'air au-dessus et de la terre en dessous. Cependant, des règles conflictuelles ne fonctionneront pas dans le même bloc 'Tous', ce qui signifie que vous ne pouvez pas avoir deux masques 'bloc =' ou deux masques 'au-dessus =' simultanément. Mais, il est possible d'imbriquer un autre bloc 'N'importe lequel' à l'intérieur.

- **Pas (Not)**
La condition 'Pas' inverse les résultats des règles, les rendant vrais seulement lorsque les conditions initiales ne sont pas remplies. Par exemple, en définissant la règle 'au-dessus = air' à l'intérieur d'un bloc 'Pas', sélectionnez tous les blocs qui n'ont pas d'air au-dessus d'eux.

En combinant ces conditions logiques, vous pouvez exprimer une large gamme de masques, vous permettant de sélectionner presque tous les blocs répondant à des critères spécifiques.

## Masques

Les masques sont des conditions qui dépendent de l'état de la cible ou de l'état des blocs environnants.

- **Bloc**
Le masque 'Bloc' renvoie vrai lorsque la cible correspond au bloc ou à l'état de bloc spécifié.
- **Y**
Le masque 'Y' renvoie vrai lorsque la cible correspond à la condition donnée relative au niveau de coordonnée Y du bloc. Il existe plusieurs conditions pour le masque Y qui peuvent être modifiées en cliquant sur le signe '='.
- **Sélectionné**
La condition 'Sélectionné' renvoie vrai lorsque le bloc cible se trouve dans la zone de sélection définie par l'utilisateur.
- **Supérieur à**
La condition 'Supérieur à' est vraie lorsque le bloc directement au-dessus du bloc cible correspond au bloc ou à l'état de bloc spécifié.
- **Inférieur à**
La condition 'Inférieur à' est vraie lorsque le bloc directement en dessous du bloc cible correspond au bloc ou à l'état de bloc spécifié.
- **Proche de**
La condition 'Proche de' est vraie lorsque l'un des blocs dans la zone 3x3 (26 blocs) entourant la cible correspond au bloc ou à l'état de bloc spécifié.
- **Voisin de**
La condition 'Voisin de' renvoie vrai lorsque l'un des six blocs directement adjacents (haut, bas, nord, sud, est, ouest) à la cible correspond au bloc ou à l'état de bloc spécifié, permettant au masque de vérifier le voisinage immédiat du bloc cible.