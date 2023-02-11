# GDB with Python 3.11 for Windows

This distribution of GDB is based on (reasonably) newest development (`master` branch) version.

## Features:
* Support for Python 3.11 (and required!)
* Support for virtualenv for GDB only (Create venv in `<gdb-dir>/venv` directory)
* Relocatable installation - unzip anywhere (note: Python's venv is NOT relocatable)
* Reduced verbosity of startup
* Support for all architectures in single executable
* (Optional) Source highlighting with pygments (install `pygments` package into venv)
* Fixed default auto-load path to support automatically loading `gdbinit` files from `share/gdb/system-gdbinit` directory
