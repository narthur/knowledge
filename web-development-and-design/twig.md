# Twig



## Snippets

Prevent returned HTML from being auto-escaped by Twig \([source](https://stackoverflow.com/a/44736733/937377)\):

```php
class MyParser {
    public function getHTML() {
         $rawString = '<a href="#">Hello World</a>'
         return new \Twig\Markup( $rawString, 'UTF-8' );
    }
}
```

## Links

[Key Value Arrays in Twig](https://mijingo.com/blog/key-value-arrays-in-twig) \#article - "A hash is one of [several types of literals available in Twig](http://twig.sensiolabs.org/doc/templates.html#literals). It has a key and a value. The pairs are separated by a comma and enclosed in curly braces."

[Twig Documentation](https://twig.symfony.com/doc/2.x/)

[TwigFiddle](https://twigfiddle.com/) \#webapp

[Twig property search order SO answer](https://stackoverflow.com/a/14413657/937377) \#article - “{{ lang.test }} will try to invoke one of the following, in this order:”

* $lang-&gt;test
* $lang-&gt;test\(\)
* $lang-&gt;getTest\(\)
* $lang-&gt;isTest\(\)

[Twig property search order Twig docs](https://twig.symfony.com/doc/2.x/templates.html#variables) \#article - “For convenience's sake foo.bar does the following things on the PHP layer:”

* Search order:
  * check if foo is an array and bar a valid element;
  * if not, and if foo is an object, check that bar is a valid property;
  * if not, and if foo is an object, check that bar is a valid method \(even if bar is the constructor - use \_\_construct\(\) instead\);
  * if not, and if foo is an object, check that getBar is a valid method;
  * if not, and if foo is an object, check that isBar is a valid method;
  * if not, and if foo is an object, check that hasBar is a valid method;
  * if not, return a null value.
* foo\['bar'\] on the other hand only works with PHP arrays:
  * check if foo is an array and bar a valid element;
  * if not, return a null value.

