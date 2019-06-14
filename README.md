# SmartCore

## Manage dependencies

### pip-tools
Command line tools pip-tools are used to manage project dependencies
https://github.com/jazzband/pip-tools

### Update requirements
File 'requirements.in' contanes project dependencies. Add here new dependencies.
Then execute command:
pip-compile requirements.in
It will generate requirements.txt with actual versions.

### Install requirements
After puling updates with new dependencies execute command:
pip install -r requirements.txt
It will update all dependencies
