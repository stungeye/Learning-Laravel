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
