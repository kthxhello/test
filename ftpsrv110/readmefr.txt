***********************************************************************
*                       TYPSoft FTP Serveur 1.10                      *
***********************************************************************

TYPSoft FTP Serveur est un ftp serveur rapide et facile avec le support
des commandes Standard de FTP, Interface propre et claire, architecture
de syst�me de fichiers virtuelle, capacit� de reprendre le 
t�l�chargement interrompu tant qu�en download qu'en upload,
Restriction IP, Message de Bienvenue et de D�part, Log de connexion, 
Multi langue et beaucoup d'autres choses.


Innovations
-----------

1.10
- Cette version contient tout ce que la 1.09 devrait avoir sauf que
  j'avais pas inclus le bon exe dans le fichier d'installation :(
  C'est ce qui arrive quand on travail avec plusieurs versions diff�rentes
  du m�me produit...

1.09
- Les usagers doivent maintenant avoir le droit d'Effacer les fichiers
  pour pouvoir les �craser sur le Upload.
- Liste des IP enlev�s de dans Usager Info. Trop de confusion pour les
  usager sans exp�rience.
- Ajout d'une option pour sp�cifier le IP pour le mode PASV.
- Correction d'un bug avec l'Affichage en mode Virtuel quand les
  r�pertoires on des espaces dans leur nom.
- Autres bugs mineur corrig� et quelques optimisations.

1.08
- Correction d'un bug connu depuis longtemps quand on passait le
  param�tre -n au client FTP de *NIX en ligne de commande.

1.07
- Correction d'un bug introduit dans la version pr�c�dente. Tous les 
  fichiers uploader allaient dans le R�pertoire Maison.

1.06
- Correction d'un bug avec la cr�ation de r�pertoire avec le syst�me
  de lien virtuel.

1.05
- Correction d'un bug sur la commande CWD introduite dans la version
  pr�c�dente.

1.04
- Correction d'un bug de s�curit�. Quand un usager a des droits en
  upload et n'a pas Sous R�pertoire Inclus, l'usager peut �crire sur
  n'importe quel fichier du syst�me. Merci a Egor Chusov pour ce bug.
- Ajout d'une option pour s�lectionner les ports que l'option PASV
  peut utiliser. Maintenant si vous avez un routeur/firewall, vous
  pouvez seulement rediriger les ports que vous avez s�lectionn� et
  non tout les ports de 1024 � 65535.

1.03
- Arrgg. Une option du compilateur que j'avais activ�e pour debuger une
  fonction qui fesait en sorte que �a me sortait la moindre petite
  erreur m�me ceux que je disais de passer par dessus :/

1.02
- Correction d'un bug introduit dans la version 1,01. Personnes ne pouvait 
  aller dans un lien virtuel apr�s que la correction du bug pour ".." 
  dans le nom de fichier et r�pertoire.

1.01
- Correction d'un probl�me quand on s�lectionnait un usager apr�s 
  avoir tri� la liste par ID. �a ne s�lectionnait pas le bon.
- Quelques r�ponses de chemin on �t� converti au style Unix
  (conversion de "\" � "/")
- Correction d'un bug avec certain r�pertoire qui �tait pas cacher 
  quand Sous R�pertoire Inclus �tait d�coch�.
- Correction d'un bug quand Lien Virtuel �tait cocher et qu'il n'y 
  avait pas de nom. Ceci donnait une erreur de type "Out of List Bound"
- Correction d'un bug avec la commande "LS". Les liens virtuels
  n'�taient pas affich�s.
- Correction d'un bug avec les R�pertoires et les Fichiers qui 
  avait ".." dans le nom.

1.00    
- Premi�re version finale. Retrait du statut de B�ta.


***********************************************************************

TYPSoft
L'innovation est notre domaine...

Page Web: http://www.typsoft.com
E-Mail:   webmaster@typsoft.com

***********************************************************************