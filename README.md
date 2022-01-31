# Glossaire-du-php

Strings = collection de txt avec lettres …

Operator=caractère qui performe des tâches dans le code. 

concatenation operator = (.) combine 2 string en une.

Variables = permet de réutiliser des données.

Déclarer variables ($)suivi de (=);

Reassignment= changer la valeur de la variable.

Alias pour la  variable=juste une copie qui utilise  (=&).

The concatenating assignment operator (.=) plus courte notation  pour  réassigner  une  string variable à la valeur courante avec une autre valeur.


Array


Arrays = collections de données qui sont un type de structure de données fondamental dans un ordinateur.

index = location d’un élément.

Les index sont numérotés et commencent par 0..

function: array()= fonction php qui fait des arrays ordonnés.

 e.g. [1,2,3]=Syntaxe plus courte à la fonction.
 
print_r()=print la fonction 

implode() =fonction qui convertit en string.

brackets ([]) = donne accès aux éléments dans les index.

operator (=)= assigne  une valeur avec l’assignement.

array_pop() =fonction rebouge le dernier élément dans  array.

array_push() = fonction ajoute des  éléments à la fin de l’array.

array_shift()= fonction rebouge le 1 élément  de l’ array.

array_unshift()= fonction ajoute  des éléments au début de l’array.

square brackets ([]) =pour accéder aux changements.


Associative array 


Associative arrays= structures de données qui ont des string ou intègrent des clés associés à des valeurs.

=> =opérateur pour associer la clé à la valeur. $my_array = ["panda"=>"very cute"]

To print an array’s keys and their values, we can use the print_r()= print les clés des array avec leurs valeurs.

([ ])= permet d’avoir accès aux valeurs associées aux clés. exemple: $my_array["panda"] retourne  "very cute".

(=): bonne syntaxe  $my_array["dog"] = "good cuteness";

$my_array["dog"] = "max cuteness";= même syntaxe pour changer des éléments existants.

unset() =fonction qui permet de faire re bouger les clés et leurs valeurs.

(+) = union d'opérateurs qui prend 2 opérateurs et les retourne dans un nouvel array.


Loops


while =la boucle exécute aussi longtemps que la condition est vraie( TRUE.).

do…while =la boucle exécute toujours la boucle au moins une fois et continue à exécuter tant qu’elle est vraie.

for =la boucle contient 3 expressions souvent utilisées et exécute à bloc de code un nombre plusieurs fois.

La première expression est exécutée à la première itération (valeur initiale).

La seconde expression permet de continuer la boucle tant que l’expression est vraie.

La 3e expression est évaluée après chaque itération.

foreach =les boucles sont utilisés sont utilisés pour itérer les éléments	dans un tableau. Les clés et les valeurs de chaque élément sont disponibles dans le code. 

break = est utilisé pour arrêter une exécution de boucle plus tôt.

continue = est utilisé pour arrêter une itération de boucle mais continuer les prochaines itérations.

 
Fonction


function= permet de mettre nos instructions dans une fonction et les réutiliser tant qu’on veut.

return = La fonction va retourner un mot clés. si il n’y a pas de mot clés elle va retourner =NULL qui veut dire sans valeur. On peut stocker la valeur de return de la valeur dans une variable.

Paramètre= dans une fonction les paramètres permettent de stocker des variables avec quoi on peut se repérer dans la fonction.

Quand on invoque des fonctions, les valeurs qu’on donne s’appellent des arguments.

L’ordre des arguments décident avec quels paramètres ils sont associés.

On peut rendre un argument optionnel quand le paramètre qui lui correspond à une valeur par défaut. 

(&)=l’argument va passer en préférence si il est avant le paramètre. 

Les variables dans les fonctions ont des objectifs locaux et ne peuvent pas avoir accès en  dehors de la fonction.

global =mot clé qui utilise des variables qui ont des objectifs globaux en dehors des fonctions.

HTML
 
Le back-end a toute la logique et les données dont il a besoin pour maintenir le site web ou l’application.

PHP est un langage de back.

PHP peut être utilisé pour générer des fichiers html.

