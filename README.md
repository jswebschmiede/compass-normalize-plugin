# normalize.css - Compass Plugin
A Compass plugin of Nicolas Gallagher's normalize.css project.

## Usage
Execute the following command to create a new project with compass, using normalize.css:

	$ compass create my_project -r normalize --using normalize

To add normalize.css to an existing project, edit `config.rb` and add `compass` to your imports:

	require 'normalize'

Import the plugin and use the mixin

	@import "normalize";
	
	@include normalize;
	
or include and use only parts of it:

	@import "normalize/html5";
	@import "normalize/base";
	
	@include normalize-html5;
	@include normalize-base;

## Available mixins and imports
- normalize-html5 (normalize/html5)
- normalize-base (normalize/base)
- normalize-links (normalize/links)
- normalize-typography (normalize/typography)
- normalize-lists (normalize/lists)
- normalize-embedded (normalize/embedded)
- normalize-figures (normalize/figures)
- normalize-forms (normalize/forms)
- normalize-tables (normalize/tables)

## License
Public domain

## Acknowledgements
* [Normalize.css](https://github.com/necolas/normalize.css/) is a project by [Nicolas Gallagher](http://github.com/necolas) and [Jonathan Neal](http://github.com/jonathantneal).
* [compass-normalize-plugin](https://github.com/jroettger/compass-normalize-plugin) is a [Compass](http://compass-style.org) plugin by [Johannes Röttger](http://github.com/jroettger).