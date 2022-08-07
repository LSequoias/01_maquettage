# Les Users Stories
*A defaut d'avoir une équipe de dev, les users stories peuvent être remplacer par les diagrammes de cas d'utilisation propre à l'UML si le développeur est tous seul.*

## Leurs usages
Les users stories permette de comprendre se que veulent les clients ou les utilisateur d'un produits.

Une stories n'est utile que si plusieurs personnes peuvent débatte à sa viabilitée, pour réalisée une carte user storie on peu partir de plusieurs Personna, les Personna décrive un ensemble de personne qu'une application pourrait interressez comme telle, partons du principe que l'on dois réaliser un site de cocktail nommée Kokomo.

>**Nom** : Bob   
**Spécialitée** : Etudiant   
**Age** : 21 
>>**Recherche** : Boire un verre entre ami(e)s de tant à autre. Sans pour autant se ruinée et dans un endroit convivial.
>
>**Plateform** : Phone
>

Pour ce Personna nous avons un potentiel un client. Bien sûr le Personna se doit être objectif et non incohérent. Bob est étudiant et a 21 ans ont sait déja qu'il est majeur et donc potentiellement interresser aux boissons avec Alcool. Il cherche un endroit convivial où boire un verre entre pote, la première feature qui nous vient en tête c'est la map avec la position de l'enseigne, on as déja une feature à mettre de cotée : une geomap de l'endroit de l'enseigne donc.  
Comme info aussi ont sait que Bob se sert de son Phone pour trouver se dont il veux, il n'as pas mentionnée un ordinateur portable. Ont sait donc que l'application devrat être responsive pour répondre aux besoins des client comme Bob.

>**Nom** : Alice  
**Spécialitée** : Infirmière  
**Age** : 33  
>>**recherche** : Un bar entre copine, rien de plus. Ah si pas mal famé sa serait bien.
>
>**Platform** : Phone - Ordinateur portable

Pour ce Personna nous avons Alice qui comme Bob cherche un endroit où boire un verre, comme platforme elle utilise le portable et son ordinateur portable. Sa recherche n'impacte pas automatiquement l'équipe de dev, ce n'est pas au dev qu'encombre le devoir de rendre le bar sécurisée ou non, en revanche ont peu rendre le site un plus accueillant de notre cotée.   


## La différence entre Personna et une Users Stories
Globalement le Personna est un indice de se que l'ont attend d'un client, les users stories cible directement les besoins de l'application en elle même. Les Personna donne une idée du client type.

## Des Users Stories
> Bob   
> Si le site montre sa localisation se serais un gros plus.  
> Un large choix des bières traditionnelles et cocktail.
> Que les prix sont affichez.

> Alice  
> Un site beau, que sa donne envie.  
> Qu'il soit rapide et simple

## Qu'en tirée de ces Personna et de ces Users Stories
> geomap : feature  
> site rapide : Demande d'autres sous-taches.    
> peu de navigation, une sidebar pour les produits pour accélérée la recherche rapide.   
> Un travail sur UI en ce basant sur la loi de Jakob par exemple.

_____

## Synopsis
Comme projet j'ai à réaliser un site web type vitrine, ce site à pour objectif de faire découvrir une liste de cocktail à un large public. Ce site doit être attractif pour pouvoir rivaliser avec les autres enseignes environnante, on pars d'une mise en valeur d'une enseigne émergente qui as choisie le marketing digital pour promouvoir son action dans la régions d'Amiens. Temporairement l'enseigne se nomme **Kokomo**, temporairement car ce nom de domaine est déja pris, pour la suite ce nom suffiras à élaborée le projet.

## Méthode MosCow
*En UML l'équivalent est la grille de risque, c'est une grille qui as pour vocation d'identifier les features et de les classées par importances avant la mise en production. Dans le cas où une équipe est constituées d'un product owner et que les stories ont étais déposée cette grille se remplace par une méthodologie nommée MosCow *

- M - Must have this
- Les O sert pour donnée du sens à l'acronyme (lol)
- S - Should have this if at all possible
- C - Could have this if it does not affect anything else
- voir ligne deux
- W - Won't have this time but would like in the future

### Must have this :
Ce sont les Features essentiel qui compose le site web, impossible de passer **Kokomo** en production sans ça.

### Should have this if at all possible
Ce sont les Features qui impacte énormément le site web mais ne sont pas essentiel à son bon fonctionnement ou son objectif central.

### Could have this if it does not affect anything else
Ce sont des petites Features pour mettre en valeurs le site, généralement en sont plus en question de confort que de fonctionnalitée. 

### Won't have this time but would like in the future
Ces features reste à cotée du projet et seront traitée plus tard.


## Exemple d'employment de la méthode MosCow

### Must have
1. la page de produits (temporairement la page principale).
2. Les détails de chaque produit.
3. le pieds de page contenant les CGU.
4. La sideBar pour naviguée à travers tout les produits.
5. La page de gestion des produits, un simple crud pour commençais.

### Should have this if at all possible
1. l"application de géocalisation pour afficher l'emplacement de l'enseigne.
2. Application d'Ajax sur la Sidebar afin d'éviter les rechargement de la page produit.
3. Appliquée le site en responsive pour les formats mobiles.
4. Ajout de la page accueil.
5. Faire le référencement.

### Could have this if it does not affect anything else
1. Afinnée les filtres de recherches.
2. Ajout des prix des produits dans les détails.
3. Une page de Contacte - SAV
4. Mise en place d'un système SMTP.
5. Application de WAI Aria.

### Won't have this time but would like in the future
1. Une page destinée à visualisée l'équipe de l'enseigne
2. Ajout d'animation et de Transition.
3. Gérée les bug post-production. 
4. Un suivit des clicks client, un CRM en gros.
5. Téléchargement des statistiques générée par les clicks des clients.
6. Refactorisation du code.
7. CSR ou SSR voir un serveur hybride selon la tech.


Voila les tâches définits par ordre de prioritée. Bien sûr ces tâches se veulent être exaussif et sans doute plus tard de nouvelle apparaitrons. Pour élaborée ces tâches en équipe des outils telle que Jira existe.