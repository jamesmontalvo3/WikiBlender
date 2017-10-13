WikiBlender
===========

Give a landing page for a multi-wiki (MediaWiki) environment. Also provides a unified Recent Changes page and all-wiki search utility.

## BlenderSettings.php
Below is an example of what you should put in the BlenderSettings.php file.


```php

<?php

$blenderTitle = "Our Company Wikis";
$blenderServer = "https://example.com/wikis/";
// if your Blender is setup for a sub-domain based wiki farm?
// defaults to 'path'
$blenderMode = "domain";

$blenderWikis = array(
	array(
		"path"     => "acct",
		"name"     => "Accounting",
		"logo"     => "acct/skins/common/images/wiki.png",
	),
	array(
		"path"     => "hr",
		"name"     => "Human Resources",
		"logo"     => "hr/skins/common/images/wiki.png",
	),
	array(
		"path"     => "marketing",
		"name"     => "Marketing",
		"logo"     => "marketing/skins/common/images/logo.png",
	),
);


$blenderFooterLinks = array(
	"<a href='http://example.com'>Company Homepage</a>",
	"<a href='http://example.com/careers'>Careers</a>",
);


$blenderAdmins = array(
	"John.Smith@example.com" => "John Smith",
	"Sarah.Jones@example.com" => "Sarah Jones",
);


```
