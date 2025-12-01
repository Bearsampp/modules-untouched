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

- [Apache](#apache)
- [Bruno](#bruno)
- [Clink](#clink)
- [Composer](#composer)
- [Ghostscript](#ghostscript)
- [Git](#git)
- [Mailpit](#mailpit)
- [MariaDB](#mariadb)
- [Memcached](#memcached)
- [MySQL](#mysql)
- [Ngrok](#ngrok)
- [Node.js](#nodejs)
- [Perl](#perl)
- [PHP](#php)
- [phpMyAdmin](#phpmyadmin)
- [phpPgAdmin](#phppgadmin2)
- [PostgreSQL](#postgresql)
- [PowerShell](#powershell)
- [Prerequisite](#Prerequisites)
- [Python](#python)
- [Ruby](#ruby)
- [Xlight](#xlight)

## Apache

No rebuild required. Available as archive artefact (zip).

* https://www.apachelounge.com/download/
* be sure to get mod_fcgid also

NOTE: Check OpenSSL version here: https://www.apachelounge.com/viewforum.php?f=1

## Bruno

*Download portable x64
*No rebuld needed.

* https://www.usebruno.com/downloads

## Composer

No rebuild required. Available as a single PHAR file.

* https://getcomposer.org/ ( windows only has .exe installer )
* https://github.com/composer/composer/releases ( preferred )

## Ghostscript

Rebuild required, only available as setup executable.<br />
Extracted using 7zip.

* https://www.ghostscript.com/download/gsdnld.html
* https://github.com/ArtifexSoftware/ghostpdl-downloads/releases

Remove the following before zipping...
![image](https://github.com/user-attachments/assets/349f3d5d-679f-40d6-908c-ceb2306c1045)


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

Download https://github.com/Bearsampp/sandbox/releases/download/2025.2.11/memcached_download.bat and run it.
use the created .zip file.

<b> Windows dll's seem to be no longer being made by memcached.  Use nono303's build</b>
</i>Do NOT confuse this with the "memcache" contained as part of php pecl package.  They work together</i>

* https://github.com/nono303/memcached

## MySQL

No rebuild required. Available as archive artefact (zip).

* https://dev.mysql.com/downloads/mysql/

## Ngrok

No rebuild required. Available as a 7z artefact.

In order to see version you must first extract the .zip then check the properties->Details section of the .exe

* https://ngrok.com/downloads/windows?tab=download

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

## PowerShell

No rebuild required. Available as archive artefact (zip).

* https://github.com/PowerShell/PowerShell/releases

#### oh-my-posh

No rebuild required. Available as archive artefact for Binaries and Dependencies (zip).

* https://github.com/JanDeDobbeleer/oh-my-posh/releases

oh-my-posh theme ( Paradox - Bearsampp default )
* https://github.com/JanDeDobbeleer/oh-my-posh/blob/main/themes/paradox.omp.json

#### Customization guide
* https://amanek.com/better-command-line-experience-on-windows-with-conemu-clink-and-oh-my-posh/
To reset default bearsampp omp theme use    
```oh-my-posh init pwsh --config https://github.com/JanDeDobbeleer/oh-my-posh/blob/main/themes/paradox.omp.json | Invoke-Expression```

## Prerequisites
No rebuild required.  Update src.<br>

[Latest VC](https://learn.microsoft.com/en-us/cpp/windows/latest-supported-vc-redist?view=msvc-170#latest-microsoft-visual-c-redistributable-version)

## Python

Rebuild required, only available as setup executable.<br />
Extracted using 7zip.

* https://pypi.org/project/pywin32/#files ( Wheel )
* [https://github.com/winpython/winpython/releases ( official git )](https://winpython.github.io/)
<b>MUST use pyqt package, which is the "slim" version.</b>
![image](https://github.com/user-attachments/assets/b2c73095-d104-4ebc-a7ac-82af7d710820)


Need to set pyqt properties to match download
![image](https://user-images.githubusercontent.com/1850089/179404623-aedf7592-5979-4c72-a89b-d0839acd1805.png)

unzip, move files into root, delete subfolder, rezip and upload


## Ruby

No rebuild required

* [http://rubyinstaller.org](https://rubyinstaller.org/downloads/) use 7-zip archive build
* https://rubygems.org


## Xlight

No rebuild required.

* https://www.xlightftpd.com/download.htm
