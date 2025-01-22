### focus vs focus-visible

En CSS, `button:focus` et `button:focus-visible` sont deux sélecteurs qui permettent de styliser un bouton lorsqu'il est en "focus", c'est-à-dire lorsqu'il est sélectionné ou actif.

- **`button:focus`** : Ce sélecteur s'applique à un bouton dès qu'il est sélectionné, peu importe comment il a été sélectionné. Par exemple, si tu cliques sur le bouton avec ta souris ou si tu utilises la touche "Tab" pour naviguer jusqu'à lui, le style défini pour `button:focus` sera appliqué.

- **`button:focus-visible`** : Ce sélecteur est un peu plus intelligent. Il s'applique seulement lorsque le bouton est sélectionné de manière visible. Par exemple, si tu utilises la touche "Tab" pour naviguer jusqu'au bouton, le style défini pour `button:focus-visible` sera appliqué. Cependant, si tu cliques sur le bouton avec ta souris, le style ne sera pas appliqué. Cela permet d'éviter d'afficher des styles de focus lorsque ce n'est pas nécessaire, comme lors d'un clic de souris.

En résumé :

- `button:focus` s'applique toujours quand le bouton est sélectionné.
- `button:focus-visible` s'applique seulement quand le bouton est sélectionné de manière visible (comme avec la touche "Tab").

Cela permet de rendre l'interface utilisateur plus agréable et moins encombrée visuellement.
