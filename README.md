# Selenium standalone server #

This is a composer compatible version of the standalone Selenium server. It's designed to mirror the version numbers of
selenium itself.

## Installation ##
To include in your project, add the following line to your composer.json file:

    "pawcode/selenium-standalone": 2.*
    
Or to have composer do it for you:

    $ composer.phar require pawcode/selenium-standalone:2.x
    
## Usage ##
Once in your project, you can run it from the `vendor/bin` directory:

    $ java -jar bin/selenium-standalone.jar
    
