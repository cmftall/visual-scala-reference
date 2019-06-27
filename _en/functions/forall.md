---
name: forall
---

# `forall`

@include [signatures/forall.md]

`forall` checks whether all elements in this collection satisfy the predicate `p`, returning `false` if `p` doesn't stand for at least one element.

<figure class="diagram">
  <img src="images/forall.svg" alt="forall function">
  <!-- <figcaption class="diagram-desc"></figcaption> -->
</figure>

On empty collections there is no element which doesn't satisfy `p`, hence this function returns `true`.

<figure class="diagram">
  <img src="images/forall.2.svg" alt="forall function">
  <!-- <figcaption class="diagram-desc"></figcaption> -->
</figure>