ANNEE 2022 - 2023
Intégration continue, Analyse statique et Automatisation des tests

Pour ce tutoriel, nous utiliserons le front d'un projet réalisé dans le cadre du cours d'Architecture Logiciel fait en Angular.

## Problematique abordée:
L’objectif de ce travail était de se familiariser avec les outils d'intégration continue dans un contexte devops en donnant les différentes étapes du processus d’intégration continue, les différents outils utilisés, et en analysant également les résultats obtenus.L’intégration continue une pratique clé du processus DevOps qui consiste à intégrer fréquemment et automatiquement des modifications afin de détecter rapidement les erreurs et de réduire le temps nécessaire pour mettre à jour le code. Son processus implique l'utilisation d'outils d'automatisation de tests  qui permettent de compiler et de tester automatiquement le code à chaque modification, puis de signaler les erreurs aux développeurs. Les tests peuvent inclure des tests unitaires, des tests de performance, des tests de sécurité et d'autres types de tests qui vérifient que le code fonctionne correctement et est conforme aux exigences.

## Objectif:

Ces pratiques nous permettront d'améliorer la qualité de notre code, de détecter les erreurs plus rapidement et de déployer des versions de votre application plus rapidement et en toute confiance. Un des principaux but du DevOps


## Presentation d'outils
- Pour l'intégration continue
Il existe plusieurs plateformes d'intégration continue, telles que Travis CI, CircleCI, Jenkins, GitLab CI/CD, qui offrent des plans gratuits pour les projets open source.
- Pour l'analyse statique du code
On configure l'analyse statique du code en ajoutant des outils d'analyse statique tels que SonarQube, CodeClimate, Codacy, etc. Ces outils peuvent détecter des problèmes de qualité de code tels que des vulnérabilités, des erreurs de syntaxe et des erreurs de style.
- Pour l'automatisation des tests
On ajoute des tests automatisés pour les différentes parties de l'application en utilisant des frameworks de test tels que JUnit, PyTest, Mocha, etc. Ces tests automatisés doivent être ajoutés dans le fichier de configuration de l'étape de test sur la plateforme d'intégration continue.

## Utilisation des outils:
Nous nous sommes tournés vers l'utilisation de la version gratuite d'azure devops qui est une plateforme de microsoft qui nous regroupe tout ce dont on a besoin pour lancer l'intégration continue (à travers un fichier azure-pipelines.yml) avec une interface assez intuitive et interactive facilitant la , concernant l'analyse du code, nous la faisons via sonarqube

Les limites des outils qu'on a utlisés:
Jenkins :
Configuration complexe : La configuration de Jenkins peut être complexe et difficile pour les débutants, ce qui peut nécessiter un certain temps pour apprendre et maîtriser.
Scalabilité : Bien que Jenkins soit très extensible, il peut ne pas être idéal pour les grandes équipes et les projets complexes qui nécessitent une grande capacité de traitement.
Dépendance aux plugins : Jenkins repose largement sur les plugins pour étendre ses fonctionnalités, ce qui peut entraîner des problèmes de compatibilité et de sécurité.
Maven :
Performance : Bien que Maven soit capable de gérer des projets de grande taille, il peut parfois être lent en raison de son approche basée sur les plugins et la configuration XML.
Dépendances : Maven gère les dépendances des projets en téléchargeant les bibliothèques requises à partir des dépôts centraux, ce qui peut poser des problèmes si les bibliothèques sont absentes ou obsolètes.
Intégration avec d'autres outils : Bien que Maven dispose d'une intégration solide avec de nombreux outils de développement, il peut être difficile d'intégrer certains outils personnalisés ou tiers.
JUnit :
Tests complexes : JUnit peut être limité dans la prise en charge de tests unitaires complexes ou sophistiqués.
Couverture de code : JUnit ne fournit pas de fonctionnalités de couverture de code intégrées, vous devez utiliser un plugin tiers ou une autre solution pour obtenir une couverture de code détaillée.
Test d'intégration : JUnit est conçu pour les tests unitaires et peut ne pas être idéal pour les tests d'intégration, qui peuvent nécessiter des outils supplémentaires pour être gérés.

