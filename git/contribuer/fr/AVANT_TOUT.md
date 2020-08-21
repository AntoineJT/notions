# Avant de contribuer

Avant de contribuer à un projet open source, il faut prendre connaissances de certaines informations.

## 1. Lire le README

Ceci est la toute première chose à faire : lire attentivement le fichier lisez-moi. Il s'agit généralement d'un fichier markdown (dont l'extension est *.md*) ou d'un fichier texte (*.txt*). Il peut également s'agir de tout autre format disposant d'une prévisualisation GitHub, ou non : il peut, par exemple, s'appeller tout simplement *README* sans extension de fichier. La plupart du temps, il est affiché juste en dessous de l'arborescence du projet (prévisualition).

Ce fichier est, comme son nom l'indique, destiné à fournir des informations cruciales sur le projet, telle que son nom, sa finalité, le lien du site web officiel, ou encore, potentiellement, comment y contribuer.

## 2. Prendre connaissance de la licence du projet

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

## 3. Parcourir les issues

Les *issues* sont des discussions permettant de signaler des bugs, de proposer des modifications telles que de nouvelles fonctionnalités, des améliorations du code source, etc.
Elles peuvent également servir à obtenir du support, ce qui ne nous intéresse pas spécialement ici.

Utilisez la fonctionnalité de recherche pour chercher si une *issue* portant sur ce que vous souhaitez ajouter ou corriger a déjà été ouverte.

**Cherchez également dans les *issues* fermées**. Enlevez le filtre "is:open" pour rechercher également dans les *issues* fermées.

![Rechercher dans les issues](.images/chercher_issues.png)

Malgré ces recherches, il se pourrait que vous n'ayiez pas utilisé les bons mots-clés ou que l'auteur de l'*issue* n'ait pas utilisé des mots-clés significatifs. Dans ce cas, il se pourrait qu'un *maintainer* marque votre *issue* comme dupliquée (par défaut l'étiquette (le *label*) *duplicated*). N'oubliez pas de parcourir les *pull requests* de la même manière afin de réduire ce risque également.

## 4. Parcourir les pull requests

Une *pull request* sert à proposer des modifications ayant été effectuées sur notre *fork*. Un *fork* est une copie d'un projet, sur un compte utilisateur ou une organisation GitHub par exemple, pour lequel le compte sur lequel il est situé a la permission de faire des modifications. Concrètement, il s'agit d'une copie avec droit d'écriture : vous pouvez donc *commit* et *push* sur votre *fork*.

D'exactement la même manière que pour les *issues*, vous devez chercher dans les *pull requests* ouvertes **mais également celles fermées**, afin d'être certain de ne pas passer à côté d'informations utiles, pouvant vous indiquer notamment que le *maintainer* n'est pas intéressé par une telle fonctionnalité, ou encore voir les remarques qu'il a fait à quelqu'un ayant fait une contribution assez similaire. 

Ne vous y attardez pas trop longtemps néanmoins, il ne s'agit pas de lire le contenu de toutes les *pull requests*, en particulier s'il y en a beaucoup.

![Rechercher dans les pull requests](.images/chercher_pr.png)

Tout comme pour les *issues*, n'oubliez pas de supprimer le filtre "is:open" afin de chercher dans les *pull requests* fermées également.

## 5. Lire le code de conduite

Ce fichier est appelé *CODE_OF_CONDUCT* et tout comme la licence et le fichier lisez-moi, il s'agit généralement d'un fichier markdown ou d'un fichier texte avec ou sans extension de nom de fichier.

Il donne des indications sur les bonnes attitudes à avoir, le langage à adopter lorsqu'on participe au projet de quelque sorte que ce soit, etc.

**Il convient donc de lire ce fichier lorsqu'on ouvre ou commente une *issue* ou une *pull request* notamment**.

**S'il n'y a pas de code de conduite, remettez vous-en à votre bon sens**. Si, par exemple, vous êtes particulièrement agressif ou que vous vous amusez à troller dans les *issues*, ne vous étonnez pas si vous vous faites bannir du projet en question.

## 6. Lire les règles de contribution

Les règles de contribution sont mises à disposition dans un fichier nommé *CONTRIBUTING*, le plus généralement un fichier markdown ou texte, tout comme pour le lisez-moi, la licence et le code de conduite.

S'il n'y en a pas, regardez dans les *commits* et dans les *pull requests* fermées et acceptées. Essayez de vous en inspirer pour votre future contribution.

**Dans tous les cas, respectez le *code style* en application**. 
