About r-rgdal
=============

Home: http://www.gdal.org, https://r-forge.r-project.org/projects/rgdal/

Package license: GPL (>= 2)

Feedstock license: BSD 3-Clause

Summary: Provides bindings to Frank Warmerdam's Geospatial Data Abstraction Library (GDAL) (>= 1.6.3) and access to projection/transformation operations from the PROJ.4 library. The GDAL and PROJ.4 libraries are external to the package, and, when installing the package from source, must be correctly installed first. Both GDAL raster and OGR vector map data can be imported into R, and GDAL raster data and OGR vector data exported. Use is made of classes defined in the sp package. Windows and Mac Intel OS X binaries (including GDAL, PROJ.4 and Expat) are provided on CRAN. 



Current build status
====================

Linux: [![Circle CI](https://circleci.com/gh/conda-forge/r-rgdal-feedstock.svg?style=shield)](https://circleci.com/gh/conda-forge/r-rgdal-feedstock)
OSX: [![TravisCI](https://travis-ci.org/conda-forge/r-rgdal-feedstock.svg?branch=master)](https://travis-ci.org/conda-forge/r-rgdal-feedstock)
Windows: [![AppVeyor](https://ci.appveyor.com/api/projects/status/github/conda-forge/r-rgdal-feedstock?svg=True)](https://ci.appveyor.com/project/conda-forge/r-rgdal-feedstock/branch/master)

Current release info
====================
Version: [![Anaconda-Server Badge](https://anaconda.org/nomr/r-rgdal/badges/version.svg)](https://anaconda.org/nomr/r-rgdal)
Downloads: [![Anaconda-Server Badge](https://anaconda.org/nomr/r-rgdal/badges/downloads.svg)](https://anaconda.org/nomr/r-rgdal)

Installing r-rgdal
==================

Installing `r-rgdal` from the `nomr` channel can be achieved by adding `nomr` to your channels with:

```
conda config --add channels nomr
```

Once the `nomr` channel has been enabled, `r-rgdal` can be installed with:

```
conda install r-rgdal
```

It is possible to list all of the versions of `r-rgdal` available on your platform with:

```
conda search r-rgdal --channel nomr
```




Updating r-rgdal-feedstock
==========================

If you would like to improve the r-rgdal recipe or build a new
package version, please fork this repository and submit a PR. Upon submission,
your changes will be run on the appropriate platforms to give the reviewer an
opportunity to confirm that the changes result in a successful build. Once
merged, the recipe will be re-built and uploaded automatically to the
`nomr` channel, whereupon the built conda packages will be available for
everybody to install and use from the `nomr` channel.
Note that all branches in the conda-forge/r-rgdal-feedstock are
immediately built and any created packages are uploaded, so PRs should be based
on branches in forks and branches in the main repository should only be used to
build distinct package versions.

In order to produce a uniquely identifiable distribution:
 * If the version of a package **is not** being increased, please add or increase
   the [``build/number``](http://conda.pydata.org/docs/building/meta-yaml.html#build-number-and-string).
 * If the version of a package **is** being increased, please remember to return
   the [``build/number``](http://conda.pydata.org/docs/building/meta-yaml.html#build-number-and-string)
   back to 0.
