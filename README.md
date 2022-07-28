# archsrc-unpack
### A tool to unpack an Arch Linux package provided as a source (git package).

## How to install
```shell
> sudo ./install.sh
```

## Usage
```shell
> archsrc-unpack <package_name>.src.tar.gz
Your package has been extracted to <pace_name>-tree
```

## If `/bin/sh` is not a symlink to `/bin/bash`
Make sure that you have bash installed and:
```shell
> bash archsrc-unpack
```

## Examples
### Extract a package from steamos.cloud repository (steamdeck source packages)
```shell
> archsrc-unpack jupiter-hw-support-3.3.20220719.1-1.src.tar.gz
Your package has been extracted to jupiter-hw-support-tree
> ls -lh jupiter-hw-support-tree
drwxr-xr-x 5 user user 47 Jul 28 19:52 etc/
drwxr-xr-x 5 user user 41 Jul 28 19:52 usr/
```
