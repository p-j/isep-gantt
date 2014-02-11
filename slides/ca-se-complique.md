##  Et si ça se complique ?

Différentes règles applicables en cas de *sous-capacités* :

- priorité à la réalisation des fabrications dont la date de livraison est la plus rapprochée ;
- priorité à la première commande arrivée *(FIFO)*;
- priorité aux fabrications dont la durée totale est la plus courte *(cf PERT)*;
- priorité aux fabrications qui utilisent au moins une ressource critique ;
- priorité aux fabrications qui disposent du minimum de marge globale *(cf PERT)*.

note:
    Le diagramme de Gantt ne résout pas tous les problèmes, en particulier si l'on doit planifier des fabrications qui viennent en concurrence pour l'utilisation de certaines ressources de l'entreprise. Dans ce cas, il est nécessaire de faire appel à des algorithmes plus complexes issus de la recherche opérationnelle et de la théorie de l'ordonnancement. Toutefois, il est souvent possible de trouver des solutions satisfaisantes en appliquant simplement des règles de priorité heuristiques. La méthode consiste à placer les tâches à effectuer dans le diagramme de Gantt dans l'ordre défini par la priorité et en tenant compte des ressources encore disponibles. Les règles les plus courantes sont :
