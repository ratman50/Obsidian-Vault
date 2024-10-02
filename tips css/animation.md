## ==Animation==
La propriété `animation-fill-mode` en CSS détermine comment un élément animé doit être stylisé avant que l'animation ne commence et après qu'elle soit terminée. L'option `backwards` est l'une des valeurs possibles de cette propriété et elle a un effet spécifique avant que l'animation ne démarre.
### Explication de `animation-fill-mode: backwards;`

Lorsque vous utilisez `animation-fill-mode: backwards`, cela signifie que l'élément adoptera les styles définis dans la première image clé (**keyframe**) de l'animation, **avant même que l'animation ne commence**. Cela est particulièrement utile si vous souhaitez que l'élément commence dans l'état initial de l'animation, même avant le déclenchement de celle-ci.