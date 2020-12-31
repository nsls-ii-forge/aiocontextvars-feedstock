About aiocontextvars
====================

Home: https://github.com/fantix/aiocontextvars

Package license: MIT

Feedstock license: [BSD-3-Clause](https://github.com/nsls-ii-forge/aiocontextvars-feedstock/blob/master/LICENSE.txt)

Summary: Asyncio support for PEP-567 contextvars backport

Current build status
====================


<table><tr><td>All platforms:</td>
    <td>
      <a href="https://dev.azure.com/nsls2forge/nsls2forge/_build/latest?definitionId=272&branchName=master">
        <img src="https://dev.azure.com/nsls2forge/nsls2forge/_apis/build/status/aiocontextvars-feedstock?branchName=master">
      </a>
    </td>
  </tr>
</table>

Current release info
====================

| Name | Downloads | Version | Platforms |
| --- | --- | --- | --- |
| [![Conda Recipe](https://img.shields.io/badge/recipe-aiocontextvars-green.svg)](https://anaconda.org/nsls2forge/aiocontextvars) | [![Conda Downloads](https://img.shields.io/conda/dn/nsls2forge/aiocontextvars.svg)](https://anaconda.org/nsls2forge/aiocontextvars) | [![Conda Version](https://img.shields.io/conda/vn/nsls2forge/aiocontextvars.svg)](https://anaconda.org/nsls2forge/aiocontextvars) | [![Conda Platforms](https://img.shields.io/conda/pn/nsls2forge/aiocontextvars.svg)](https://anaconda.org/nsls2forge/aiocontextvars) |

Installing aiocontextvars
=========================

Installing `aiocontextvars` from the `nsls2forge` channel can be achieved by adding `nsls2forge` to your channels with:

```
conda config --add channels nsls2forge
```

Once the `nsls2forge` channel has been enabled, `aiocontextvars` can be installed with:

```
conda install aiocontextvars
```

It is possible to list all of the versions of `aiocontextvars` available on your platform with:

```
conda search aiocontextvars --channel nsls2forge
```




Updating aiocontextvars-feedstock
=================================

If you would like to improve the aiocontextvars recipe or build a new
package version, please fork this repository and submit a PR. Upon submission,
your changes will be run on the appropriate platforms to give the reviewer an
opportunity to confirm that the changes result in a successful build. Once
merged, the recipe will be re-built and uploaded automatically to the
`nsls2forge` channel, whereupon the built conda packages will be available for
everybody to install and use from the `nsls2forge` channel.
Note that all branches in the nsls-ii-forge/aiocontextvars-feedstock are
immediately built and any created packages are uploaded, so PRs should be based
on branches in forks and branches in the main repository should only be used to
build distinct package versions.

In order to produce a uniquely identifiable distribution:
 * If the version of a package **is not** being increased, please add or increase
   the [``build/number``](https://conda.io/docs/user-guide/tasks/build-packages/define-metadata.html#build-number-and-string).
 * If the version of a package **is** being increased, please remember to return
   the [``build/number``](https://conda.io/docs/user-guide/tasks/build-packages/define-metadata.html#build-number-and-string)
   back to 0.

Feedstock Maintainers
=====================


