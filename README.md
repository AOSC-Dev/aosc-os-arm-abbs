AOSC OS ABBS Tree
=================

The AOSC OS ABBS Tree contains build configurations and scripts
for all packages made available in the official AOSC OS
[repository](https://repo.aosc.io), organised in a tree-like fashion. The "Tree"
is split into three main classes and various sub-categories:

- `core-*` contains components of the [AOSC OS Core](README.CORE.md).
- `base-*` contains tools and libraries for basic system functionalities.
- `extra-*` contains... practically everything else.

Branches
--------

The ABBS Tree is maintained in a multi-branch fashion, for more information,
please refer to the [AOSC OS Maintenance Guidelines](https://wiki.aosc.io/developer/packaging/topic-based-maintenance-guideline).

Groups
------

When using [ACBS](https://github.com/AOSC-Dev/acbs/) (Autobuild CI Build System),
it is possible to build a series of packages with a single command. This is
achieved by the "groups" defined in the `groups/` directory, with files defining
a list of packages to build.

Further Readings
----------------

- [Intro to Package Maintenance](https://wiki.aosc.io/developer/packaging/basics)
- [AOSC OS Package Styling Manual](https://wiki.aosc.io/developer/packaging/package-styling-manual)

Useful Links
------------

- [AOSC OS Packages](https://packages.aosc.io/)
- [AOSC OS Packages, QA Information](https://packages.aosc.io/qa/)
    - [List of Package Issue Codes](https://wiki.aosc.io/developer/packaging/qa-issue-codes)
- [AOSC BuildBot Information](https://wiki.aosc.io/developer/infrastructure/buildbots)

Need Help?
----------

Please report any build-time and run-time issues using our
[issues](https://github.com/AOSC-Dev/aosc-os-abbs/issues/new/choose) page.
