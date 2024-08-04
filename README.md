# pyprojinit

A CLI to initialize a simple Python pyproject.toml file with a simple executable CLI that can launch a web UI.

## Installation

`pip install pyprojinit`

## Usage

Initialize on current Folder:
- `pyprojinti init`

Initialize on target folder: 
- `pyprojinit init --output target_folder/`

## Files created

The CLI will create the following files and folder structure:

```text
<package>/__init__.py
<package>/version.py
<package>/cmd/__init__.py
<package>/cmd/root.py
LICENSE
README
pyproject.toml
setup.py
buid.sh
```
## Sample Output

```text
 pyprojinit init --output myproj1
PyProjInit CLI
Package name [mypackage]: myproject1
Description [My package]: Description for myproject1
Author [Name]: 
Author email [name@email.com]: 
Homepage [https://github/usernane/repo]: 
Comma separated packages (space=None) [click, fastapi, unvicorn[standard]]: 
Creating package myproject1 in folder myproj1 with author Name and email name@email.com
Creating folder myproj1
New project iniatialize at: myproj1
```


## `build.sh`

`build.sh` is a useful bash script to start the build process and deploy the package locally in editable mode.