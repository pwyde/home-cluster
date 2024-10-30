# Talos Patching

This directory contains Kustomization patches that are added to the `talhelper` configuration file.

- [Talos Configuration Patches](https://www.talos.dev/latest/talos-guides/configuration/patching/)
- [`talhelper` Configuration](https://budimanjojo.github.io/talhelper/latest/reference/configuration/)

## Patch Directories

Under this `patches` directory, there are several sub-directories that can contain patches that are added to the talhelper configuration file.
Each directory is optional and might not be applicable.

- `controller/`: Patches that are applied to the controller configurations.
- `global/`: Patches that are applied to both the controller and worker configurations.
- `gpu/`: Patches that are applied to nodes with NVIDIA GPU present.
- `worker/`: Patches that are applied to the worker configurations.
