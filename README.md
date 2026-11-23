# Introduction

This repository contains resources to review scientific software repositories, with a focus on reproducibility.

# How it works

To review a repository, create a file named `reviews/YYYY-MM-DD_name-of-repo.md`, copy paste the following template, and review the repository by filling out said template.

Do not create any issue or pull request in the repository being reviewed: the task of taking appropriate corrective measures in response to the review is the responsibility of the repository's maintainers.

```
 - URL of the repository:

 - Commit being reviewed:

 - Référencement, accessibilité, réutilisation

   * [ ] [niveau 1] Le repo est public
   * [ ] [niveau 1] Le repo est synchronisé sur Software Heritage
   * [ ] [niveau 1] Une LICENSE est associée au logiciel

 - README.md

   * [ ] [niveau 1] Le README est présent
   * [ ] Le README décrit / contient:
     - [ ] [niveau 1] le nom du programme
     - [ ] [niveau 1] à quoi sert le programme
     - [ ] [niveau 1] instructions pour l'installation du programme et de ses dépendances
     - [ ] [niveau 1] un quick start : comment lancer le programme sur un test quelconque, le plus rapidement possible
     - [ ] [niveau 2] un lien vers une documentation plus fournie le cas échéant
   * [ ] [niveau 1] Présence d'une documentation utilisateurs.trices (qui peut se trouver dans le README.md)
   * [ ] [niveau 1] Présence des DOI/liens vers les articles cités, le cas écheant
   * [ ] [niveau 2] Le repo contient un fichier citation.cff pour indiquer comment citer le logiciel
   * [ ] [niveau 2] Un fichier CONTRIBUTING.md et/ou GOVERNANCE.md qui décrit comment contribuer
   * [ ] [niveau 2] Présence d'un changelog ou de release notes
   * [ ] [niveau 2] Présence d'exemples d'utilisation
   * [ ] [niveau 2] Présence d'un jeu de données test ou d'une explication d'où le trouver, le cas échéant
   * [ ] [niveau 2] Présence des DOI vers les jeux de données cités, le cas échéant

- Clarté du code

   * [ ] [niveau 1] Est-ce que le code est découpé de manière modulaire ?
   * [ ] [niveau 2] Est-ce que le code est linté ? Est-ce qu'une CI contrôle le linting ?
   * [ ] [niveau 1] Est-ce que la signature de chaque fonction est documentée ? Avec un format homogène ?
   * [ ] [niveau 1] Présence d'un .gitignore pour lutter contre l'inclusion de fichiers parasites

- Tests

   * [ ] [niveau 1] Présence de tests unitaires
   * [ ] [niveau 1] Présence de tests d'intégration
   * [ ] [niveau 2] Est-ce qu'il existe une CI qui vérifie les tests ?
   * [ ] [niveau 2] Est-ce que la couverture des tests est mesurée ?

- Versioning / reproductibilité

   * [ ] [niveau 1] Est-ce qu'il existe des versions facilement identifiables du logiciel (tags, releases) ?

- Cas spécifiques:

   * [ ] Python:
     - [ ] [niveau 1] le dépôt contient un pyproject.toml
     - [ ] [niveau 1] le package est installable via pip
```
