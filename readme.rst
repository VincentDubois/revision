====================
Git : Tp de révision
====================

------------
Présentation
------------

L'objectif de ce TP est de créer en groupe une page présentant quelquess
framework web (un par étudiant), en utilisant git et GitHub pour mettre en
commun le travail de chacun. Il s'agit d'une répétition générale pour le TP noté.

Ce dépôt contient la version initiale du projet.

---------------
Recommandations
---------------

L'éditeur de code Atom (installé à l'iut) dispose par défaut d'un plugin
permettant de travailler avec git et GitHub. La plupart des IDE modernes
possédant ce genre de fonctionnalité, c'est une bonne idée que d'essayer
de s'en servir. En cas de problème ou de doute, ou pour utiliser des commandes
non gérées par l'interface, la ligne de commande reste toujours disponible

------------------
Utilisation d'Atom
------------------

L'onglet package->GitHub permet d'accéder à l'onglet git/GitHub. On y retrouve
en gros les informations fournies par un ``git status`` :

- Les fichiers modifiés mais pas ajoutés (en rouge dans ``git status``)  sont
  dans 'Unstaged changes'
- Les fichiers modifiés et ajoutés (pour lesquels on a fait ``git add`` et qui
  seraient en vert dans un ``git status``) sont dans 'staged changes'
- On passe de l'un à l'autre en cliquant sur le +
- La branche active est indiquée en dessous

L'onglet navigation (à gauche) d'atom utilise aussi un code couleur pour
signaler ces mêmes informations (il y a des couleurs différentes pour
chaque cas possible signalé par ``git status``, y compris les fichiers
non encore suivis etc...)

Il est possible de réaliser la plupart des commandes vues en ligne avec cette
interface (à noter que le bouton 'fetch' propose d'autres options avec un clic
droit). De plus, certaines actions concernant GitHub peuvent être réalisées
directement à partir de l'interface (comme les Pull Request).
Le menu Package->Open on GitHub permet aussi d'ouvrir directement la page
souhaitée sur GitHub.
