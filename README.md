[![tests](https://github.com/Metadrop/ddev-newman/actions/workflows/tests.yml/badge.svg)](https://github.com/Metadrop/ddev-newman/actions/workflows/tests.yml) ![project is maintained](https://img.shields.io/maintenance/yes/2024.svg)
![GitHub Release](https://img.shields.io/github/v/release/Metadrop/ddev-newman)


# DDEV newman

Allows running [newman](https://www.npmjs.com/package/newman) on ddev setups. Use it to run postman tests through CLI.

## Installation

For DDEV v1.23.5 or above run

```sh
ddev add-on get metadrop/ddev-newman
```

For earlier versions of DDEV run

```sh
ddev get metadrop/ddev-newman
```

## Usage

```sh
ddev newman [args]
```

Example:

```sh
ddev newman my_collection.json -e environment.json
```

To view all the possible command line options, please [check the documentation](https://www.npmjs.com/package/newman#command-line-options).
