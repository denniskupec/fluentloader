FluentLoader
============

SplClassLoader modified with an added method that makes this _fluent_. Makes things a little more simple.  

**Original Class:** https://gist.github.com/jwage/221634  

**Registering one namespace:**

```php
require("<your-path>/FluentClass.php");  
FluentLoader::create("namespace", "path");
```

**Registering multiple:**

```php
require("<your-path>/FluentClass.php");  
FluentLoader::create(array(
  "apples" => "path-to-fruit-basket",  
  "beef" => "path-to-pasture"
));
```
