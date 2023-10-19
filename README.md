# Progen

Progen is a simple tool for linux to generate project skeletons from templates.

## Installation

install the last release on https://github.com/Zephied/Progen/releases
for linux users get the .tar file
```bash
tar -xf Progen-1.0.tar.gz
cp Progen-1.0/progen /bin/progen
```

## Usage

```
progen use sudo to install depedencies
progen [option]
if no option is given, progen will ask you only for the project name and the project language
```

### Options

```
--help: Display help
-vs: start visual studio code after project creation
```

### exit codes

```
0: success

1: minor error

2: major error

3: if language is not supported
```

## Contact

email: nicolas.galmiche@ynov.com

discord id: zephied
