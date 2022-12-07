# crcnsget

Command-line interface for downloading data from crcns.org


- Free software: BSD license
- Documentation: https://crcnsget.readthedocs.io.

## Installation

To install crcnsget, run this command in your terminal:

```sh
  $ pip install crcnsget
```

## Usage

crcnsget is a command-line utility to enable downloading datasets from crcnr.org

First, make sure you are have an account at at crcns.org. If you do not, you can request one https://crcns.org/request-account/fg_base_view_p3.

```sh
  $ crcnsget --username <username> --dataset <path to dataset>
```

crcnsget will then prompt for your password.

For example,

```sh
  $ crcnsget --username crcnsget --dataset alm-1/datafiles/data_structure_files/data_structure_ANM218457.tar.gz
```

Will download the from the `data_structure_ANM218457.tar.gz` file from the `alm-1` dataset.

## Credits

This package was created with Cookiecutter_ and the `audreyr/cookiecutter-pypackage`_ project template.

[Cookiecutter](https://github.com/audreyr/cookiecutter)
[`audreyr/cookiecutter-pypackage`](https://github.com/audreyr/cookiecutter-pypackage)

