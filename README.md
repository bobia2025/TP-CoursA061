# TP-CoursA061
TP déploiement application IA V2

<b>1 . Objectif du TP</b>
<Br/>
Composee de 14 etapes dont 12 obligatoires, ce TP etait pour nous l'occasion d'appliquer et d'utiliser differents outils comme git, github, tox, pytes et flask, pour ne citees que ceux la.
Chaque etapes nous rapporcher progressivement de la mise en place d'un pipeline avec des tests automatisees dans un enviromment MLOps.
Il a fallu adapter chaque etape pour pouvoir lancer et valider les tests avant de passer a l'etapes suivantes.
Et ceci n'etait pas sans contraintes, avec en chemin, plusieurs problemes, souvent lies a notre environnement en local ou aux version des librairairies utilisees.
je precise que je travaille dans un envoronnement macOs. Cela m'a value plus de probleme.

<b>2 . Problemes rencontresP</b>
Partie 1 et 2: Les problemes que j'ai eu a rencontre en premier est la version des librairies, que ca soit pout numpy, pandas scikit-learn, j'ai du installe les dernieres version de chaque pour pouvoir avancer.
Au lieu d'utiliser le fichier requiements, j'ai du installe un a un chaque librairie dans  mon environnement virtuelle.
![image](https://github.com/user-attachments/assets/61302cdc-e0c0-4af4-813d-e3ce536fdeb9)


Partie 3 a 12: J'ai eu aussi plusieurs probleme a execute tox a toutes les etapes. Il fallut que je commente le fichier tox.ini a toute les reprise pour pouvoir passer la premieres etapes.
![image](https://github.com/user-attachments/assets/0a3bd8a2-3023-4a0d-93a8-40824b55a80c)
En tapant la commande pip freeze, je voyais bien que le module de numpy etait present. Mais je n'arrivais pas a valider.
j'ai force et refaire les tests a chaque etape, mais sans succes.

<b>3 . Conclusion</b>
L'ajout des differentes parties , etapes par etapes m'as permis quand de comprendre l'evolution du code progressivement, de l'initialisation  jusqu'a la validation.
je compte ajouter aussi pour la suite les etapes 13 et 14 qui concerne le cercleCi et Gemfry.
Mais, j'aimerais prendre plus de temps pour adapter la solution a mon environnement pour pouvoir effectuer les tests passant pour chate etapes.

