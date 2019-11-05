# Evaluation par les pairs - Programmation réseau (module RE216)

Voici la procédure à suivre pour la réalisation de l'évaluation par les pairs pour le module RE216. 

## Evaluation par les pairs

Votre projet sera testé et évalué par vos pairs (les T2) pendant la dernière heure de la 4ième et derniere séance de projet en suivant la politique d'évaluation en double aveugle : les identités des auteurs du code ainsi que des évaluateurs ne sont pas révélées. Chaque projet sera anonyme et aléatoirement assigné pour évaluation à un autre groupe de projet anonyme lui aussi.

## Procédure de soumission du travail

Le non respect de la procédure de soumission du travail (arborescence et nommage des fichiers, soumission avant l'heure précisée, etc.) entrainera une pénalité sur la note final du binôme. 


### Format et arborescence des fichiers
Afin de rendre votre travail, vous devrez créer un dossier `jalon_final`et un dossier `jalon_surprise` à la racine de votre répertoire git. Vous devrez déposer dans chacun de ces dossiers **les fichiers executables et compilés sur les machines de l'enseirb** contenant le programme du client qui sera nommé `client` et le programme du serveur qui sera nommé `server`. 

Le repository contiendra à la racine un fichier csv ou pdf détaillant la répartition et la réalisation des taches entre les membres du binome au sein du projet.

- Le dossier `jalon_final`comprendra un fichier `readme.txt` qui indiquera  le dernier jalon réalisé dans son intégralité (jalonX avec X dans {0,1,2,3,4}), ainsi que les requirements faits dans le jalon en cours (s'il y en a un).

- Le dossier `jalon_surprise` comprendra un fichier `readme.txt` donnant les détails des fonctionnalités ajoutées dans le code du client et du server,  ainsi que la façon de les tester.

N'oubliez pas d'ajouter ces fichiers à la liste des fichiers suivis par git avec la commande `git add ./*` lorsque vous êtes à la racine du repository.

N.B.: Dans l'éventualité ou vous auriez un jalon surprise et n'auriez pas anticipé le séparation de votre code en "jalon final" et "jalon surprise", vous devrez alors soumettre un seul et même rendu dans le dossier `jalon_surprise` en précisant le readme du dossier `jalon_final` que le code à éaluer se trouve dans `jalon_surprise`.

## 

### Soumission du code

A l'heure indiquée en début de séance, vous allez devoir faire un ultime commit/push de votre code, suivi d'une ultime release nommée `rendu_final` sur votre répository privé. C'est ce code là qui sera évalué.

## Evaluation en double aveugle

A l'issue de la soumission des travaux, chaque binôme évaluera un autre groupe en remplissant la [feuille d'évaluation](feuille_eval.pdf). L'assignation des travaux à évaluer sera disponible sur cette page web en temps voulu. 

Les feuilles d'évaluation seront ensuite récupérées par l'équipe enseignante à la fin de la séance. 

## Retour sur évaluation 

Chaque binôme aura accès à l'évaluation de son travail par les autres au moyen d'un mail envoyé aux membres du binôme. Si vous constater une erreur dans l'évaluation réalisée, merci de bien vouloir tenir l'équipe enseignante informée. Attention, à ne pas nous solliciter pour des erreurs minimes qui n'auraient pas (ou ridiculement peu) d'impact sur la note finale. 

Pour rappel : 
- Remise en cause (par les enseignants ou le groupe de dev) à raison d'une mauvaise évaluation faite volontairement ou non : -3 points pour l'équipe évaluante;
- Remise en cause (par le groupe de dev malicieusement ou non) à tort d'une bonne évaluation : -3 points pour l'équipe de dev.



## Grille de notation 

Voici le barème indicatif pour la note de réalisation des requirements :

| Note | Réalisation non buggée des requirements du(es) jalon(s) |
| ------ | ------ |
| \[0-5\[ | \[0 - Jalon 1\[ |
| 5 | Jalons 1 |
| \]5-8\[ | Jalon 1 + ]0 - Jalon 2\[ | 
| 8 | Jalon 1 + 2 |
| \]8-14\[  | Jalon 1 + 2 + \]0 - Jalon 3\[ |
| 14  | Jalon 1 + 2 + 3 |
| \]14-18\[ | Jalon 1 + 2 + 3 + \]0 - Jalon 4\[ |
| 18 | Jalon 1 + 2 + 3 + 4 |
| \[18-20\] | Jalon 1 + 2 + 3 + 4 + _Surprise_ |

### Points bonus
- Tout fonctionne en IPv6 et IPV4 : +0.25 point

### Point malus
Des points malus peuvent être appliqués dans les cas suivants:
- Non respect du rendu des jalons aux deadlines indiquées : -2 points;
- Mémoire non libérée : -2 points;
- File descriptors des sockets et des fichiers non fermés : -2 points;

## Assignation

<!-- 
[To be done by group 1](double_blind_eval/eval_g1.tar.gz)

[To be done by group 2](double_blind_eval/eval_g2.tar.gz)

[To be done by group 3](double_blind_eval/eval_g3.tar.gz)

[To be done by group 4](double_blind_eval/eval_g4.tar.gz)

[To be done by group 5](double_blind_eval/eval_g5.tar.gz)

[To be done by group 6](double_blind_eval/eval_g6.tar.gz)

[To be done by group 7](double_blind_eval/eval_g7.tar.gz)

[To be done by group 8](double_blind_eval/eval_g8.tar.gz)

[To be done by group 9](double_blind_eval/eval_g9.tar.gz)

[To be done by group 10](double_blind_eval/eval_g10.tar.gz)

[To be done by group 11](double_blind_eval/eval_g11.tar.gz)

[To be done by group 12](double_blind_eval/eval_g12.tar.gz)

[To be done by group 13](double_blind_eval/eval_g13.tar.gz)

[To be done by group 14](double_blind_eval/eval_g14.tar.gz)

[To be done by group 15](double_blind_eval/eval_g15.tar.gz)

[To be done by group 16](double_blind_eval/eval_g16.tar.gz)

[To be done by group 17](double_blind_eval/eval_g17.tar.gz)

[To be done by group 18](double_blind_eval/eval_g18.tar.gz)

[To be done by group 19](double_blind_eval/eval_g19.tar.gz)

[To be done by group 20](double_blind_eval/eval_g20.tar.gz)

[To be done by group 21](double_blind_eval/eval_g21.tar.gz)

[To be done by group 22](double_blind_eval/eval_g22.tar.gz)

[To be done by group 23](double_blind_eval/eval_g23.tar.gz)

[To be done by group 24](double_blind_eval/eval_g24.tar.gz)

[To be done by group 25](double_blind_eval/eval_g25.tar.gz)

[To be done by group 26](double_blind_eval/eval_g26.tar.gz)

[To be done by group 27](double_blind_eval/eval_g27.tar.gz)

[To be done by group 28](double_blind_eval/eval_g28.tar.gz)

[To be done by group 29](double_blind_eval/eval_g29.tar.gz)

[To be done by group 30](double_blind_eval/eval_g30.tar.gz) -->
