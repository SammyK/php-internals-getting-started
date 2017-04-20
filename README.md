# PHP Internals: Getting Started

PHP internals is a great place to get connected to a passonate and vibrant community of coders. But knowing where to start can be difficult since much of the information is locked away in "[tribal knowledge](https://en.wikipedia.org/wiki/Tribal_knowledge)". This document aims to break down the barrier of entry for getting started with the lovely PHP internals community. **PR's are welcome!** :)

## Official Process & Culture

Possibly the highest barrier to entry is simply understanding "how things work" in PHP internals.

### RFC's (Request for Comments)

The [RFC wiki](https://wiki.php.net/rfc) is where all the proposed changes are made to PHP.

- Have an idea for PHP? [Create an RFC](https://wiki.php.net/rfc/howto)!

### Karma

PHP internals has an [ACL](https://en.wikipedia.org/wiki/Access_control_list) called "karma". Depending on your level of karma, you will be permitted to update the wiki, push to the docs SVN, push to php-src, etc.

- **@TODO:** Find a good resource to explain the karma system in detail.
- [Requesting karma](http://php.net/git-php.php) (scroll down to "Request a Git account" section)
- [Karma access control document](http://svn.php.net/viewvc/SVNROOT/global_avail?view=markup)

### Community

Where the internals folks hang out.

- [Subscribe to the internals mailing list](http://php.net/mailing-lists.php)
- [Watch the internals mailing list from afar](https://externals.io/)
- [Room 11](http://chat.stackoverflow.com/rooms/11/php) chat room
- **@TODO:** Add IRC channels
- [PHP Conferences](http://www.php.net/conferences/)


## Source

PHP is written in C.

- [php-src on GitHub](https://github.com/php/php-src)
- PHP 5: [A good overview of PHP source](http://www.phpinternalsbook.com/)

### Extensions

- PHP 5: [Building extensions](http://www.phpinternalsbook.com/build_system/building_extensions.html)
- PHP 5: [Extending & Embedding PHP](https://www.amazon.com/Extending-Embedding-PHP-Sara-Golemon/dp/067232704X/) by Sara Golemon on writing extensions for PHP 5.x.
- Sometimes learning by example is helpful. Take a look at some PR's like the [password_*() PR](https://github.com/php/php-src/pull/191/files) to see how extensions tie into source.

### Engine

- PHP 7: [Virtual Machine](https://nikic.github.io/2017/04/14/PHP-7-Virtual-machine.html)
- PHP 5: [Getting into the Zend Execution engine](http://jpauli.github.io/2015/02/05/zend-vm-executor.html)

### Blogs about php-src

- [Julien Pauli](http://jpauli.github.io/)
- [Nikita Popov](https://nikic.github.io/)

### Tools

- [Grok](http://lxr.php.net/) *seems to be down right now :/*

## Documentation

- [Official PHP Manual Contribution Guide](http://doc.php.net/tutorial/)
- [Online GUI documentation editor](https://edit.php.net/)
- [PhD: The PHP docs generator](http://doc.php.net/phd/docs/)
- [Guide: How to contribute to PHP documentation](https://www.sammyk.me/how-to-contribute-to-php-documentation)

## Testing

PHP has a black-box testing tool called [run-tests](https://github.com/php/php-src/blob/master/run-tests.php). The tests (`.phpt` files) are written in PHP so it's a great entry point for newbies to get started with PHP internals.

- [Docs for writing tests](http://qa.php.net/write-test.php)
- [The .phpt sections reference](http://qa.php.net/phpt_details.php)
- [Code coverage website](http://gcov.php.net/) (helps you find untested code)

## Bugs

The [PHP bug tracking system](https://bugs.php.net/) is where all bugs for PHP are tracked. We need help triaging bugs!

- **@TODO:** Add resources for triaging & fixing bugs

## Websites: Source Code

Nearly all the websites in the PHP ecosystem are open source. Send some PR's to make them better! :)

- [Main website (php.net) source code](https://github.com/php/web-php)
- [Bugs (bugs.php.net) source code](https://github.com/php/web-bugs)
- [Wiki (wiki.php.net) source code](https://github.com/php/web-wiki)
- [Testing/QA (qa.php.net) source code](https://github.com/php/web-qa)
- [Code Coverage (gcov.php.net) source code](https://github.com/php/web-gcov)
- [PECL website (pecl.php.net) source code](https://github.com/php/web-pecl)
