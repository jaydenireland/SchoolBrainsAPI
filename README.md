# SchoolBrainsAPI
SchoolBrains API wrapper for PHP

Start a new instance like this
```php
<?php
require("api.php");
$api = new schoolBrains($username, $password);
?>
```

Methods available are
```php
classes();
grades();
schedule($term);
attendance();
id();
getName();
letterToPercent($letter);
```
