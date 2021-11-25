![Total downloads](https://img.shields.io/github/downloads/neard/modules-untouched/total.svg?style=flat-square)

This a sub-repo of [Neard project](https://github.com/neard/neard) involving mirror of all modules binaries untouched from their original locations.<br />
There are hosted on Github to prevent dead links.<br />
Binaries files that are not available as archives artefacts or single file are rebuild for Neard but original files are included too.<br />
Issues must be reported on [Neard repository](https://github.com/neard/neard/issues).

<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->


- [Adminer](#adminer)
- [Apache](#apache)
- [Composer](#composer)
- [ConsoleZ](#consolez)
- [Filezilla Server](#filezilla-server)
- [Ghostscript](#ghostscript)
- [Git](#git)
- [Gitlist](#gitlist)
- [MailHog](#mailhog)
- [MariaDB](#mariadb)
- [Memcached](#memcached)
- [MongoDB](#mongodb)
- [MySQL](#mysql)
- [Nginx](#nginx)
- [ngrok](#ngrok)
- [Node.js](#nodejs)
- [Perl](#perl)
- [PHP](#php)
- [phpMemAdmin](#phpmemadmin)
- [phpMyAdmin](#phpmyadmin)
- [phpPgAdmin](#phppgadmin)
- [PostgreSQL](#postgresql)
- [Python](#python)
- [Ruby](#ruby)
- [SVN](#svn)
- [Webgrind](#webgrind)
- [WebSVN](#websvn)
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

* https://filezilla-project.org/download.php?show_all=1&type=server

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

## Nginx

No rebuild required. Available as archive artefact (.zip).

* http://nginx.org/en/download.html

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

* http://windows.php.net/downloads/releases/

## phpMemAdmin

No rebuild required. Available as archive artefact (zip).<br />
Taken from sources on Github and version tagged as Travis build number.

* https://github.com/clickalicious/phpMemAdmin/releases

## phpMyAdmin

No rebuild required. Available as archive artefact (zip).

* https://www.phpmyadmin.net/downloads/

## phpPgAdmin

No rebuild required. Available as archive artefact (zip).

* https://github.com/phppgadmin/phppgadmin/releases

Some are available through forked repositories :

* Tomicapo: [phppgadmin-d32e737a0de724ab954a996d5bada363c863770f](https://github.com/Tomicapo/phppgadmin/tree/d32e737a0de724ab954a996d5bada363c863770f)

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

## XDebugClient

No rebuild required. Available as archive artefact (zip).

* https://code.google.com/archive/p/xdebugclient/

## Yarn

No rebuild required. Available as msi artefact.

* https://yarnpkg.com/en/docs/install/
