***********************************************************************
*                       TYPSoft FTP Serveur 1.10                      *
***********************************************************************

TYPSoft FTP Serveur est un ftp serveur rapide et facile avec le support
des commandes Standard de FTP, Interface propre et claire, architecture
de système de fichiers virtuelle, capacité de reprendre le 
téléchargement interrompu tant qu’en download qu'en upload,
Restriction IP, Message de Bienvenue et de Départ, Log de connexion, 
Multi langue et beaucoup d'autres choses.


Innovations
-----------

1.10
- Cette version contient tout ce que la 1.09 devrait avoir sauf que
  j'avais pas inclus le bon exe dans le fichier d'installation :(
  C'est ce qui arrive quand on travail avec plusieurs versions différentes
  du même produit...

1.09
- Les usagers doivent maintenant avoir le droit d'Effacer les fichiers
  pour pouvoir les écraser sur le Upload.
- Liste des IP enlevés de dans Usager Info. Trop de confusion pour les
  usager sans expérience.
- Ajout d'une option pour spécifier le IP pour le mode PASV.
- Correction d'un bug avec l'Affichage en mode Virtuel quand les
  répertoires on des espaces dans leur nom.
- Autres bugs mineur corrigé et quelques optimisations.

1.08
- Correction d'un bug connu depuis longtemps quand on passait le
  paramètre -n au client FTP de *NIX en ligne de commande.

1.07
- Correction d'un bug introduit dans la version précédente. Tous les 
  fichiers uploader allaient dans le Répertoire Maison.

1.06
- Correction d'un bug avec la création de répertoire avec le système
  de lien virtuel.

1.05
- Correction d'un bug sur la commande CWD introduite dans la version
  précédente.

1.04
- Correction d'un bug de sécurité. Quand un usager a des droits en
  upload et n'a pas Sous Répertoire Inclus, l'usager peut écrire sur
  n'importe quel fichier du système. Merci a Egor Chusov pour ce bug.
- Ajout d'une option pour sélectionner les ports que l'option PASV
  peut utiliser. Maintenant si vous avez un routeur/firewall, vous
  pouvez seulement rediriger les ports que vous avez sélectionné et
  non tout les ports de 1024 à 65535.

1.03
- Arrgg. Une option du compilateur que j'avais activée pour debuger une
  fonction qui fesait en sorte que ça me sortait la moindre petite
  erreur même ceux que je disais de passer par dessus :/

1.02
- Correction d'un bug introduit dans la version 1,01. Personnes ne pouvait 
  aller dans un lien virtuel après que la correction du bug pour ".." 
  dans le nom de fichier et répertoire.

1.01
- Correction d'un problème quand on sélectionnait un usager après 
  avoir trié la liste par ID. Ça ne sélectionnait pas le bon.
- Quelques réponses de chemin on été converti au style Unix
  (conversion de "\" à "/")
- Correction d'un bug avec certain répertoire qui était pas cacher 
  quand Sous Répertoire Inclus était décoché.
- Correction d'un bug quand Lien Virtuel était cocher et qu'il n'y 
  avait pas de nom. Ceci donnait une erreur de type "Out of List Bound"
- Correction d'un bug avec la commande "LS". Les liens virtuels
  n'étaient pas affichés.
- Correction d'un bug avec les Répertoires et les Fichiers qui 
  avait ".." dans le nom.

1.00    
- Première version finale. Retrait du statut de Bêta.


***********************************************************************

TYPSoft
L'innovation est notre domaine...

Page Web: http://www.typsoft.com
E-Mail:   webmaster@typsoft.com

***********************************************************************