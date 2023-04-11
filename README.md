# Reproduction d'une analyse multivariée d'un article avec des données ouvertes

La science actuelle réalise un tournant depuis ces dernières années afin d'être ouverte. Le terme en anglais est *Open Science*, science ouverte. Cette volonté de rendre accessible la science est venue de pair avec l'*Open data*, données ouvertes.

Lors de la publication d'articles scientifiques, il est de plus en plus courant que les revues demandent aux auteurs de rendre leurs données disponibles en open data. Il est même conseillé de fournir le code employé pour réaliser les analyses statistiques. On peut mettre en avant quelques avantages de ces bonnes pratiques :

-   Reproductibilité : En fournissant les données et le code, les autres scientifiques peuvent reproduire les analyses et les résultats. Cela contribue à renforcer la transparence et la confiance dans les résultats de l'étude.

-   Vérification des résultats : Les données et le code peuvent être utilisés pour vérifier les résultats de l'étude et détecter les erreurs ou les biais. Cela contribue à renforcer la qualité de la recherche scientifique et à éviter les erreurs.

-   Réutilisation des données : Les données peuvent être réutilisées pour d'autres études, ce qui permet de maximiser l'utilisation des ressources.

-   Accélération de la recherche : En partageant les données et le code, les autres scientifiques peuvent construire sur les résultats de l'étude plus rapidement et plus efficacement. Cela peut accélérer la recherche scientifique et aider à trouver des solutions plus rapidement.

-   Meilleure collaboration : En partageant les données et le code, les scientifiques peuvent collaborer plus facilement et travailler ensemble pour résoudre des problèmes complexes.

La mise à disposition des données (et du code employé) doit respecter certains critères que l'on peut regrouper sous l'acronyme FAIR pour Findable, Accessible, Interoperable, Reusable. Des données qui ne respectent pas ces critères sont en pratique inutilisable.

## Objectifs

Ce projet est **libre** et sera réalisé en **groupes de quatre étudiants**. Il permettra de démontrer que vous avez acquis les compétences suivantes :

-   trouver des données ouvertes associées à un article scientifique publié utilisant des analyses multivariées

-   critiquer les données trouvées selon le principe FAIR

-   reproduire l'analyse multivariée réalisée dans l'article

-   critiquer cette analyse multivariée

## Consignes

La première étape de ce travail consiste dans la recherche de données ouvertes. Ces données doivent être **associées à un article scientifique** et **employées afin de réaliser une analyse multivariée**. Les données devront être placées dans le dossier **data/**.

Nous vous proposons plusieurs sites en ligne pour vous aider dans vos recherches :

-   [zenodo](https://zenodo.org/)

-   [ORBI Umons](https://orbi.umons.ac.be/)

-   [Dryad](https://datadryad.org/)

-   [Free and open access to biodiversity data](https://www.gbif.org/)

-   [The Knowledge Network for Biocomplexity](https://knb.ecoinformatics.org/data)

-   [EDI Data Portal](https://portal.edirepository.org/nis/home.jsp)

La deuxième partie de ce travail est de proposer une critique des données sélectionnées sur base du principe FAIR dans le document **docs/open_data.Rmd**.

Enfin la dernière partie de ce projet consiste dans la reproduction de l'analyse multivariée sur base des données sélectionnées dans le document **docs/analysis.Rmd**. Citez correctement vos données et l'article scientifique employé.

N'oubliez pas de **knitter** les documents en HTML à la fin du travail pour vérifier que tout fonctionne bien, et corrigez les erreurs éventuelles rencontrées à ce stade avant de clôturer votre travail. Vérifiez également que votre dernier commit a bien été pushé sur GitHub avant la deadline.
