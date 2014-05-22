FluentLoader
============

SplClassLoader modified with an added method that makes this _fluent_. Makes things a little more simple.  

**Original Class:** https://gist.github.com/jwage/221634  

**Original Usage:**
```php
require("<your-path>/FluentLoader.php");  
$class_loader = new FluentLoader("namespace", "path");
$class_loader->register();
// multiple times for multiple namespaces
```

**Registering one namespace:**
```php
require("<your-path>/FluentLoader.php");  
FluentLoader::create("namespace", "path");
```

**Registering multiple:**
```php
require("<your-path>/FluentLoader.php");  
FluentLoader::create(array(
  "apples" => "path-to-fruit-basket",  
  "beef" => "path-to-pasture"
));
```
