Sources des données
Les données utilisées dans ce projet proviennent des informations trouvées sur le lien suivant :
https://khkgears.net/new/gear_knowledge/gear_technical_reference/calculation_gear_dimensions.html
Je me suis référé à la première figure et au premier tableau de cette page. (Fig. 4.1 & Table 4.1)

Implémentation dans Excel
Dans le fichier Excel, j'ai programmé les mêmes équations que celles du tableau du site en utilisant des fonctions VBA.
Les valeurs pertinentes sont accessibles sur la feuille intitulée "TableDeParametreStandard".

Intégration avec CATIA
Le fichier CATIA récupère directement les valeurs du fichier Excel et les convertit en paramètres. Ces derniers sont déjà au bon format (type et unité) pour une utilisation directe.
Dans le fichier CATIA, une esquisse sert de guide pour les différents diamètres (Reference Diameter, Base Diameter, Tooth Diameter et Root Diameter)
Ne connaissant pas précisément les proportions des dents, j'ai opté pour des formes elliptiques.
Veuillez noter que dans le fichier CATIA, vous pouvez choisir entre la configuration de la ligne 1 et celle de la ligne 2.

Progrès du projet
Au moment de la rédaction de ce README, les pièces n'ont pas encore été imprimées ni testées.
Cela est dû au fait que mon imprimante 3D refuse de coopérer, et je n'ai malheureusement pas le temps de m'en occuper pour l'instant.

Suggestions et retours
Si certains points ne sont pas clairs, s'il y a des erreurs ou si vous avez des recommandations, n'hésitez pas à me contacter à l'adresse suivante :
phil.balaz@gmail.com