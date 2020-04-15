## Intérêts de recherche

Je m’intéresse à plusieurs sujets en combinatoire algébrique. Dans le cadre de mon mémoire, j’ai travaillé sur la théorie de la représentation, les tableaux domino, les produits de polynômes de Schur,  les produits de tableaux ainsi que sur les cristaux. Ce sont des sujets qui continuent à m’intéresser. Je m’intéresse présentement à divers algorithmes sur les tableaux de rubans (dont les tableaux domino sont un cas particulier). Dans le cadre de mon doctorat, je souhaite me pencher sur les produits de polynômes de Schubert (dont les polynômes de Schur sont un cas particuliers), et principalement les représentations combinatoires de ceux-ci. Ces polynômes sont fortement liés à la théorie de la représentation, et à la cohomologie des variétés de drapeaux, dont ils forment une base. Je m’intéresse également aux variétés dites de Hessenberg, qui généralisent les variétés de drapeaux et pour lesquelles une base combinatoire devrait exister. Il s’agit d’un sujet à la pointe de la recherche actuelle.

Plus généralement, je m'intéresse aux approches combinatoires à différents problèmes mathématiques.

## Thèse de doctorat

**Titre :** Modèles combinatoires pour le produit de polynômes de Schubert

Pour un ensemble d'objets mathématiques, une base linéaire est un sous-ensemble tel que chaque objet du grand ensemble peut être exprimé de façon unique par une somme d'objets de ce petit ensemble. Les fonctions de Schur et les polynômes de Schubert constituent des bases pour des espaces de polynômes. Dans le cadre de mon mémoire, j'ai étudié les fonctions de Schur, qui forment une base de l'ensemble des polynômes symétriques. Les fonctions de Schur sont des cas particuliers des polynômes de Schubert, qui constituent également une base, cette fois pour un espace de polynômes plus grand.

Dans mon mémoire, j'ai étudié plusieurs règles combinatoires pour la multiplication de deux fonctions de Schur, et j'ai tenté de vérifier si ces descriptions étaient bonnes au sens de la théorie des cristaux. Pour le doctorat, le problème qui m'intéresse est de comprendre le produit de deux polynômes de Schubert, puisqu'il s'agit d'une généralisation du problème sur lequel je me suis penché durant ma maîtrise. Ces polynômes peuvent être très longs, complexes et avoir une infinité de variables; on ne peut donc pas se contenter de calculer explicitement leur produit. Il faut plutôt trouver des méthodes détournées pour l'exprimer. La combinatoire est alors une méthode tout indiquée.

Les fonctions de Schur peuvent être décrites par une sommation sur des objets combinatoires appelés tableaux de Young semi-standards. Plusieurs modèles combinatoires ont été avancés pour décrire de façon similaire les polynômes de Schubert. En particulier, on souhaite obtenir un modèle conséquent avec celui déjà existant pour les fonctions de Schur, puisque ce modèle a été déterminant pour le développement de la théorie des fonctions de Schur. On voudrait de plus que le modèle choisi soit donné par des objets combinatoires sur lesquels il est possible d'effectuer des manipulations, car cela permet de rendre les calculs plus efficaces.

Macdonald a décrit la combinatoire sous-jacente aux polynômes de Schubert en 1991, alors qu'il était en résidence au LaCIM (Laboratoire de combinatoire et d'informatique mathématique) à l'UQAM. Billey, Jockush et Stanley ont décrit un modèle combinatoire pour les polynômes de Schubert en 1993, et de nombreux modèles combinatoires ont été développés par la suite. Entre autres, Assaf regroupe et compare plusieurs modèles dans un article publié en 2017: graphes réduits, tableaux balancés, tableaux de Rothe et diagrammes de Kohnert. D'autres modèles existent encore, comme les tableaux de prisme, les pipe dreams, etc.

Quel modèle retenir? Chacun apporte certaines réponses, a ses avantages et ses défauts. Un bon modèle serait conséquent dans toutes les situations, ou du moins dans la majorité des cas, et permettrait de faire des manipulations directement sur les objets combinatoires pour avoir des résultats sur les polynômes de Schubert. Nous ne connaissons toutefois pas assez les différents modèles pour déterminer si le meilleur se trouve parmi ceux-ci, ou s'il reste encore à développer. 

Je souhaite étudier les articles récents portant sur des modèles combinatoires des polynômes de Schubert pour faire une synthèse des connaissances du moment sur ceux-ci. Je propose d'analyser chacun de ces modèles sous la loupe de la théorie des cristaux, tel que je l'ai fait à la maîtrise. Cette approche des polynômes de Schubert par la théorie des cristaux a d'ailleurs été entamée par Anne Schilling.
Finalement, je compte développer et poursuivre l'étude des modèles les plus prometteurs.

**Un peu d'histoire:**

Les polynômes de Schubert ont été introduits par Lascoux et Schützenberger, en 1982, dans le cadre de la cohomologie de la variété de drapeaux complète. La cohomologie est une façon de rendre algébriques des problèmes géométriques et permet dans ce contexte de décrire la structure de la variété pour mieux la comprendre. Lascoux et Schützenberger ont montré que les polynômes de Schubert forment une base de cette cohomologie. Le produit de deux tels polynômes se décompose donc en terme de la base des polynômes de Schubert.

