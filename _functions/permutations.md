---
title: permutations
layout: function
permalink: /permutations
---

# `permutations`

~~~ scala
trait Collection[A] {
  def permutations: Iterator[Collection[A]]
}
~~~

`permutations` computes all the possible permutations of this collection and returns an `Iterator` to iterate them.

<figure class="diagram">
  <img src="images/permutations.svg" alt="permutations function">
  <!-- <figcaption class="diagram-desc"></figcaption> -->
</figure>