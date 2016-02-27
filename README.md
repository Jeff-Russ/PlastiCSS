# Routestrap
## A better Bootstrap that speaks only when spoken to

### Description 

Twitter's Boostrap is a great stylesheet/Javascript framework but if you're like me you find yourself spending just as much time trying to block or override it's behavior as you spend using it as intended. Custom installation barely help as the smallest units are still rather large bundles of CSS classes. Worst of all, Boostrap effects the default behavior of many HTML tag whether you use the classes meant to utilize these new behaiviors or not.  

The end result is a large stylesheet with many unused classes and even more definitions in place to override their overrides. I needed a better solution.

Thanks to Sass's "placeholders" I saw a way to encapsulate each class into tidy "silent classes" that do not compile unless you @extend them into real classes. In other words, it makes it possible to have a library that compiles into a completely blank CSS file unless you specifically state which classes you intend on using.  

This makes for cleaner, smaller stylesheets and less unexpected behavior. 

### Status

* file _1_ is identical to twbs when everything is selected
* file _2_ is theoretically bug free. it's identical but rearranged slightly
* file _3_ grids are identical to twbs when everything is selected
* file _4_ tables fixed. problem was a placeholder in a mixin!
* file _4_ forms is functionally identical
* the rest? not.
