## User Agent List

### Original Creator
Readme date: Nov 2 2011  
Contributors: lukapusic  
URI: http://360percents.com/posts/php-random-user-agent-generator/  
Github: https://github.com/lukapusic/random-uagent  

### Changes
Convert it to class, so it is easier to use

### Usage
```php
<?php
	require "uagent.php"
	$uagent = new UserAgentList();

	echo $uagent->get_random();
?>
```
