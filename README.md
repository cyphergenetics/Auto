Auto IRC Bot 3.0
============================================================
------------------------------------------------------------

## Table of Contents
1.   Description
2.   Developers
3.   Requirements
4.   How to install
5.   How to upgrade
6.   Help, Bugs, Suggestions

------------------------------------------------------------
## 1. DESCRIPTION

Auto IRC Bot is an IRC channel bot that was created in
December of 2009; over time, it progressed into a bot with an
advanced and lightweight module API. Many of its features
are modules and can be loaded/unloaded to your wish.

Using the module API, you can also write your own modules to
further extend your copy.  If you think your module is useful
and should be included in the mainline program, you can
contact us and request that your module be added to
contributed modules. There is a chance that it will be accepted.


## 2. DEVELOPERS

Auto IRC Bot is developed by Arinity Development Group, a team
of people who contribute their time and knowledge to the
maintenance of Auto, and other projects.

+ Matthew Barksdale &lt;mattwb65@gmail.com&gt;
+ Russell Bradford &lt;Russell@rbradford.me&gt;
+ Liam Smith &lt;me@liam.co&gt;
+ Alexandria "alyx" Wolcott &lt;alyx@woomoo.org&gt;


Contributors - Non-developers who contribute to the project
greatly.

+ None at present.

'Retired' Developers 

+ Elijah "starcoder" Perrault &lt;elijah@starcoder.info&gt;

## 3. REQUIREMENTS
Auto being a Perl IRC Bot obviously requires perl (5.10+) be installed. If you use *nix most package managers have this as 'perl'.
If you're using OS X, this is already installed on your system. Lastly, if you're using Windows we suggest [Strawberry Perl](http://strawberryperl.com/).

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

## 4. HOW TO INSTALL
Installation documentation can be found [here](http://wiki.xelhua.org/index.php/Auto:Installation_guide). (yes, down)


## 5. HOW TO UPGRADE

Reserved. Currently there is no method of upgrading version.


## 6. HELP, BUGS, SUGGESTIONS

For help with Auto, you can ask on the [forums](http://forums.xelhua.org) or in our IRC chatroom at irc.arinity.org
&#35;auto.

To report a bug, please visit our IRC channel.
Thanks for contributing by reporting issues!

To suggest a feature, it's best to post it on the above link,
but you can also let us know in our IRC chatroom.

