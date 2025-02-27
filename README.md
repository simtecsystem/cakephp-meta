# Meta plugin for CakePHP
[![License](https://poser.pugx.org/dereuromark/cakephp-meta/license.svg)](https://packagist.org/packages/dereuromark/cakephp-meta)
[![Minimum PHP Version](http://img.shields.io/badge/php-%3E%3D%205.6-8892BF.svg)](https://php.net/)
[![Coding Standards](https://img.shields.io/badge/cs-PSR--2--R-yellow.svg)](https://github.com/php-fig-rectified/fig-rectified-standards)

This plugin is an Fork of [dereuromark](https://github.com/dereuromark/cakephp-meta) to implement compatibility for CakePHP >= 3.6
##
This plugin helps to maintain and output meta tags for your HTML pages, including SEO relevant parts like
"title", "keywords", "description", "robots" and "canonical".

It can be used as a simple view-only approach using the included helper, it can also be DB driven if desired, or dynamically
be created from the controller context by passing the meta data to the view.

## Installation and Usage
Please see [Docs](docs)

## ToDos

### DB driven approach
Adding a Meta component and Metas Table we can pull data from an admin backend inserted DB table.
Those could overwrite then any defaults set via actions or ctp templates.

