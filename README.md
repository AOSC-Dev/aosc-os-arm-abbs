AOSC OS ABBS Tree
=================

*This repo is currently work in progress.*

Here is some copypasta from the [wiki](https://github.com/AOSC-Dev/aosc-os-abbs/wiki/).
It is also available as a submodule called `.githubwiki`.

This is the repository that stores all of AOSC OS build configurations, using [ABBS](https://github.com/AOSC-Dev/abbs) (AutoBuild Build Service). This repository contains configurations of AOSC OS ports to a variety of architectures (x86_64, armel alike).

## Rationale, and the existing issue

For more than three years (from late 2011 to currently season 2 of 2015), AOSC OS has been built with Autobuild - however - without any recording and enforcement of build process. The worst of all, although patches and source modifications are recorded, no source link was provided. This, ironically, raises skepticism from inside of the development team.

### To amend the issue

With this repository, all packages in AOSC OS will be recorded in the new "abbs tree" model that includes source code specs (that includes download link for the source code, and the versions), and unified configurations for various architectural ports.
