About scrape-search-engine
==========================

Home: https://github.com/sujitmandal/scrape-search-engine

Package license: MIT

Feedstock license: [BSD-3-Clause](https://github.com/conda-forge/scrape-search-engine-feedstock/blob/master/LICENSE.txt)

Summary: Search anything on the different Search Engine's it will collect all the links.

Development: https://github.com/sujitmandal/scrape-search-engine

Documentation: https://sujitmandal.github.io/scrape-search-engine/

Current build status
====================


<table><tr><td>All platforms:</td>
    <td>
      <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=15290&branchName=master">
        <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/scrape-search-engine-feedstock?branchName=master">
      </a>
    </td>
  </tr>
</table>

Current release info
====================

| Name | Downloads | Version | Platforms |
| --- | --- | --- | --- |
| [![Conda Recipe](https://img.shields.io/badge/recipe-scrape--search--engine-green.svg)](https://anaconda.org/conda-forge/scrape-search-engine) | [![Conda Downloads](https://img.shields.io/conda/dn/conda-forge/scrape-search-engine.svg)](https://anaconda.org/conda-forge/scrape-search-engine) | [![Conda Version](https://img.shields.io/conda/vn/conda-forge/scrape-search-engine.svg)](https://anaconda.org/conda-forge/scrape-search-engine) | [![Conda Platforms](https://img.shields.io/conda/pn/conda-forge/scrape-search-engine.svg)](https://anaconda.org/conda-forge/scrape-search-engine) |

[![Build Status](https://travis-ci.org/sujitmandal/scrape-search-engine.svg?branch=master)](https://travis-ci.org/sujitmandal/scrape-search-engine) [![GitHub license](https://img.shields.io/github/license/sujitmandal/scrape-search-engine)](https://github.com/sujitmandal/scrape-search-engine/blob/master/LICENSE) ![PyPI - Python Version](https://img.shields.io/pypi/pyversions/scrape-search-engine) ![PyPI - Wheel](https://img.shields.io/pypi/wheel/scrape-search-engine) ![PyPI](https://img.shields.io/pypi/v/scrape-search-engine) [![Conda Version](https://img.shields.io/conda/vn/conda-forge/scrape-search-engine.svg)](https://anaconda.org/conda-forge/scrape-search-engine) [![Anaconda-Server Badge](https://anaconda.org/conda-forge/scrape-search-engine/badges/version.svg)](https://anaconda.org/conda-forge/scrape-search-engine) [![Anaconda-Server Badge](https://anaconda.org/conda-forge/scrape-search-engine/badges/installer/conda.svg)](https://conda.anaconda.org/conda-forge) [![Anaconda-Server Badge](https://anaconda.org/conda-forge/scrape-search-engine/badges/platforms.svg)](https://anaconda.org/conda-forge/scrape-search-engine)


Installing scrape-search-engine
===============================

Installing `scrape-search-engine` from the `conda-forge` channel can be achieved by adding `conda-forge` to your channels with:

```
conda config --add channels conda-forge
conda config --set channel_priority strict
```

Once the `conda-forge` channel has been enabled, `scrape-search-engine` can be installed with:

```
conda install scrape-search-engine
```

It is possible to list all of the versions of `scrape-search-engine` available on your platform with:

```
conda search scrape-search-engine --channel conda-forge
```

## How to import the module:
```python
userAgent = ('') #search on google "my user agent"
search = ('')  #Enter Anything for Search
```
## Google Search Engine : 
```python
from ScrapeSearchEngine.ScrapeSearchEngine import Google

google = Google(search, userAgent)

print(google)
```
## Duckduckgo Search Engine : 
```python
from ScrapeSearchEngine.ScrapeSearchEngine import Duckduckgo

duckduckgo = Duckduckgo(search, userAgent)

print(duckduckgo)
```
## Givewater Search Engine : 
```python
from ScrapeSearchEngine.ScrapeSearchEngine import Givewater

givewater = Givewater(search, userAgent)

print(givewater)
```
## Ecosia Search Engine : 
```python
from ScrapeSearchEngine.ScrapeSearchEngine import Ecosia

ecosia = Ecosia(search, userAgent)

print(ecosia)
```
## Bing Search Engine : 
```python
from ScrapeSearchEngine.ScrapeSearchEngine import Bing

bing = Bing(search, userAgent)

print(bing)
```
## Yahoo Search Engine : 
```python
from ScrapeSearchEngine.ScrapeSearchEngine import Yahoo

yahoo = Yahoo(search, userAgent)

print(yahoo)
```
## Scrape Search Engine With Text and Link :

Search anything on the different Search Engine's it will collect all the links with corresponding text.

## Google Search Engine : 
```python
from ScrapeSearchEngine.SearchEngine import Google

googleText, googleLink = Google(search, userAgent)

print(googleText)
print(googleLink)
```
## Duckduckgo Search Engine : 
```python
from ScrapeSearchEngine.SearchEngine import Duckduckgo

duckduckgoText, duckduckgoLink = Duckduckgo(search, userAgent)

print(duckduckgoText)
print(duckduckgoLink)
```
## Givewater Search Engine : 
```python
from ScrapeSearchEngine.SearchEngine import Givewater

givewaterText, givewaterLink = Givewater(search, userAgent)

print(givewaterText)
print(givewaterLink)
```
## Ecosia Search Engine : 
```python
from ScrapeSearchEngine.SearchEngine import Ecosia

ecosiaText, ecosiaLink = Ecosia(search, userAgent)

print(ecosiaText)
print(ecosiaLink)
```
## Bing Search Engine : 
```python
from ScrapeSearchEngine.SearchEngine import Bing

bingText, bingLink = Bing(search, userAgent)

print(bingText)
print(bingLink)
```
## Yahoo Search Engine : 
```python
from ScrapeSearchEngine.SearchEngine import Yahoo

yahooText, yahooLink = Yahoo(search, userAgent)

print(yahooText)
print(yahooLink)
```

About conda-forge
=================

[![Powered by
NumFOCUS](https://img.shields.io/badge/powered%20by-NumFOCUS-orange.svg?style=flat&colorA=E1523D&colorB=007D8A)](https://numfocus.org)

conda-forge is a community-led conda channel of installable packages.
In order to provide high-quality builds, the process has been automated into the
conda-forge GitHub organization. The conda-forge organization contains one repository
for each of the installable packages. Such a repository is known as a *feedstock*.

A feedstock is made up of a conda recipe (the instructions on what and how to build
the package) and the necessary configurations for automatic building using freely
available continuous integration services. Thanks to the awesome service provided by
[CircleCI](https://circleci.com/), [AppVeyor](https://www.appveyor.com/)
and [TravisCI](https://travis-ci.com/) it is possible to build and upload installable
packages to the [conda-forge](https://anaconda.org/conda-forge)
[Anaconda-Cloud](https://anaconda.org/) channel for Linux, Windows and OSX respectively.

To manage the continuous integration and simplify feedstock maintenance
[conda-smithy](https://github.com/conda-forge/conda-smithy) has been developed.
Using the ``conda-forge.yml`` within this repository, it is possible to re-render all of
this feedstock's supporting files (e.g. the CI configuration files) with ``conda smithy rerender``.

For more information please check the [conda-forge documentation](https://conda-forge.org/docs/).

Terminology
===========

**feedstock** - the conda recipe (raw material), supporting scripts and CI configuration.

**conda-smithy** - the tool which helps orchestrate the feedstock.
                   Its primary use is in the construction of the CI ``.yml`` files
                   and simplify the management of *many* feedstocks.

**conda-forge** - the place where the feedstock and smithy live and work to
                  produce the finished article (built conda distributions)


Updating scrape-search-engine-feedstock
=======================================

If you would like to improve the scrape-search-engine recipe or build a new
package version, please fork this repository and submit a PR. Upon submission,
your changes will be run on the appropriate platforms to give the reviewer an
opportunity to confirm that the changes result in a successful build. Once
merged, the recipe will be re-built and uploaded automatically to the
`conda-forge` channel, whereupon the built conda packages will be available for
everybody to install and use from the `conda-forge` channel.
Note that all branches in the conda-forge/scrape-search-engine-feedstock are
immediately built and any created packages are uploaded, so PRs should be based
on branches in forks and branches in the main repository should only be used to
build distinct package versions.

In order to produce a uniquely identifiable distribution:
 * If the version of a package **is not** being increased, please add or increase
   the [``build/number``](https://docs.conda.io/projects/conda-build/en/latest/resources/define-metadata.html#build-number-and-string).
 * If the version of a package **is** being increased, please remember to return
   the [``build/number``](https://docs.conda.io/projects/conda-build/en/latest/resources/define-metadata.html#build-number-and-string)
   back to 0.

Feedstock Maintainers
=====================

* [@sujitmandal](https://github.com/sujitmandal/)

