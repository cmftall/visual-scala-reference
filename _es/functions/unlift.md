---
name: unlift
---

# `unlift`

@include [signatures/unlift.md]

`unlift` crea una función anónima que devuelve el valor envuelto con `Some` devuelto por esta función parcial.

<figure class="diagram">
  <img src="../images/unlift.svg" alt="unlift function">
  <!-- <figcaption class="diagram-desc"></figcaption> -->
</figure>

Si esta función devuelve `None` entonces la función anónima lanzará una excepción `MatchError`.

<figure class="diagram">
  <img src="../images/unlift.2.svg" alt="unlift function">
  <!-- <figcaption class="diagram-desc"></figcaption> -->
</figure>
