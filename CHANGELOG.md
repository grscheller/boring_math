# CHANGELOG: grscheller-python-libs

Will become CHANGELOG for grscheller.boring_math

## Overview

* Single Maintainer PyPI Package
* Rolling Release Model
  * maintained on GitHub, software is an Alpha release 
  * maintainer will not back port bug fixes to previous versions
  * main branch will be the release branch
    * will either be the current PyPI release, or
    * will be the release canidate for the next PyPI release
    * PyPI releases are tagged with a leading "v" on GitHub
  * devel branch will be the only software development tracking branch
    * will attempt to keep relatively stable, but
    * may not be fully tested
  * feature branches begin with "feature_" and are places to
    * explore new directions
    * commit potentially very broken code
    * could be deleted from GitHub anytime WITHOUT WARNING
* Semantic versioning for PyPI releases:
  * first digit signifies a major event, epoch, or paradigm shift
  * second digit means
    * breaking API changes
    * major changes
  * third digit either means
    * API additions
    * bugfixes or minor changes
    * documentation updates
  * forth digit (develoment branches only)
    * commit count
    * development environment thrashing
    * not to be taken too seriously

## Version - PyPI releases begin with "v"

### Version 0.0.0.1 - commit date 2023-12-06

* First non-trivial commit
* 
