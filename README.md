# Check pip install

The script [`check_pip_install.py`](check_pip_install.py) checks
candidates for the [`pip
install`](https://pip.pypa.io/en/stable/reference/pip_install/)
command.

Use:

    $ python check_pip_install.py [options] <requirement specifier>

`<requirement specifier>` is a Python package (aka PyPI *project*)
with optional version specifier.

`[options]` are options that apply to `pip install`. For help with
available options, run `pip install --help`.

This script prints the following information to stdout:

- Specified requirements specifier
- System info
- Valid tags (used to select candidates)
- Skipped candidates (those that did not match valid tags)
- All selected candidates
- Applicable candidates (matching requirement version specifier)
- Best candidate (the candidate that will be selected by pip for
  install)

## License

```
This is free and unencumbered software released into the public domain.

Anyone is free to copy, modify, publish, use, compile, sell, or
distribute this software, either in source code form or as a compiled
binary, for any purpose, commercial or non-commercial, and by any
means.

In jurisdictions that recognize copyright laws, the author or authors
of this software dedicate any and all copyright interest in the
software to the public domain. We make this dedication for the benefit
of the public at large and to the detriment of our heirs and
successors. We intend this dedication to be an overt act of
relinquishment in perpetuity of all present and future rights to this
software under copyright law.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.
IN NO EVENT SHALL THE AUTHORS BE LIABLE FOR ANY CLAIM, DAMAGES OR
OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE,
ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR
OTHER DEALINGS IN THE SOFTWARE.

For more information, please refer to <http://unlicense.org/>
```
