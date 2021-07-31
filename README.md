# Flavortext

[![GitHub issues](https://img.shields.io/github/issues/larryare/flavortext)](https://github.com/larryare/flavortext/issues)
[![GitHub license](https://img.shields.io/github/license/larryare/flavortext)](https://github.com/larryare/flavortext/blob/master/LICENSE)
![](https://img.shields.io/badge/Version-1.0-success)

Converted Voidstar lab's C++ code into python.

Usable standalone or as module.

## Demo

#### Constructors
![Constructors](https://media.giphy.com/media/fw7DiDjcoc7rEeQh8A/giphy.gif)
#### Destructors
![Destructor](https://media.giphy.com/media/bzW0XrF2G1fLe1of0Q/giphy.gif)

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