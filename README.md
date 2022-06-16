
## bioc-api-package

This repository contains a _very minimal_ package with it a single piece of
funtionality: to provide the (virtual) package tag `r-api-bioc-3.14`.  

Once installed, it provides this tag so that Debian / Ubuntu packages with a
dependency on it can be installed, see [issue #11 in the r2u
repo](https://github.com/eddelbuettel/r2u/issues/11) for some context and
usage.

## Status

Highly unofficial and transient <grin> existing only for the demo use in
[issue #11](https://github.com/eddelbuettel/r2u/issues/11)

## Use

Check out the repo and run `dpkg-buildpackage -us -uc -tc -rfakeroot` as a
user, or omit `-rfakeroot` and run as root. You may have to create a source
tarball first.

## Author

Dirk Eddelbuettel

## Licence

GPL (>= 2)
