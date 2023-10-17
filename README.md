# Progen

Progen is a simple tool for linux to generate project skeletons from templates.

## Installation

```bash
git clone https://github.com/Zephied/Progen
cp Progen/progen /usr/bin/progen
```

## Usage

progen [option]
if no option is given, progen will ask you only for the project name and the project language"

### Options

--help: Display help\n
-vs: start visual studio code after project creation

### exit codes
0: success
1: minor error
2: major error
3: if language is not supported
