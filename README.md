Aix Core packaging
=======

Aix Core is packaged and distributed through different channels.

Advanced users can compile Aix Core from source. Static binaries for Linux, as well as installers for Windows and macOS are
provided on the [website](https://aixcore.org/en/download/).

Aix Core is also distributed on several Linux package managers:

* The `aix-core` snap package for https://snapcraft.io/aix-core is maintained in [/snap](/snap)
* The `org.aixcore.aix-qt` flatpak package is maintained under their organization: https://github.com/flathub/org.aixcore.aix-qt
* The `aix-core` guix package is maintained under https://codeberg.org/guix/guix/src/branch/master/gnu/packages/finance.scm
* The `aix` gentoo package is maintained under https://gitlab.com/aix/gentoo
* The [/debian](/debian) packaging is currently unmaintained, see https://github.com/aix-core/packaging/issues/36

An RPM spec file was removed in commit fa7c698cb24bab350b40ee2d825c443dabdd9633, because is was unmaintained and
outdated.
