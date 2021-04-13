¡Ya sabés bastante de CSS! :raised_hands: Pero… ¿sabías que todo es una caja? :hushed: Bueno, o al menos en eso nos basamos al momento de diseñar: en el _modelo de cajas_. Es por esto que a cada elemento HTML se lo considera una caja :package: compuesta por un contenido, un margen interior, un borde y un margen exterior.

<div style="display:center;">
<img src="https://raw.githubusercontent.com/MumukiProject/mumuki-guia-html-diseno/master/assets/modelo_cajas_1566497793652.png" alt="modelo_cajas_1566497793652.png" width="auto" height="auto">
</div>

Esto quiere decir que cuando usábamos `height` y `width` para modificar el alto y el ancho de un elemento, en realidad estábamos modificando el tamaño de su **contenido**. Así que cuidado a la hora de calcular el tamaño de un elemento :straight_ruler: ya que tenemos que considerar también las medidas de sus márgenes y bordes. Veamos...

> Si un elemento tiene establecido un ancho de `320px` y `30px` de margen exterior. ¿Cuánto será el ancho final de la caja?