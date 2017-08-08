# PDF_Label
This repository is only made for cloning the PHP_Lable script from offical FPDF releases which is available at http://www.fpdf.org/en/script/index.php. THERE WILL BE NO DEVELOPMENT IN THIS REPO.

## Installation with [Composer]

This library has not been registered with Packagist so you will have to add a custom repository definition in your composer.json file:

```json
"repositories": [
	{
		"type": "vcs",
		"url": "https://github.com/GSGCorp/pdf-label.git"
	}
],
```
With that repo definied, you can then just include the following in your the require section of your composer.json file:

```json
{
	"require": {
		"... other libraries": "... other version",

		"GSGCorp/pdf-label": "1.8.1"
	}
}
```
