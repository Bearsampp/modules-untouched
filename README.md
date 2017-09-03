![Total downloads](https://img.shields.io/github/downloads/crazy-max/neard-modules-untouched/total.svg?style=flat-square)

This a sub-repo of [Neard project](https://github.com/crazy-max/neard) involving mirror of all modules binaries untouched from their original locations.<br />
There are hosted on Github to prevent dead links.<br />
Binaries files that are not available as archives artefacts or single file are rebuild for Neard but original files are included too.<br />
Issues must be reported on [Neard repository](https://github.com/crazy-max/neard/issues).

<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->


- [Adminer](#adminer)
- [Apache](#apache)
- [Composer](#composer)
- [Console](#console)
- [Drush](#drush)
- [Filezilla Server](#filezilla-server)
- [Ghostscript](#ghostscript)
- [Git](#git)
- [Gitlist](#gitlist)
- [HostsEditor](#hostseditor)
- 🚫 [ImageMagick](#imagemagick)
- [MailHog](#mailhog)
- [MariaDB](#mariadb)
- [Memcached](#memcached)
- [MongoDB](#mongodb)
- [MySQL](#mysql)
- [Node.js](#nodejs)
- 🚫 [Notepad2-mod](#notepad2-mod)
- [Perl](#perl)
- [PHP](#php)
- [phpMemAdmin](#phpmemadmin)
- [PhpMetrics](#phpmetrics)
- [phpMyAdmin](#phpmyadmin)
- [phpPgAdmin](#phppgadmin)
- [PHPUnit](#phpunit)
- [PostgreSQL](#postgresql)
- [Python](#python)
- [Ruby](#ruby)
- [SVN](#svn)
- [Webgrind](#webgrind)
- [WebSVN](#websvn)
- [WP-CLI](#wp-cli)
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

* https://getcomposer.org/

## Console

Console is based on Console2 with extra dependencies.<br />
See `deps.properties` file on the module repository.

#### Console2

No rebuild required. Available as archive artefact (zip).

* http://sourceforge.net/projects/console/files/console-devel/2.00/

#### ANSICON

No rebuild required. Available as archive artefact (zip).

* https://github.com/adoxa/ansicon/releases

#### Clink

No rebuild required. Available as archive artefact (zip).

* https://github.com/mridgers/clink

#### GnuWin32 CoreUtils

No rebuild required. Available as archive artefact for Binaries and Dependencies (zip).

* http://gnuwin32.sourceforge.net/packages/coreutils.htm

#### TCC/LE

Rebuild required, only available as setup executable.<br />
Extracted by installing it and rebuild without unecessary files (uninstall).

* https://jpsoft.com/all-downloads/downloads.html

## Drush

No rebuild required. Available as archive artefact (zip).<br />
Some binaries provided by GnuWin have been included as well as MySQL.

* https://github.com/drush-ops/drush/releases
* https://sourceforge.net/projects/gnuwin32/
* https://dev.mysql.com/downloads/mysql/

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

No rebuild required. Available as archive artefact (.7z).

* https://github.com/git-for-windows/git/releases
* https://github.com/msysgit/msysgit/releases

## Gitlist

No rebuild required. Available as archive artefact (tar.gz).

* http://gitlist.org/

## HostsEditor

No rebuild required. Available as archive artefact (.zip).

* https://hostseditor.codeplex.com/

## 🚫 ImageMagick

No rebuild required. Available as archive artefact (.zip).

* http://www.imagemagick.org/script/binary-releases.php

## MailHog

No rebuild required. Available as a single EXE file.

* https://github.com/mailhog/MailHog/releases

## MariaDB

No rebuild required. Available as archive artefact (zip).

* https://downloads.mariadb.org/mariadb/+releases/

## Memcached

No rebuild required. Available as archive artefact (zip).

* https://memcached.org/
* https://commaster.net/content/installing-memcached-windows

## MongoDB

No rebuild required. Available as archive artefact (zip).

* https://www.mongodb.org/dl/win32/

## MySQL

No rebuild required. Available as archive artefact (zip).

* https://dev.mysql.com/downloads/mysql/

## Node.js

No rebuild required. Available as msi or 7z artefact.

* https://nodejs.org/dist/

## 🚫 Notepad2-mod

No rebuild required. Available as archive artefact (zip).

* https://github.com/XhmikosR/notepad2-mod/releases

## Perl

No rebuild required. Available as archive artefact (zip).

* http://strawberryperl.com/releases.html

## PHP

No rebuild required. Available as archive artefact (zip).

* http://windows.php.net/downloads/releases/

## phpMemAdmin

No rebuild required. Available as archive artefact (zip).<br />
Taken from sources on Github and version tagged as Travis build number.

* https://github.com/clickalicious/phpMemAdmin/releases

## PhpMetrics

No rebuild required. Available as archive artefact (zip).

* https://github.com/phpmetrics/PhpMetrics/releases

## phpMyAdmin

No rebuild required. Available as archive artefact (zip).

* https://www.phpmyadmin.net/downloads/

## phpPgAdmin

No rebuild required. Available as archive artefact (zip).

* https://github.com/phppgadmin/phppgadmin/releases

Some are available through forked repositories :

* Tomicapo: [phppgadmin-d32e737a0de724ab954a996d5bada363c863770f](https://github.com/Tomicapo/phppgadmin/tree/d32e737a0de724ab954a996d5bada363c863770f)

## PHPUnit

No rebuild required. Available as a single PHAR file.

* https://github.com/sebastianbergmann/phpunit/releases

## PostgreSQL

No rebuild required. Available as archive artefact (zip).

* https://www.enterprisedb.com/products-services-training/pgbindownload

## Python

Rebuild required, only available as setup executable.<br />
Extracted using 7zip.

* https://winpython.github.io/
* http://www.lfd.uci.edu/~gohlke/pythonlibs/#pyqt4

## Ruby

Rebuild required, only available as setup executable.<br />
Extracted using 7zip.

* http://rubyinstaller.org
* https://rubygems.org

## SVN

Rebuild required, only available as setup executable.<br />
Installed on a computer by selecting SVNSERVE component and rebuilded.

* http://www.collab.net/downloads/subversion

## Webgrind

No rebuild required. Available as archive artefact (zip).

* https://github.com/jokkedk/webgrind/releases

## WebSVN

No rebuild required. Available as archive artefact (zip).

* http://www.websvn.info/download/

## WP-CLI

No rebuild required. Available as a single PHAR file.

* https://github.com/wp-cli/wp-cli/releases

## XDebugClient

No rebuild required. Available as archive artefact (zip).

* https://code.google.com/archive/p/xdebugclient/

## Yarn

No rebuild required. Available as msi artefact.

* https://yarnpkg.com/en/docs/install/
