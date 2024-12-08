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
Use threadsafe packages!<br />
Issues must be reported on [Bearsampp repository](https://github.com/bearsampp/bearsampp/issues).

- [Adminer](#adminer)
- [Apache](#apache)
- [Bruno](#bruno)
- [Clink](#clink)
- [Composer](#composer)
- [ConsoleZ](#consolez)
- [Ghostscript](#ghostscript)
- [Git](#git)
- [Mailpit](#mailpit)
- [MariaDB](#mariadb)
- [Memcached](#memcached)
- [MySQL](#mysql)
- [Node.js](#nodejs)
- [Perl](#perl)
- [PHP](#php)
- [phpMyAdmin](#phpmyadmin)
- [phpPgAdmin](#phppgadmin2)
- [PostgreSQL](#postgresql)
- [Prerequisite](#Prerequisites)
- [Python](#python)
- [Ruby](#ruby)
- [Webgrind](#webgrind)
- [Xlight](#xlight)
- [Yarn](#yarn)

## Adminer

Available as a single PHP file.<br />
[Login server enhanced](https://github.com/crazy-max/login-servers-enhanced) plugin and [Adminer theme by Hever](https://raw.githubusercontent.com/vrana/adminer/master/designs/hever/adminer.css) have been integrated.

* https://github.com/vrana/adminer/releases
* https://github.com/vrana/adminer/blob/master/plugins/plugin.php

## Apache

No rebuild required. Available as archive artefact (zip).

* https://www.apachelounge.com/download/
* be sure to get mod_fcgid also

NOTE: Check OpenSSL version here: https://www.apachelounge.com/viewforum.php?f=1

## Bruno

extract and move everything in "win-unpacked" to root.
delete "win-unpacked"
rezip and upload

* https://www.usebruno.com/downloads

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

* https://github.com/chrisant996/clink

#### GnuWin32 CoreUtils

No rebuild required. Available as archive artefact for Binaries and Dependencies (zip).

* http://gnuwin32.sourceforge.net/packages/coreutils.htm

## Ghostscript

Rebuild required, only available as setup executable.<br />
Extracted using 7zip.

* https://www.ghostscript.com/download/gsdnld.html
* https://github.com/ArtifexSoftware/ghostpdl-downloads/releases

## Git

No rebuild required. Available as portable exe (.exe).

* https://github.com/git-for-windows/git/releases

## Mailpit

No rebuild required.

* https://github.com/axllent/mailpit/releases

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
*  [try here first](https://phpext.phptools.online/extension/caching/memcached-19)

## MySQL

No rebuild required. Available as archive artefact (zip).

* https://dev.mysql.com/downloads/mysql/

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
* [xdebug](https://xdebug.org/download/historical)
* [imagemagick:](https://imagemagick.org/script/download.php#windows)
* [imagick:](https://mlocati.github.io/articles/php-windows-imagick.html)
* [pear](https://pear.php.net/package/pearweb_phars/download/)
<h6><b>Pear requires extracting and using the "install-pear-nozlib.phar"</b></h6> 
<h6>*all of these are required when updating php.</h6>
<h6>test imagemagick with php --ri imagick</h6>

## phpMyAdmin

No rebuild required. Available as archive artefact (zip).

* https://www.phpmyadmin.net/downloads/

## phpPgAdmin2

No rebuild required. Available as archive artefact (zip).

* https://github.com/ReimuHakurei/phpPgAdmin

## PostgreSQL

No rebuild required. Available as archive artefact (zip).

* https://www.enterprisedb.com/download-postgresql-binaries

## Prerequisites
No rebuild required.  Update src.<br>

[Latest VC](https://learn.microsoft.com/en-us/cpp/windows/latest-supported-vc-redist?view=msvc-170#latest-microsoft-visual-c-redistributable-version)

## Python

Rebuild required, only available as setup executable.<br />
Extracted using 7zip.

* https://pypi.org/project/pywin32/#files ( Wheel )
* https://github.com/winpython/winpython/releases ( official git )
<b>MUST use pyqt package, which is the one WITHOUT the "dot" in it.</b>
![image](https://user-images.githubusercontent.com/1850089/235342622-a27ecfdf-7882-422d-af07-03bf8537ea94.png)


Need to set pyqt properties to match download
![image](https://user-images.githubusercontent.com/1850089/179404623-aedf7592-5979-4c72-a89b-d0839acd1805.png)

uznip, move files into root, delete subfolder, rezip and upload


## Ruby

No rebuild required

* [http://rubyinstaller.org](https://rubyinstaller.org/downloads/) use 7-zip archive build
* https://rubygems.org

## Webgrind

No rebuild required. Available as archive artefact (zip).

* https://github.com/jokkedk/webgrind/releases

## Xlight

No rebuild required.

* https://www.xlightftpd.com/download.htm

## Yarn

No rebuild required. Available as msi artefact.
Requires nodejs also.

* https://yarnpkg.com/en/docs/install/
* https://nodejs.org/en
