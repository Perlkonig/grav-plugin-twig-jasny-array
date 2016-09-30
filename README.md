# Twig Jasny Array Plugin

The **Twig Jasny Array** plugin is for [Grav CMS](http://github.com/getgrav/grav). It incorporates the Array module from [Jasny's Twig extensions](https://github.com/jasny/twig-extensions).

For a demo, [visit my blog](https://perlkonig.com/demos/twig-jasny-array).

## Installation

Installing the Twig Jasny Array plugin can be done in one of two ways. The GPM (Grav Package Manager) installation method enables you to quickly and easily install the plugin with a simple terminal command, while the manual method enables you to do so via a zip file.

### GPM Installation (Preferred)

The simplest way to install this plugin is via the [Grav Package Manager (GPM)](http://learn.getgrav.org/advanced/grav-gpm) through your system's terminal (also called the command line).  From the root of your Grav install type:

    bin/gpm install twig-jasny-array

This will install the Twig Jasny Array plugin into your `/user/plugins` directory within Grav. Its files can be found under `/your/site/grav/user/plugins/twig-jasny-array`.

### Manual Installation

To install this plugin, just download the zip version of this repository and unzip it under `/your/site/grav/user/plugins`. Then, rename the folder to `twig-jasny-array`. You can find these files on [GitHub](https://github.com/Perlkonig/grav-plugin-twig-jasny-array) or via [GetGrav.org](http://getgrav.org/downloads/plugins#extras).

You should now have all the plugin files under

    /your/site/grav/user/plugins/twig-jasny-array
  
## Configuration

The config consists of the single `enabled` field, which turns the plugin off and on.

## Usage

This plugin *only* incorporates the Array module from [Jasny's Twig extensions](https://github.com/jasny/twig-extensions). The other modules duplicate functionality found in the [Twig Extensions](https://github.com/Perlkonig/grav-plugin-twig-extensions) and [Twig PCRE](https://github.com/kesslernetworks/grav-plugin-twigpcre) plugins.

It exposes the following filters:

  * `sum` – calculates the sum of the values in an array
  * `product` – calculates the product of the values in an array
  * `values` – returns all the values of an array
  * `as_array` – casts an object to an associative array
  * `html_attr` – turns an array into an HTML attribute string (i.e. `$key="$value"`)



