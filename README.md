# z-pyenv-alias

Rename a pyenv version when `pyenv install` it.

## Installation
Installing as a pyenv plugin

```
$ git clone https://github.com/ladyrick/z-pyenv-alias.git "$(pyenv root)/plugins/z-pyenv-alias"
```

## usage
```
$ VERSION_ALIAS=alias_name pyenv install 3.11.3
```

then `pyenv versions` will get

```
* system (set by xxx)
  alias_name
```
