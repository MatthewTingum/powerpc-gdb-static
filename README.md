# GDB PowerPC (PPC) Static Build

Builds a static `gdb` and `gdbserver` for PowerPC.

## Requirements

- Docker
- [scuba](https://pypi.org/project/scuba/)

## Building

```sh
# Extract and patch sources
scuba sources

# Build gdb
scuba build_gdb

# Build gdbserver
scuba build_gdbserver

# Strip the binaries
scuba strip
```
