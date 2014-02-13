# Gantt
*Présentation pour l'APP ISEP 2014*

Sources:
- [Gantt chart - Wikipedia [en]](http://en.wikipedia.org/wiki/Gantt_chart)
- [Diagramme de Gantt - Wikipedia [fr]](http://fr.wikipedia.org/wiki/Diagramme_de_Gantt)
- [Gantt Charts - Planning and Scheduling Team Projects [en]](http://www.mindtools.com/pages/article/newPPM_03.htm)
- [How to make a simple Gantt chart [en]](http://theresearchwhisperer.wordpress.com/2011/09/13/gantt-chart/)

Réalisé avec [reveal.js](https://github.com/hakimel/reveal.js) et [generator-reveal](https://github.com/slara/generator-reveal)

---

## Comment visualiser la présentation ?
+ Solution simple : [http://p-j.github.io/isep-gantt/](http://p-j.github.io/isep-gantt/)
  + Une fois sur la page, appuyé sur `S` pour voir les notes du présentateur
   + `N` pour passer au slide suivant
   + `P` pour revenir au précédent.
   + Les fleches directionnelles peuvent également être utilisées, mais n'oubliez pas les slides verticaux !
+ Juste les sources (avec les notes du présentateur) : [sources](https://github.com/p-j/isep-gantt/tree/master/slides)
+ Cloner et regarder :
  + `$ cd /chemin/vers/votre/dossier/www`
  + `$ git clone git@github.com:p-j/isep-gantt.git` (clone le dépôt de la présentation)
  + Naviguez vers [http://127.0.0.1/isep-gantt/](http://127.0.0.1/isep-gantt/)
+ Pour les curieux, la présentation peut être modifiée et réutilisée à l'aide des outils suivant :
  + [node](http://nodejs.org/)
  + [grunt](http://gruntjs.com/getting-started#installing-the-cli)
+ Une fois ces outils installés, la procédure suivante permet d'accéder à la présentation :
  + `$ git clone git@github.com:p-j/isep-gantt.git` (clone le dépôt de la présentation)
  + `$ cd isep-gantt` (aller dans le dossier que l'on vient de créer)
  + `$ npm install` (installer les dépendances)
  + `$ grunt` (assembler les fichiers et lancer le server local pour afficher la présentation)
  + Puis naviguez vers [http://localhost:9000](http://localhost:9000) pour voir la présentation

D'avantage d'information sur comment utiliser [reveal.js](https://github.com/hakimel/reveal.js) sont disponibles sur le dépôt officiel [hakimel/reveal.js](https://github.com/hakimel/reveal.js) (en anglais).

## License
MIT licensed

Copyright (C) 2014 Jérémie Parker, http://jeremie-parker.com
