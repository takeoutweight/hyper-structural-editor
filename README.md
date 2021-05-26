# hyper-structural-editor
history-aware editing, structure-aware history.

There has been significant behind-the-scenes work to this end. Stay tuned.

## Use cases

* Semantic refactoring-style patches from libraries for client code brings ergonomics of dynlangs. I.e. renaming a type name at definition site comes with the transformation that changes call-sites. So the library author can effectively propose refactorings of client code
* Typed Macros
* Multi-cursors as structure & type-aware lightweight syntax selectors
* Nameless pattern variables via graphical pattern syntax
* Pervasive "code lenses" eg. editing within git staging view
* Undo / version control combined
* Semantic / structural laws for rebasing/simplifying patches
* Pairing via subscribing to live patch streams
* Dr. Racket style visual linking of semantic reference structure
* Maintain "last-good-compile" structure, all jump-to-source, type info, etc, maximally works on broken edits
* History-aware polymorphism, blame recent code for unification errors etc
* Frank-style applicative monad syntax
* Local-to-function sum types, mimicking Clojure-style keywords with quick "add to local sum" ergonomics on new usages
* Pervasive forward/backward references proactively visualized. Encourage "berry-picking" navigation.
