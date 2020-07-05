# GNU GCC Toolchain

Bleeding edge GNU GCC toolchains built from sources with latest binutils and glibc.

## Getting the toolchain

Clone using git 
```
$ git clone https://github.com/theradcolor/aarch64-linux-gnu -b <branch-name> --depth=1
```

where branches
- aarch64-linux-gnu-10.1.0

For ARM, checkout https://github.com/theradcolor/arm-linux-gnueabi.git

## Using the toolchain

Export the `CROSS_COMPILE` in enviroment

```
$ export CROSS_COMPILE=<toolchain-path>/bin/aarch64-linux-gnu-
```

## License

GCC is licensed under version 3 of the [GNU General Public License.](https://www.gnu.org/licenses/gpl-3.0.html)
The GCC runtime exception permits compilation of proprietary and free software programs with GCC and usage of free software plugins. The availability of this exception does not imply any general presumption that third-party software is unaffected by the copyleft requirements of the license of GCC. 