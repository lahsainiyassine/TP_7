Exercice 1 — Gestion de la Paie des Employés
Ce qui est fait
Définition d'une classe abstraite Employe contenant l'identité de base (nom, prenom) et déclarant la méthode abstraite calculerSalaire().

Déclinaison en sous-classes avec règles de rémunération propres :

EmployeHoraire : rémunération au taux horaire multiplié par le nombre d'heures effectuées.

EmployeSalarie : salaire mensuel fixe.

Vendeur : hérite de EmployeSalarie en ajoutant une commission variable au salaire de base.

Centralisation dans la classe Entreprise à l'aide d'un tableau dynamique redimensionné via System.arraycopy.

Parcours polymorphe pour imprimer les bulletins individuels (toString()) et calculer la masse salariale globale (masseSalariale()).






https://github.com/user-attachments/assets/e2bcc0a5-c915-4b4a-8832-7a60a53b0ed6


Exercice 2 — Modélisation d’un Système de Fichiers
Ce qui est fait
Mise en place d'une structure arborescente (motif composite) via la classe abstraite FsItem définissant le contrat getSize().

Deux implémentations concrètes :

FileItem : fichier simple possédant une taille brute en octets.

Directory : dossier contenant une collection extensible d'enfants (FsItem[]), pouvant contenir aussi bien des fichiers que d'autres répertoires.

Calcul récursif de l'espace occupé : la méthode getSize() d'un répertoire additionne automatiquement la taille de tous ses éléments enfants.

Affichage de l'arborescence avec indentation dynamique (list(indent)) selon la profondeur du dossier.

Classe FileSystem servant de gestionnaire racine pour lister l'ensemble des disques et calculer le volume total.





https://github.com/user-attachments/assets/9a7c3ba2-2455-40a2-82a3-34cb27cd27b1



