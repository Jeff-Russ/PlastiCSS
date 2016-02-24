# Routestrap
## A better Bootstrap that speaks only when spoken to

### Description 

Twitter's Boostrap is a great stylesheet/Javascript framework but if you're like me you find yourself spending just as much time trying to block or override it's behavior as you spend using it as intended. Custom installations barely help as the smallest units are still rather large bundles of CSS classes. Worst of all, Boostrap changes the default behavior of many HTML tag whether you use the classes meant to utilize these new behaiviors or not.  

The end result is a large stylesheet with many unused classes and even more of your own definitions in place to override their overrides.

Thanks to Sass's "placeholders" there is a way to encapsulate each class into tidy "silent classes" that do not compile unless you @extend them into real classes. In other words, it makes it possible to have a library that compiles into a completely blank CSS file unless you specifically state which classes you intend on using.  

This makes for cleaner, smaller stylesheets and less unexpected behavior. 

### Status

Routestrap is in production and code should be pushed to this repo soon.


