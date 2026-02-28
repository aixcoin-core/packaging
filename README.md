Bitcoin Core packaging
=======

Bitcoin Core is packaged and distributed through different channels.

Advanced users can compile Bitcoin Core from source. Static binaries for Linux, as well as installers for Windows and macOS are
provided on the [website](https://aixcoincore.org/en/download/).

Bitcoin Core is also distributed on several Linux package managers:

* The `aixcoin-core` snap package for https://snapcraft.io/aixcoin-core is maintained in [/snap](/snap)
* The `org.aixcoincore.aixcoin-qt` flatpak package is maintained under their organization: https://github.com/flathub/org.aixcoincore.aixcoin-qt
* The `aixcoin-core` guix package is maintained under https://codeberg.org/guix/guix/src/branch/master/gnu/packages/finance.scm
* The `aixcoin` gentoo package is maintained under https://gitlab.com/aixcoin/gentoo
* The [/debian](/debian) packaging is currently unmaintained, see https://github.com/aixcoin-core/packaging/issues/36

An RPM spec file was removed in commit fa7c698cb24bab350b40ee2d825c443dabdd9633, because is was unmaintained and
outdated.
