RMenu
=====

Fonctions
---------
.. function:: RMenu.Add(Type, Name, Menu)
|   Permet l'ajout d'un menu dans la ressource.
|   ``Type string`` est une grande catégorie de menu, de préférence, garder toujours le même.                 
|   ``Name string`` est le nom du menu, changer leur à votre guise tout en lui attribuant un nom assez explicite.          
|   ``Menu table`` est le menu que vous voulez ajouté, utilisé la fonction ``RageUI.CreateMenu`` pour en créer un. 
|   **_G** est la valeur de retour, utilisation en inconnus.

_____

.. function:: RMenu:Get(Type, Name) 
|   Permet de récupérer l'objet d'un menu, utilisé comme des variables pour les pointer du doigt dans d'autre fonction (``RageUI.IsVisible`` par exemple)
|   ``Type string`` est une grande catégorie de menu, de préférence, garder toujours le même.                 
|   ``Name string`` est le nom du menu, changer leur à votre guise tout en lui attribuant un nom assez explicite.   

_____

.. function::   RMenu:Settings(Type, Name, Settings, Value) 
| Permet de récupérer l'objet d'un menu, utilisé comme des variables pour les pointer du doigt dans d'autre fonction (``RageUI.IsVisible`` par exemple)
| ``Type string`` est une grande catégorie de menu, de préférence, garder toujours le même.   
| ``Name string`` est le nom du menu, changer leur à votre guise tout en lui attribuant un nom assez explicite.   
| ``Settings string`` est encore un paramètre plus ou moins inconnus, encore en étude, mais potentiellement utilisé dans un table permettant de définir des variables intégré à la table/objet Menu, dans le même style que les RightLabel pour les boutons. 
| ``Value any optional`` est un pramètre universel permettant l'intégration de n'importe quel valeur. En étude encore.  

_____

.. function::   RMenu:DeleteType(Type) 
| Permet la supression d'un type de menu dans la ressource. Aucun utilité pour le moment.
| ``Type string`` est une grande catégorie de menu, de préférence, garder toujours le même.   

_____

.. function::   RMenu:Delete(Type, Name) 
| Permet la supression d'un menu dans la ressource.
| ``Type string`` est une grande catégorie de menu, de préférence, garder toujours le même.                 
| ``Name string`` est le nom du menu, changer leur à votre guise tout en lui attribuant un nom assez explicite.          

_____

.. function::   RMenu:DeleteType(Type) 
| Permet la supression d'un type de menu dans la ressource. Aucun utilité pour le moment.
| ``Type string`` est une grande catégorie de menu, de préférence, garder toujours le même.                 


