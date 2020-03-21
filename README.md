# abi2csv [![License](https://img.shields.io/badge/license-ISC-blue.svg)](/LICENSE)

**abi2csv** is a base caller which converts electrophoregram raw data in the ABIF format to reusable sequences in CSV format.

## Current Status

abi2csv is only at very first developement step, but it can already be used — just don't trust its output too much.

## Compilation

Run `poetry build` in your working copy.

## Usage

```
Usage: abi2csv <input.ab1> > output.csv

Arguments:
    input.ab1 raw electrophoregram data in the ABIF format
```

## Contributing and reporting bugs

Contributions are welcome through [GitHub pull requests](https://github.com/Arkanosis/abi2csv/pulls).

Please report bugs and feature requests on [GitHub issues](https://github.com/Arkanosis/abi2csv/issues).

## License

abi2csv is copyright (C) 2020 Jérémie Roquet <jroquet@arkanosis.net> and licensed under the ISC license.
