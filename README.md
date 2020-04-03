# Univeristy of Illinois SecOps-Tools Repo VS Code Settings
VS Code Settings for University of Illinois SecOps-Tools Repo

## What It's For
University of Illinois' SecOps-Tools repo uses Docker to spin up a container / image for one of its legacy python
environments. Using VS Code, it is possible to [develop inside a Docker container.](https://code.visualstudio.com/docs/remote/containers)
The .json files in this repo are for configuring VS Code in a specific way.

### settings.json
Contains settings for python linting, including ignoring specific [Flake8 rules.](https://lintlyci.github.io/Flake8Rules/)

### launch.json
Contains debug configuration settings including explicit CLI arguments for specific SecOps scripts.
