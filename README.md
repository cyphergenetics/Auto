Auto 3.0 _Euryale_
==================

Synopsis
-----------

Auto is an IRC channel bot that was created in
December of 2009; over time, it progressed into a bot with an
advanced and lightweight module API. Many of its features
are modules and can be loaded/unloaded to your wish.

Using the module API, you can also write your own modules to
further extend your copy.  If you think your module is useful
and should be included in the mainline program, you can
contact us and request that your module be added to
contributed modules. There is a chance that it will be accepted.

Please do see **Moving Forward** below for information regarding the new 4.0
_Phoenix_, and NOTICE.md.

Developers
----------

Auto 3 is developed by the Auto Project, a team
of people who contribute their time and knowledge to the
maintenance of Auto, and other projects.

- [mattwb65](https://github.com/mattwb65) &lt;mattwb65@gmail.com&gt;
- [noxgirl](https://github.com/noxgirl) &lt;xoeverlux@gmail.com&gt;

Inactive

- [RussellB28](https://github.com/RussellB28) &lt;russell@rbradford.me&gt;
- [liamsmithuk](https://github.com/liamsmithuk) &lt;me@liam.co&gt;
- [alyx](https://github.com/alyx) &lt;contact@alyxw.me&gt;
- [dwfreed](https://github.com/dwfreed)
- [grimreaper](https://github.com/grimreaper)
- [cooper](https://github.com/cooper)

Requirements
------------

Auto being a Perl IRC Bot obviously requires perl (5.10+) be installed. If you
use \*nix most package managers have this as 'perl'. If you're using OS X, this
is already installed on your system. Lastly, if you're using Windows we suggest
[Strawberry Perl](http://strawberryperl.com/).

Auto also requires a few CPAN modules in order to correctly function, they are:

+ IO::Async
+ Net::Async::HTTP
+ IO::Socket::IP
+ Class::Unload
+ IO::Async::Timer::Periodic
+ IO::Async::Stream
+ DBI

The following are required if built in a certain way:
+ IO::Socket::SSL (needed unless built with --disable-ssl)
+ MIME::Base64 (--enable-sasl)
+ DBD::mysql (--with-mysql)
+ DBD::Pg (--with-pgsql)
+ DBD::SQLite (needed unless built with --with-mysql or --with-pgsql)

Moving Forward
--------------

The Auto Project has initiated a significant revision of Auto, 4.0 _Phoenix_,
which although in-development at this time represents the latest and greatest
of Auto. If this piques your curiosity, see the [official page](http://auto.autoproj.org).

Currently, 4.0 is not ready for use in a productive environment. Support for
3.0 is planned to continue indefinitely for the moment.

You may find the [autobot-talk](http://j.mp/autotalk) mailing group to be of
interest.

Help, Bugs, Suggestions
-----------------------

Unavailable at the moment.
