# Learning Laravel

## Setup on my Macbook

* `brew update`
* `brew cleanup`
* `brew install php`
* `brew install nginx`
* `brew install composer`
* [PHP 7.3 PCRE JIT FIX](https://stackoverflow.com/a/53709484)
* `composer global require laravel/installer`
* `composer global require laravel/valet`
* Add to `.bash_profile`: `export PATH=$PATH:~/.composer/vendor/bin`
* `source .bash_profile`
* `valet install`
* `mkdir ~/www`
* `cd ~/www`
* `valet park`
* `laravel new blog`
* Open: [http://blog.test](http://blog.test)

## Potential Admin Dashboards

* [Voyager - The Missing Laravel Admin ](https://laravelvoyager.com/academy/) - Open Source
* [LaraAdmin - Admin Panel for Laravel](http://laraadmin.com) - Open Source
* [Backback for Laravel](https://backpackforlaravel.com/) - Free Plan for Non-Commercial else 50 to 300 Euro license.
* [Nova - Official Laravel Dashboard](https://nova.laravel.com/) - $100 to $200 USD license.
