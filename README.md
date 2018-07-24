# termcolor_util

`termcolor_util` is a set of functions on top of termcolor for every single color.

## Installation

```sh
pip install termcolor_util
```

## Functions

```python
def yellow(text: str, bold=False, underline=False) -> str: ...

def green(text: str, bold=False, underline=False) -> str: ...

def blue(text: str, bold=False, underline=False) -> str: ...

def red(text: str, bold=False, underline=False) -> str: ...

def gray(text: str, bold=False, underline=False) -> str: ...

def cyan(text: str, bold=False, underline=False) -> str: ...

def magenta(text: str, bold=False, underline=False) -> str: ...

def white(text: str, bold=False, underline=False) -> str: ...
```

Beside colors, there is a function for directly printing on the stderr.

```python
def eprint(*args) -> None: ...
```
