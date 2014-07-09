ghcjs-tools-debian
==================

This repository contains debian packaging to build the ghcjs library,
compiler, and associated tools.  Drop a copy of the debian directory
into a checked out copy of https://github.com/ghcjs/ghcjs.git and run
dpkg-buildpackage.  The resulting ghcjs-tools package can then be used
as a build dependency for the package at
https://github.com/ddssff/ghcjs-debian.
