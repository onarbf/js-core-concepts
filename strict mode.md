In 2009, with the release of ES5, it was added the "strict mode" to [[Javascript]].

It's still optional.

You add to your code  ``` use strict``` and then there are new guidance about what you can do to improve your code for the JS Engine.

It's mainly focused on *early errors*, those are not like syntax errors but more like bad practice errors, like having for a function the same name in two parameters:  ``function yeyu(foo,foo){}``

