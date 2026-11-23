# Introduction

This repository contains resources to review scientific software repositories, with a focus on reproducibility.

# How it works

To review a repository, create a file named `reviews/YYYY-MM-DD_name-of-repo.md`, copy paste the following template, and review the repository by filling out said template.

Do not create any issue or pull request in the repository being reviewed: the task of taking appropriate corrective measures in response to the review is the responsibility of the repository's maintainers.

Note that we ranked reviewing criteria according to

 - L1 (level 1): all repositories should ideally checked these.
 - L2 (level 2): these criteria are a bit more advanced.

```
 - URL of the repository:

 - Commit being reviewed:

 - Findability, accessibility, reusability

   * [ ] [L1] The repository is public
   * [ ] [L1] The repository is backed up on [Software Heritage](https://www.softwareheritage.org/)
   * [ ] [L1] The software has an explicit license
   * [ ] [L1] The license is listed as a free and open source software license by the [open source initiative](https://opensource.org/licenses) and/or the [GNU project](https://www.gnu.org/licenses/license-list.html).

 - README.md

   * [ ] [L1] Le README est présent
   * [ ] Le README décrit / contient:
     - [ ] [L1] le nom du programme
     - [ ] [L1] à quoi sert le programme
     - [ ] [L1] instructions pour l'installation du programme et de ses dépendances
     - [ ] [L1] un quick start : comment lancer le programme sur un test quelconque, le plus rapidement possible
     - [ ] [L2] un lien vers une documentation plus fournie le cas échéant
   * [ ] [L1] Présence d'une documentation utilisateurs.trices (qui peut se trouver dans le README.md)
   * [ ] [L1] Présence des DOI/liens vers les articles cités, le cas écheant
   * [ ] [L2] Le repo contient un fichier citation.cff pour indiquer comment citer le logiciel
   * [ ] [L2] Un fichier CONTRIBUTING.md et/ou GOVERNANCE.md qui décrit comment contribuer
   * [ ] [L2] Présence d'un changelog ou de release notes
   * [ ] [L2] Présence d'exemples d'utilisation
   * [ ] [L2] Présence d'un jeu de données test ou d'une explication d'où le trouver, le cas échéant
   * [ ] [L2] Présence des DOI vers les jeux de données cités, le cas échéant

- Clarté du code

   * [ ] [L1] Est-ce que le code est découpé de manière modulaire ?
   * [ ] [L2] Est-ce que le code est linté ? Est-ce qu'une CI contrôle le linting ?
   * [ ] [L1] Est-ce que la signature de chaque fonction est documentée ? Avec un format homogène ?
   * [ ] [L1] Présence d'un .gitignore pour lutter contre l'inclusion de fichiers parasites

- Tests

   * [ ] [L1] Présence de tests unitaires
   * [ ] [L1] Présence de tests d'intégration
   * [ ] [L2] Est-ce qu'il existe une CI qui vérifie les tests ?
   * [ ] [L2] Est-ce que la couverture des tests est mesurée ?

- Versioning / reproductibilité

   * [ ] [L1] Est-ce qu'il existe des versions facilement identifiables du logiciel (tags, releases) ?

- Cas spécifiques:

   * [ ] Python:
     - [ ] [L1] le dépôt contient un pyproject.toml
     - [ ] [L1] le package est installable via pip
```
