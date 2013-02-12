---
title: testing markdown engines
layout: default
---

<div>
a sentence with **markdown** in it, but no attribute.
</div>

<div markdown="1">
a sentence with **markdown** in it with the attribute.
</div>

{::comment}
This is a comment, kramdown ignores this.
{:/comment}

Maruku supports adding [IDs](#){:title="bananas"}

``` ruby
Redcarpet = Supports.code("blocks like this")
```

Red carpet supports ~~strikethrough~~, not sure about Maruku. `2^(nd)`, it supports superscripts.

Testing.
