# Avant de contribuer

Avant de contribuer à un projet open source, il faut prendre connaissance de certaines informations.

## 1. Lire le README

Ceci est la toute première chose à faire : lire attentivement le fichier lisez-moi. Il s'agit généralement d'un fichier markdown (dont l'extension est *.md*) ou d'un fichier texte (*.txt*). Il peut également s'agir de tout autre format disposant d'un rendu HTML sur GitHub, ou non : il peut, par exemple, s'appeller tout simplement *README* sans extension de fichier. La plupart du temps, il est affiché juste en dessous de l'arborescence du projet.

Ce fichier est, comme son nom l'indique, destiné à fournir des informations cruciales sur le projet, telle que son nom, sa finalité, le lien du site web officiel, ou encore, potentiellement, comment y contribuer.

Vous êtes censé l'avoir déjà lu, ne serait-ce qu'en diagonale, afin d'être certain que ce projet réponde à vos besoins.

## 2. Vérifiez que vous avez réellement besoin de contribuer

**Même si vous êtes pressé par le temps, il vaut mieux vous renseigner sur le projet en lisant la documentation**. Il est plus rapide de lire la documentation que de contribuer à un projet.

**S'il n'y a pas de documentation, n'hésitez pas à lire le code à la recherche de réponses, ou à ouvrir une *issue* pour poser votre question**. Plus le projet est petit, plus il y aura de chances pour qu'il soit plus rapide de lire le code que d'attendre une réponse à votre *issue*. Plus le projet est grand, plus il y aura de chances qu'une documentation existe.

Si vous souhaitez contribuer pour améliorer le projet, et non par besoin (professionnel par exemple), cela est très bien également. Dans ce cas, vous n'êtes a priori pas pressé par le temps.

## 3. Assurez-vous que le projet est toujours maintenu

Si vous désirez modifier le projet de votre côté uniquement, vous n'avez pas besoin de vous intéresser à cette étape, cependant, étant donné que ce cours porte sur le fait de contribuer à un projet existant, maintenu par d'autres personnes, cela n'est certainement pas votre cas.

Vérifiez que ce projet n'a pas été abandonné par son *maintainer*. S'il est archivé, vous aurez la réponse tout de suite : il a été abandonné. Cela peut être pour diverses raisons : le projet était obsolète, il a été remplacé, le *maintainer* n'a plus le temps de s'y consacrer et personne pour reprendre le projet, etc.

Afin de le vérifier, vous pouvez déjà observer la date de dernier *commit*.

![Date dernier commit](.images/date_dernier_commit.png)

Vous pouvez également observer les informations présentes dans l'onglet *Insights*.
Vous pouvez alors regarder notamment la fréquence de commit.

![Fréquence de commit](.images/frequence_commit.png)

Vous pouvez également regarder la fréquence d'ajout/suppression de lignes. Cela est néanmoins moins indicatif de la vitalité du projet, plutôt que représentatif de l'implication du *maintainer* et de la communauté autour du projet.

![Fréquence de code](.images/frequence_code.png)

Si c'est le cas, et que vous avez néanmoins besoin de modifier ce projet, vous pouvez toujours en faire un *fork*, et le modifier de votre côté, sans proposer les modifications au dépôt original. Concrètement, vous ne ferez pas de *pull request* (explications plus loin) vers l'*upstream* (le dépôt dont vous avez fait un *fork*).

## 4. Prendre connaissance de la licence du projet

Ce fichier est généralement appelé *LICENSE*, et comme le fichier lisez-moi, il s'agit généralement d'un fichier markdown ou d'un fichier texte, avec ou sans extension.
Le plus souvent, il s'appelle tout simplement *LICENSE* sans extension de fichier.

**S'il n'y a pas de licence, il vaut mieux ne pas contribuer**.
En France, quand un projet n'est pas sous licence, le droit d'auteur s'applique. Vous n'avez donc légalement pas le droit de modifier le code mis à disposition.

Pour connaître les modalités abrégées des licences les plus communes, vous pouvez vous référer à [ce site](https://choosealicense.com/licenses/).

Pour des licences moins connues, vous devrez les lire ou vous renseigner sur Internet (voire contacter un juriste si le texte de la licence est complexe et que vous souhaitez être certain, bien que cela serait certainement disproportionné).

Sur GitHub, si un projet utilise une des licences les plus communes, alors son nom sera indiqué à côté du langage majoritaire.

![Licence preview 1](.images/licence_usuelle_preview1.png)

De même, sur la page du projet, une telle licence verra son nom indiqué dans la section *About* à droite de l'arborescence des fichiers.

![Licence preview 2](.images/licence_usuelle_preview2.png)

## 5. Parcourir les issues

Les *issues* sont des discussions permettant de signaler des bugs, de proposer des modifications telles que de nouvelles fonctionnalités, des améliorations du code source, etc.
Elles peuvent également servir à obtenir du support, ce qui ne nous intéresse pas spécialement ici.

Utilisez la fonctionnalité de recherche pour chercher si une *issue* portant sur ce que vous souhaitez ajouter ou corriger a déjà été ouverte.

**Cherchez également dans les *issues* fermées**. Enlevez le filtre "is:open" pour rechercher également dans les *issues* fermées.

![Rechercher dans les issues](.images/chercher_issues.png)

Malgré ces recherches, il se pourrait que vous n'ayiez pas utilisé les bons mots-clés ou que l'auteur de l'*issue* n'ait pas utilisé des mots-clés significatifs. Dans ce cas, il se pourrait qu'un *maintainer* marque votre *issue* comme dupliquée (par défaut l'étiquette (le *label*) *duplicated*). N'oubliez pas de parcourir les *pull requests* de la même manière afin de réduire ce risque également.

## 6. Parcourir les pull requests

Une *pull request* sert à proposer des modifications ayant été effectuées sur notre *fork*. Un *fork* est une copie d'un projet, sur un compte utilisateur ou une organisation GitHub par exemple, pour lequel le compte sur lequel il est situé a la permission de faire des modifications. Concrètement, il s'agit d'une copie avec droit d'écriture : vous pouvez donc *commit* et *push* sur votre *fork*.

D'exactement la même manière que pour les *issues*, vous devez chercher dans les *pull requests* ouvertes **mais également celles fermées**, afin d'être certain de ne pas passer à côté d'informations utiles, pouvant vous indiquer notamment que le *maintainer* n'est pas intéressé par une telle fonctionnalité, ou encore voir les remarques qu'il a fait à quelqu'un ayant fait une contribution assez similaire. 

Ne vous y attardez pas trop longtemps néanmoins, il ne s'agit pas de lire le contenu de toutes les *pull requests*, en particulier s'il y en a beaucoup.

![Rechercher dans les pull requests](.images/chercher_pr.png)

Tout comme pour les *issues*, n'oubliez pas de supprimer le filtre "is:open" afin de chercher dans les *pull requests* fermées également.

## 7. Lire le code de conduite

Ce fichier est appelé *CODE_OF_CONDUCT* et tout comme la licence et le fichier lisez-moi, il s'agit généralement d'un fichier markdown ou d'un fichier texte avec ou sans extension de nom de fichier.

Il donne des indications sur les bonnes attitudes à avoir, le langage à adopter lorsqu'on participe au projet de quelque sorte que ce soit, etc.

**Il convient donc de lire ce fichier lorsqu'on ouvre ou commente une *issue* ou une *pull request* notamment**.

**S'il n'y a pas de code de conduite, remettez vous-en à votre bon sens**. Si, par exemple, vous êtes particulièrement agressif ou que vous vous amusez à troller dans les *issues*, ne vous étonnez pas si vous vous faites bannir du projet en question.

## 8. Lire les règles de contribution

Les règles de contribution sont mises à disposition dans un fichier nommé *CONTRIBUTING*, le plus généralement un fichier markdown ou texte, tout comme pour le lisez-moi, la licence et le code de conduite.

**S'il n'y en a pas, regardez dans les *commits* et dans les *pull requests* fermées et acceptées**. Essayez de vous en inspirer pour votre future contribution. Ne vous y attardez pas trop non plus : s'il n'y a pas de règles de contribution c'est qu'il s'agit d'un projet avec

**Dans tous les cas, respectez le *code style* en application**. Ne vous avisez pas de toucher à du code que vous n'avez pas écrit pour modifier le *naming* des variables ou des fonctions par exemple. Tentez de respecter un maximum le *code style* en application dans le code que vous écrivez. Ce n'est pas à vous d'imposer votre *code style* au projet auquel vous contribuez : c'est ce dernier qui vous impose le sien.  <!-- TODO Mettre ça dans le chapitre où on attaque réellement les contributions : je ne pense pas que ce soit adapté de parler de code style ici. Du moins, il convient de le mettre dans le chapitre suivant également -->
