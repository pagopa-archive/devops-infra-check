# devops-webapp-python

## Special thanks

This project born from the fantastic tutorial created by the Biella python group.

<https://github.com/PythonBiellaGroup/FastCash>

## Goal

Have a simple api that can be use inside the ci/cd of PagoPa and allow test of ours infra.

## Build & Visual Studio code

### Pre-requisites

Install Poetry in you machine, for example using `brew`

### Steps

On root folder

1. run `poetry install`

2. run `poetry shell` to active the venv. You can see as result this snippet

```sh
❯ poetry shell
Configuration file exists at /Users/diego/Library/Application Support/pypoetry, reusing this directory.

Consider moving configuration to /Users/diego/Library/Preferences/pypoetry, as support for the legacy directory will be removed in an upcoming release.
Skipping virtualenv creation, as specified in config file.
Virtual environment already activated: /usr/local/Cellar/poetry/1.3.2/libexec
```

In visual studio code, open the `Python: select the interpreter`-> `enter interpreter path` and add the path showed into the terminal, in this way visual studio code can load the venv
