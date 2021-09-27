---
layout: post
title: Écrivez votre premier programme C
subtitle: Démmarez la programmation avec le langage C
cover-img: /assets/img/path.jpg
thumbnail-img: /assets/img/thumb.png
share-img: /assets/img/path.jpg
tags: [c]
---

Maintenant que nous avons installé un IDE, nous allons écrire notre permier programme. Il s'agit d'un programme classique, nous allons afficher le fameux message «Hello world !» à l'écran. Oui juste ça.

La première chose à faire, c'est ouvrir votre éditeur de texte. Ensuite, créez un fichier au nom de `hello.c`.

Un programme C commence généralement sinon toutjours par l'instruction `#include<stdio.h>`. Cette instruction indique qu'il faut importer la bibliothèque `stdio.h`.

```c
#include<stdio.h>

int main()
{
	printf("Hello world !\n");

	return 0;
}
```
Faites `CTRL S` pour enregistrer le fihier, ensuite compilez et exécutez.

```bash
# Compilation
gcc -o hello.o hello.c
# Exécution
./hello.o
```