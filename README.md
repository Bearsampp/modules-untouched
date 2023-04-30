<p align="center">
<a href="https://bearsampp.com" target="_blank"><img width="250" src="img/Bearsampp-logo.svg"></a></p>
</p>
<p align="center">
<a href="https://github.com/bearsampp/modules-untouched/tags"><img src="https://flat.badgen.net/github/tag/Bearsampp/modules-untouched" alt="Tag"></a>
<a href="https://github.com/sponsors/N6REJ"><img src="https://img.shields.io/badge/sponsor-N6REJ-181717.svg?logo=github&style=flat-square" alt="Become a sponsor"></a>
<a href="https://www.paypal.me/BearLeeAble"><img src="https://img.shields.io/badge/donate-paypal-00457c.svg?logo=paypal&style=flat-square" alt="Donate Paypal"></a>
</p>


This a sub-repo of [Bearsampp project](https://github.com/bearsampp/bearsampp) involving mirror of all modules binaries untouched from their original locations.<br />
There are hosted on Github to prevent dead links.<br />
Binaries files that are not available as archives artifacts or single file are rebuilt for bearsampp but original files are included too.<br />
Issues must be reported on [Bearsampp repository](https://github.com/bearsampp/bearsampp/issues).

- [Adminer](#adminer)
- [Apache](#apache)
- [Composer](#composer)
- [ConsoleZ](#consolez)
- [Filezilla Server](#filezilla-server)
- [Ghostscript](#ghostscript)
- [Git](#git)
- [MailHog](#mailhog)
- [MariaDB](#mariadb)
- [Memcached](#memcached)
- [MySQL](#mysql)
- [ngrok](#ngrok)
- [Node.js](#nodejs)
- [Perl](#perl)
- [PHP](#php)
- [phpMyAdmin](#phpmyadmin)
- [phpPgAdmin](#phppgadmin)
- [PostgreSQL](#postgresql)
- [Python](#python)
- [Ruby](#ruby)
- [Webgrind](#webgrind)
- [XDebugClient](#xdebugclient)
- [Yarn](#yarn)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

## Adminer

Available as a single PHP file.<br />
[Login server enhanced](https://github.com/crazy-max/login-servers-enhanced) plugin and [Adminer theme by Hever](https://raw.githubusercontent.com/vrana/adminer/master/designs/hever/adminer.css) have been integrated.

* https://github.com/vrana/adminer/releases
* https://github.com/vrana/adminer/blob/master/plugins/plugin.php

## Apache

No rebuild required. Available as archive artefact (zip).

* http://www.apachehaus.com/cgi-bin/download.plx

## Composer

No rebuild required. Available as a single PHAR file.

* https://getcomposer.org/ ( windows only has .exe installer )
* https://github.com/composer/composer/releases ( preferred )

## ConsoleZ

ConsoleZ with extra dependencies.<br />
See `deps.properties` file on the module repository.

#### ConsoleZ

No rebuild required. Available as archive artefact (zip).

* https://github.com/cbucher/console/releases

#### Clink

No rebuild required. Available as archive artefact (zip).

* https://github.com/mridgers/clink

#### GnuWin32 CoreUtils

No rebuild required. Available as archive artefact for Binaries and Dependencies (zip).

* http://gnuwin32.sourceforge.net/packages/coreutils.htm

## Filezilla Server

Rebuild required, only available as setup executable.<br />
Extracted using 7zip and rebuild without unecessary files (sources, readme).

* http://sourceforge.net/projects/filezilla/files/FileZilla%20Server/
* http://mirror.ufs.ac.za/filezilla/FileZilla%20Server/

## Ghostscript

Rebuild required, only available as setup executable.<br />
Extracted using 7zip.

* https://www.ghostscript.com/download/gsdnld.html
* https://github.com/ArtifexSoftware/ghostpdl-downloads/releases

## Git

No rebuild required. Available as portable exe (.exe).

* https://github.com/git-for-windows/git/releases

## MailHog

No rebuild required. Available as a single EXE file.

* https://github.com/mailhog/MailHog/releases

## MariaDB

No rebuild required. Available as archive artefact (zip).

* https://downloads.mariadb.org/mariadb/+releases/

## Memcached

Extract zip and drill down to libevent > 2.0 and then x64.
Zip all files up into memcached-VERSION.7z.
Available as dual archive artefact (zip).
<b> Windows dll's seem to be no longer being made by memcached.  Use nono303's build</b>
</i>Do NOT confuse this with the "memcache" contained as part of php pecl package.  They work together</i>

* https://github.com/nono303/memcached

## MySQL

No rebuild required. Available as archive artefact (zip).

* https://dev.mysql.com/downloads/mysql/

## ngrok

No rebuild required. Available as a single EXE file.

* https://ngrok.com/download

## Node.js

No rebuild required. Available as msi or 7z artefact.

* https://nodejs.org/dist/

## Perl

No rebuild required. Available as archive artefact (zip).

* http://strawberryperl.com/releases.html

## PHP

No rebuild required. Available as archive artefact (zip).

* [php](https://windows.php.net/download)
* [memcache](https://github.com/nono303/PHP-memcache-dll/tags)
* [xdebug](https://xdebug.org/download)
* [imagick](https://pecl.php.net/package/imagick) ( use dll versions )
* [imagemagick](https://windows.php.net/downloads/pecl/deps/)
* [pear](https://pear.php.net/package/pearweb_phars/download/)
<h6><b>Pear requires extracting and using the "install-pear-nozlib.phar"</b></h6> 
<h6>*all of these are required when updating php.</h6>

## phpMyAdmin

No rebuild required. Available as archive artefact (zip).

* https://www.phpmyadmin.net/downloads/

## phpPgAdmin2

No rebuild required. Available as archive artefact (zip).

* https://github.com/ReimuHakurei/phpPgAdmin

## PostgreSQL

No rebuild required. Available as archive artefact (zip).

* https://www.enterprisedb.com/download-postgresql-binaries

## Python

Rebuild required, only available as setup executable.<br />
Extracted using 7zip.

* https://winpython.github.io/ ( read readme )
* https://www.lfd.uci.edu/~gohlke/pythonlibs/#pywin32
* https://github.com/winpython/winpython/releases ( official git )
<b>MUST use pyqt package</b>
![image](https://user-images.githubusercontent.com/1850089/235342622-a27ecfdf-7882-422d-af07-03bf8537ea94.png)


Need to set pyqt properties to match download
![image](https://user-images.githubusercontent.com/1850089/179404623-aedf7592-5979-4c72-a89b-d0839acd1805.png)


## Ruby

Rebuild required, only available as setup executable.<br />
Extracted using 7zip.

* http://rubyinstaller.org
* https://rubygems.org

## Webgrind

No rebuild required. Available as archive artefact (zip).

* https://github.com/jokkedk/webgrind/releases

## XDebugClient

No rebuild required. Available as archive artefact (zip).

* https://code.google.com/archive/p/xdebugclient/

## Yarn

No rebuild required. Available as msi artefact.

* https://yarnpkg.com/en/docs/install/
