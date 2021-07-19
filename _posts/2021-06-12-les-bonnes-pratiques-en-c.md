---
layout: post
title: Les bonnes pratiques en C
subtitle: Quelques bonnes pratiques pour coder proprement !
cover-img: /assets/img/path.jpg
share-img: /assets/img/path.jpg
tags: [c, developpement, bonnespratiques, autres]
---

Si un bon programme est défini comme étant un programme qui donne le résultat attendu, il existe tout de même des bonnes pratiques à adpoter. Voici quelques unes qui rendront vos programmes plus propres et plus faciles à maintenir.

### 1. Indenter le code
Un bon code c'est aussi un code lisible. En effet, un code écrit en bloc est difficile à lire et il est impossible de distinguer les différents blocs. Même si vous en êtes l'auteur, vous aurez du mal à vous retrouver. Prenez l'habitude d'indenter votre code pour une meilleure lisibilté.

### 2. Commenter
Parce que d'autres personnes sont amenés à consulter votre code ou  à travailler dessus, il est important de le documenter pour expliquer vos choiix et les actions qui sont faites. Rajouter des commentaires d'abord pour que vous-même vous vous retrouez des années plus tard et pour que d'autres personnes puissent faire évoluer votre code.

### 3. Éviter le plus possible les variables gbobales
Lorsque l'on souhaite qu'une varaibale soit accessible partout dans le code, on la déclare après les bibliothèques, elle est alors une variable globale. Les pointeurs sont un bon moyen d'accéder à des variables sans qu'elles ne soient globales.

### 4. Découper en utilisant les fonctions
En informatique, on déteste la redondance, il est vivement déconseillé de dupliquer des instructions dans votre code. Les boucles permettent de faire.
Là encore il y a une contrainte, cela marche quand les intructions se répètent l'une après l'autre. 

### 5. Toujours contrôler les entrées au clavier
Retenez ceci: «Il ne faut jamais faire confiance à l'utilisateur». En effet, votre ne fonctionnera pas correctement pour certiaines valeurs, à vous de vous assurer que les utilisateurs ne peuvent as saisir n'importe quoi. C'est une règle importante des systèmes d'informations

---
*Ces bonnes pratiques valent également pour les autres langages de programmation. Cette liste n'est pas exhaustive, n'hésitez pas à m'envoyer vos bonnes pratiques, je serai ravi de les ajouter.*
