# pyprojinit

A CLI to initialize a simple Python pyproject.toml file with a simple executable CLI that can launch a web UI.

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
## `build.sh`

`build.sh` is a useful bash script to start the build process and deploy the package locally in editable mode.