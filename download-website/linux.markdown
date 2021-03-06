% Haskell Platform for Linux
%

-------------------------------
< [Home]
-------------------------------

[Home]: index.html

**Community-supported versions of the Haskell Platform on Linux and Unix**

---------                                                               ---------                                                               ---------                                                              
![](http://hackage.haskell.org/platform/icons/ubuntu.png) [Ubuntu]      ![](http://hackage.haskell.org/platform/icons/debian.png) [Debian]      ![](http://hackage.haskell.org/platform/icons/fedora.png) [Fedora]   
![](http://hackage.haskell.org/platform/icons/arch.png) [Arch Linux]    ![](http://hackage.haskell.org/platform/icons/gentoo.png) [Gentoo]      ![](http://hackage.haskell.org/platform/icons/nixos.png) [NixOS]        
![](http://hackage.haskell.org/platform/icons/openbsd.png) [OpenBSD]    ![](http://hackage.haskell.org/platform/icons/freebsd.png) [FreeBSD]    ![](http://hackage.haskell.org/platform/icons/mint.png) [Mint]
---------                                                               ---------                                                               --------- 

[Ubuntu]: http://packages.ubuntu.com/haskell-platform
[Debian]: http://packages.debian.org/haskell-platform
[Fedora]: https://admin.fedoraproject.org/community/?package=haskell-platform#package_maintenance
[Arch Linux]: http://www.archlinux.org/packages/extra/i686/haskell-platform/
[Gentoo]: http://www.haskell.org/haskellwiki/Gentoo/HaskellPlatform
[NixOS]: http://hydra.nixos.org/job/nixpkgs/trunk/haskellPackages_ghc6104.haskellPlatform_2011_4_0_0
[OpenBSD]: http://openports.se/meta/haskell-platform
[FreeBSD]: http://www.freshports.org/devel/hs-haskell-platform/
[Mint]: http://community.linuxmint.com/software/view/haskell-platform

**Information for other systems**

---------                                                                 ---------                                                                  ---------
![](http://hackage.haskell.org/platform/icons/opensuse.png) [openSUSE]    ![](http://hackage.haskell.org/platform/icons/mandriva.png) [Mandriva]     
---------                                                                 ---------                                                                  ---------

[Jaunty]: http://sitr.us/2009/07/02/how-to-install-haskell-platform-on-ubuntu-jaunty.html
[Karmic]: http://davidsiegel.org/haskell-platform-in-karmic-koala/
[Lucid]: https://launchpad.net/~justinbogner/+archive/haskell-platform
[openSUSE]: https://build.opensuse.org/project/show?project=devel:languages:haskell
[Mandriva]: http://wiki.mandriva.com/en/Development/Tasks/Packaging/Policies/Haskell

**Build from source**

For Unix systems (including Mac OS X), there is a source installer.

![](http://hackage.haskell.org/platform/icons/source.png)
<a href="http://lambda.haskell.org/platform/download/2011.4.0.0/haskell-platform-2011.4.0.0.tar.gz" onClick="javascript: pageTracker._trackPageview('/downloads/source'); ">haskell-platform-2011.4.0.0.tar.gz</a>

You need GHC 7.0.4 installed before building the platform. You can get this from your distro or
you can get a [GHC 7.0.4 generic binary].

[GHC 7.0.4 generic binary]: http://haskell.org/ghc/download_ghc_7_0_4.html#distros

To install from source download and unpack the installer, then (possibly with 'sudo'):

        ./configure
        make
        make install

You may pass --prefix flags to change the default install path.

Complete [instructions for installing from source] are available.

[instructions for installing from source]: http://www.vex.net/~trebla/haskell/haskell-platform.xhtml

<!--
**Build from cabal**

If you already have a reasonable Haskell development environment with
GHC 7.0.2 and cabal-install, you can build the platform from the Cabal
package alone.

![](http://hackage.haskell.org/platform/icons/cabal.png)
<a href="http://hackage.haskell.org/platform/2010.2.0.0/cabal/haskell-platform-2010.2.0.0.tar.gz" onClick="javascript: pageTracker._trackPageview('/downloads/cabal'); ">Haskell Platform Cabal Package</a>

To install, unpack the cabal tarball, and run:

        cabal install
 -->

**Older Releases**

Older releases of the Haskell Platform are available:

* **2011**
    * <a href="http://lambda.haskell.org/platform/download/2011.2.0.1/haskell-platform-2011.2.0.1.tar.gz" onClick="javascript: pageTracker._trackPageview('/downloads/source/old'); ">HP 2011.2.0.1</a> source, April 2011
    * <a href="http://lambda.haskell.org/platform/download/2011.2.0.0/haskell-platform-2011.2.0.0.tar.gz" onClick="javascript: pageTracker._trackPageview('/downloads/source/old'); ">HP 2011.2.0.0</a> source, March 2011
* **2010**
    * <a href="http://hackage.haskell.org/platform/2010.2.0.0/haskell-platform-2010.2.0.0.tar.gz" onClick="javascript: pageTracker._trackPageview('/downloads/source/old'); ">HP 2010.2.0.0</a> source, July 2010
    * <a href="http://hackage.haskell.org/platform/2010.1.0.0/haskell-platform-2010.1.0.0.tar.gz" onClick="javascript: pageTracker._trackPageview('/downloads/source/old'); ">HP 2010.1.0.0</a> source, March 2010
* **2009**
    * <a href="http://hackage.haskell.org/platform/2009.2.0.2/haskell-platform-2009.2.0.2.tar.gz" onClick="javascript: pageTracker._trackPageview('/downloads/source/old'); ">HP 2009.2.0.2</a> source, July 2009
    * <a href="http://hackage.haskell.org/platform/2009.2.0.1/haskell-platform-2009.2.0.1.tar.gz" onClick="javascript: pageTracker._trackPageview('/downloads/source/old'); ">HP 2009.2.0.1</a> source, June 2009
    * <a href="http://hackage.haskell.org/platform/2009.2.0/haskell-platform-2009.2.0.tar.gz" onClick="javascript: pageTracker._trackPageview('/downloads/source/old'); ">HP 2009.2.0</a> source, May 2009

