![alt text](./images/vuelogo.png)

### Historique

VueJS s'inscrit dans l'ère du SPA, pour **_Single Page Application_**, qui s'étend de 2010 à nos jours et offre la possibilité de créer des composants réutilisables au sein même de l'application ou dans d'autres !
Ils permettent de créer une hiérarchisation via des relations parents / enfants

Les composants peuvent être réutilisés autant de fois que souhaité dans une balise dite "racine":

```<
div id="components-demo">
  <button-counter></button-counter>
  <button-counter></button-counter>
  <button-counter></button-counter>
</div>
```

Source: [Doc officielle VueJS](https://fr.vuejs.org/v2/guide/components.html)

La hiérarchisation fonctionne comme ceci: Les composants sont crées de manière isolée, sur leur propre fichier, qui ne contiendra que leur contenu, l'exportation et l'importation (nous l'aboderons par la suite). Pour les afficher où l'on souhaite qu'ils soient, il suffira d'intégrer leur balise dans la balise **racine**

Le positionnement de ce composant "invoqué" sera en dessous du composant invoqué au dessus, et au dessus du composant invoqué en dessous par défaut
