Symfony Response Application
============

The "Symfony Response Application" is a simple application to show how to response a 
request following the [Symfony Best Practices][1].

Requirements
------------

Require the [usual Symfony application requirements][2].

  * PHP 7.2.9 or higher
  * Some PHP extensions
  * Composer
  * Symfony CLI

Installation
------------

Clone the [repository][3] on your computer:

```bash
$ git clone https://github.com/mickaelbober/symfony-response.git symfony-response
```

Composer
------------

[Download Composer][4] to install the `composer` binary on your computer and install
dependencies to the `./vendor` directory.

```bash
$ cd symfony-response/
$ composer install
```

Symfony CLI
------------

[Download Symfony][5] to install the `symfony` binary on your computer. 

```bash
$ wget https://get.symfony.com/cli/installer -O - | bash
```

Run this command and access the application in your
browser at the given URL (<https://localhost:8000> by default):

```bash
$ cd symfony-response/
$ symfony server:start
```

If you don't have the Symfony binary installed, run `php -S localhost:8000 -t public/`
to use the built-in PHP web server or [configure a web server][6] like Nginx or
Apache to run the application.

References
------------

 * [The HttpFoundation Component][7]
 * [Symfony Request Object][8]
 * [Symfony Response Object][9]
 * [Routing][10]
 * [The HttpKernel Component][11]
 * [Openclassrooms.com : Tutorial][12]

[1]: https://symfony.com/doc/current/best_practices.html
[2]: https://symfony.com/doc/current/setup.html
[3]: https://github.com/mickaelbober/symfony-response
[4]: https://getcomposer.org/download/
[5]: https://symfony.com/download
[6]: https://symfony.com/doc/current/setup/web_server_configuration.html
[7]: https://symfony.com/doc/current/components/http_foundation.html
[8]: https://symfony.com/doc/current/introduction/http_fundamentals.html#symfony-request-object
[9]: https://symfony.com/doc/current/introduction/http_fundamentals.html#symfony-response-object
[10]: https://symfony.com/doc/current/routing.html
[11]: https://symfony.com/doc/current/components/http_kernel.html
[12]: https://openclassrooms.com/fr/courses/5489656-construisez-un-site-web-a-l-aide-du-framework-symfony-4/5489663-realisez-votre-premiere-page
