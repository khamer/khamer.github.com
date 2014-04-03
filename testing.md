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


This is a newfile
=================

This is testing the rendering engine.


Below is a test of GitHub style fenced code blocks (with PHP language hinting.)

```php
<?php this is a Github Style fenced code block.
```

Below is a test of Markdown Extra's alternative code block syntax:

~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
This is a Markdown Extra Code Block
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Below is a Markdown Extra Table:

First Header  | Second Header
------------- | -------------
Content Cell  | Content Cell
Content Cell  | Content Cell

Here is a copy-paste of Markdown Extra's definition list stuff:

Term 1

:   This is a definition with two paragraphs. Lorem ipsum 
    dolor sit amet, consectetuer adipiscing elit. Aliquam 
    hendrerit mi posuere lectus.

    Vestibulum enim wisi, viverra nec, fringilla in, laoreet
    vitae, risus.

:   Second definition for term 1, also wrapped in a paragraph
    because of the blank line preceding it.

Term 2

:   This definition has a code block, a blockquote and a list.

        code block.

    > block quote
    > on two lines.

    1.  first list item
    2.  second list item

Lastly, here is some mixed HTML with markdown content:

<div style="background: blue;" markdown="1">
Hello, **my name** is *Kevin*.
</div>

This is testing for GitHub Flavored Markdown:

perform_complicated_task

And here's some strikethrough from GHFM

This next phrase ~~has a line through it~~.
