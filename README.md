# Analyser des données ouvertes choisies librement

La science actuelle réalise un tournant depuis ces dernières années afin d'être **ouverte**. Le terme en anglais est *Open Science*, science ouverte. Il s'agit ici de rendre les analyses accessibles et de documenter tout le processus qui mène aux résultats obtenus. Il s'agit aussi de rendre les publications librement accessibles. Cette volonté de rendre la science plus transparente va de pair avec l'*Open Data*, données ouvertes. Cela signifie que les données sont également rendue publiques et accessibles.

Lors de la publication d'articles scientifiques, il est de plus en plus courant que les revues demandent aux auteurs de rendre leurs données disponibles en open data. Il est même conseillé de fournir le code employé pour réaliser les analyses statistiques. On peut mettre en avant quelques avantages de ces bonnes pratiques :

-   Reproductibilité : En fournissant les données et le code, les autres scientifiques peuvent reproduire les analyses et les résultats. Cela contribue à renforcer la transparence et la confiance dans les résultats de l'étude.

-   Vérification des résultats : Les données et le code peuvent être utilisés pour vérifier les résultats de l'étude et détecter les erreurs ou les biais. Cela contribue à renforcer la qualité de la recherche scientifique et à éviter les erreurs.

-   Réutilisation des données : Les données peuvent être réutilisées pour d'autres études, ce qui permet de maximiser l'utilisation des ressources.

-   Accélération de la recherche : En partageant les données et le code, les autres scientifiques peuvent construire sur les résultats de l'étude plus rapidement et plus efficacement. Cela peut accélérer la recherche scientifique et aider à trouver des solutions plus rapidement.

-   Meilleure collaboration : En partageant les données et le code, les scientifiques peuvent collaborer plus facilement et travailler ensemble pour résoudre des problèmes complexes.

La mise à disposition des données (et du code employé) doit respecter certains critères que l'on peut regrouper sous l'acronyme FAIR pour *Findable*, *Accessible*, *Interoperable*, *Reusable*. Des données qui ne respectent pas ces critères sont, en pratique, partiellement, voire totalement inutilisable.

## Objectifs

Ce projet est **libre** et sera réalisé en **groupes de quatre étudiants**. Répartissez-vous le travail. Il permettra de démontrer que vous avez acquis les compétences suivantes :

-   trouver des données ouvertes qui se prêtent à une analyse multivariée de type SOM (tout le monde cherche et vous choisissez de manière collégiale le jeu de données à retenir au final)

-   critiquer les données trouvées selon le principe FAIR (chaque étudiant rédige la partie relative à un des critères)

-   réaliser une SOM sur ces données et l'analyser (tous les étudiants doivent rédiger une partie du rapport, répartissez-vous les tâches au départ)

## Consignes

La première étape de ce travail consiste dans la recherche de données ouvertes. Vous suivrez les instruction du fichier `data/README` pour récupérer vos données depuis une URL de téléchargement directe avec mise en cache dans `data/cache`. Si ce n'est pas possible, il faudra le justifier dans le rapport et placer les données manuellement dans le sous-dossier `data` (max 50Mo). **Avant de faire un choix définitif de votre jeu de données, assurez-vous que le contenu du tableau de données convient pour la réalisation d'une analyse multivariée de type SOM**. Cela fait partie de l'exercice que de choisir un jeu de données adéquat ici !

Voici plusieurs sites que vous pouvez utiliser pour rechercher vos données :

-   [Zenodo](https://zenodo.org/)

-   [Dryad](https://datadryad.org/)

-   [Free and open access to biodiversity data](https://www.gbif.org/)

-   [The Knowledge Network for Biocomplexity](https://knb.ecoinformatics.org/data)

-   [EDI Data Portal](https://portal.edirepository.org/nis/home.jsp)

La deuxième partie de ce travail consiste à expliquer de manière détaillée en quoi les données choisies répondent (ou non) au principe FAIR. est de proposer une critique des données sélectionnées sur base du principe FAIR dans le document `docs/open_data.Rmd`.

Enfin, dans la dernière partie de ce projet, vous complétez le rapport dans `docs/analysis.Rmd`. Vous réalisez et interprétez une analyse multivariée de type SOM sur les données choisies. Dans le cas où vous vous rendriez compte que cela ne fonctionne pas, justifiez pourquoi et expliquez en quoi vous n'étiez pas capables avant de faire l'analyse de déterminer que ces données ne conviendraient pas. Dans ce cas, nous déterminerons si vos justifications tiennent la route pour établir votre notre de la troisième partie du travail.

N'oubliez pas de **knitter** les documents en HTML à la fin pour vérifier que tout fonctionne bien, et corrigez les erreurs éventuelles rencontrées à ce stade avant de clôturer votre projet. Vérifiez également que votre dernier commit a bien été pushé sur GitHub avant la deadline.

Ce projet correspond au template <https://github.com/BioDataScience-Course/B10Ga_open_data>.
