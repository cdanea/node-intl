node-intl
=========

Simple package to link various translation files into a common functionality


Simple translation usage example:

intl.init({
	'default': 'it',
	'path': './langs/'
});
intl.get('hello', 'es');	//-> hola
intl.get('world');		//-> mondo