Les coefficients apparaissant dans cette décomposition donnent alors le nombre d'intersections de deux variétés de drapeaux. Les  polynômes de Schubert permettent donc de traiter ce problème géométrique de façon algébrique. Un problème fondamental pour la compréhension de la cohomologie des variétés de drapeaux est de comprendre comment développer le produit de polynômes de Schubert dans la base des polynômes de Schubert. Autrement dit, on cherche une formule pour décrire directement les coefficients apparaissant dans cette décomposition.

Malheureusement cela se révèle plutôt difficile. Par l'argument géométrique énoncé plus haut, on sait que ces coefficients sont des entiers non-négatifs, ce qui explique l'intérêt d'exploiter la combinatoire pour la résolution de ce problème. En effet, on cherchera à y associer des objets combinatoires possédant des caractéristiques particulières et dont l'énumération donnerait exactement ces coefficients.

La complexité algorithmique du calcul des coefficients mentionnés ci-haut est liée à la question VP = VNP, équivalente à P = NP. Ce problème est un des sept problèmes du millénaire. Une façon d'invalider la proposition (et montrer  que VP n'est pas égal à VNP est de trouver un contre-exemple, et notre problème aurait ce potentiel. Cela illustre la complexité de calculer ces coefficients en général. 

Assaf a d'ailleurs écrit en 2017 qu'un problème ouvert fondamental en calcul de Schubert est de trouver une construction combinatoire positive pour ces coefficients.

## Thèse de maîtrise

**Titre :** Structure de cristal sur les tableaux domino et produit de tableaux

De septembre 2017 à août 2019, j'ai travaillé à mon projet de maîtrise. J'ai étudié des méthodes combinatoires pour décrire le produit de deux fonctions de Schur. Celles-ci forment une base de l'algèbre des fonctions symétrique. On peut donc s'intéresser à l'expansion d'un tel produit dans la base des fonctions de Schur. Cette décomposition a tout particulièrement une signification en théorie de la représentation.

L'approche que nous avons utilisée est combinatoire: l'étude des fonctions de Schur est ramenée systématiquement à l'étude des tableaux de Young et des manipulations sur ceux-ci. De nombreuses méthodes combinatoires existent pour décrire ce produit en termes de tableaux de Young, et nous nous sommes penchés particulièrement sur deux de celles-ci : la règle de Littlewood-Richardson et le monoïde plaxique de Schützenberger et Lascoux. Cette deuxième méthode décrit une structure de monoïde non-commutatif sur les tableaux de Young. Nous nous sommes par la suite intéressés à une troisième méthode, due à Carré et Leclerc, qui définit le produit de deux fonctions de Schur en termes de tableaux domino: un tableau domino est alors décrit comme le produit de deux tableaux de Young.

Nous avons étudié ces descriptions de produits de tableaux sous la loupe de la théorie des cristaux.Celle-ci donne un cadre et une structure pour vérifier la bonne définition de ces produits. En particulier, il existe une structure de cristal sur les tableaux de Young. Il est de plus possible de définir le produit tensoriel de deux tels cristaux, qui se traduit par un produit de tableaux. Nous nous sommes donc intéressés à démontrer l'existence d'une structure de cristal sur les tableaux domino. Nous avons également souhaité vérifier si cette structure était alors compatible avec les produits de tableaux étudiés précédemment.

Pour ce faire, nous nous sommes basés sur des résultats de Carré, Leclerc et van Leeuwen. Nous avons confirmé l'existence d'une structure de cristal sur les tableaux domino, mais nous avons démontré qu'elle n'est pas tout à fait compatible avec le produit de cristaux de tableaux. Nous avons montré qu'il est nécessaire de faire des ajustements à la définition des tableaux domino comme produit de tableaux afin que la structure de cristal sur les tableaux domino soit compatible avec celle sur les produits de cristaux de tableaux. 

Ceci confirme que les tableaux domino ont le potentiel d'être des permettent de mieux comprendre le produit de deux fonctions de Schur. Nos résultats à la fois confrontent et confirment la vision préalablement établie de la communauté mathématique sur les cristaux de tableaux domino.

## Pulications

Set-valued domino tableaux and shifted set-valued domino tableaux, écrit en collaboration avec [Rebeccas Patrias](http://lacim.uqam.ca/~patriasr/), post-doctorante au LaCIM en 2017-2019.

Cet article a été développé suite à un stage de recherche de premier cycle sous la direction de Rebecca Patrias à l'été 2017. Nous avons généralisé des résultats connus sur les tableaux domino et les tableaux domino décalés à la \(K\)-théorie de la Grassmanniennne. L'article a été soumis pour révision en octobre 2018, suite à l'obtention de nouveaux résultats, et accepté pour publication en février 2020.

La revue Involve : a journal of Mathematics est un journal de mathématiques qui promeut la participation des étudiants de tous les niveaux à la recherche. Il ne publie que des articles de qualité dont au moins le tiers des auteurs sont des étudiants et un auteur est associé à une faculté académique. Les articles acceptés sont considérés par le jury comme admissibles dans les journaux de recherche du domaine de recherche.
