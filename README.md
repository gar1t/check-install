# Check pip install

The script [`check_pip_install.py`](check_pip_install.py) checks
candidates for the [`pip
install`](https://pip.pypa.io/en/stable/reference/pip_install/)
command.

Use:

    $ python check_pip_install.py [options] <requirement specifier>

where `<requirement specifier>` is a Python package (aka PyPI
*project*) with optional version specifier.

This script prints the following information to stdout:

- Specified requirements specifier
- System info
- Valid tags (used to select candidates)
- Skipped candidates (those that did not match valid tags)
- All selected candidates
- Applicable candidates (matching requirement version specifier)
- Best candidate (the candidate that will be selected by pip for
  install)
