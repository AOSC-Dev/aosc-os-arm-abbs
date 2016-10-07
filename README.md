AOSC OS ABBS Tree
=================

Here is some copypasta from the [wiki](https://github.com/AOSC-Dev/aosc-os-abbs/wiki/).
It is also available as a submodule called `.githubwiki`.

This is the repository that stores all of AOSC OS build configurations, using [ABBS](https://github.com/AOSC-Dev/abbs) (AutoBuild Build Service). This repository contains configurations of AOSC OS ports to a variety of architectures (x86_64, armel alike).

## Rationale, and the existing issue

For more than three years (from late 2011 to currently season 2 of 2015), AOSC OS has been built with Autobuild - however - without any recording and enforcement of build process. The worst of all, although patches and source modifications are recorded, no source link was provided. And consequently raises skepticism from our users and inside of the development team.

### To amend the issue

With this repository, all packages in AOSC OS will be recorded in the new "abbs tree" model that includes source code specs (that includes download link for the source code, and the versions), and unified configurations for various architectural ports.

## Tips to new comers

* Read the wiki please!
* Always push commits to the `staging` branch, the `master` branch is only for tested commits with fixes (where necessary) from the `staging` branch, more in the wiki (again).
* Non AOSC-Dev members are also welcome to open PRs (pull requests) for this tree, but to the `staging` branch only.
* If your network condition is poor or you want to clone this huge repository quicker, please consider using our git bundles, see [here](https://aosc.io/news/aosc-os-abbs-repository-snapshots-migrated-to-git-bundles-2) for more information. 
