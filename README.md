# Flavortext

Converted Voidstar lab's C++ code into python.

Usable standalone or as module.

## Usage

### Command line
```sh
usage: flavortext.py [-h] [--slow [SLOW]] [--endless [ENDLESS]] [construct]

Print flavortext.

positional arguments:
  construct            True for constructors or False for destructors (default: True)

optional arguments:
  -h, --help           show this help message and exit
  --slow [SLOW]        Simulate typing
  --endless [ENDLESS]  Endless typing, stop with Ctrl+C
```

### As module

```py
import flavortext

print(flavortext.get_flavor_list(False, 5))
```
or
```py
import flavortext

print(flavortext.get_full_line(False))
```