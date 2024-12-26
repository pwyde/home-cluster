# Talos Patching

The `talos/patches` directory contains Kustomization patches that are added to the `talhelper` configuration file.

- [Talos Configuration Patches](https://www.talos.dev/latest/talos-guides/configuration/patching/)
- [`talhelper` Configuration](https://budimanjojo.github.io/talhelper/latest/reference/configuration/)

## Patch Directories

Inside the `talos/patches` directory, there are several sub-directories that can contain patches that are added to the talhelper configuration file.

Each directory is optional and might not be applicable.

- `talos/controller/`: Patches that are applied to the controller configurations.
- `talos/global/`: Patches that are applied to both the controller and worker configurations.
- `talos/gpu/`: Patches that are applied to nodes with NVIDIA GPU present.
- `talos/worker/`: Patches that are applied to the worker configurations.
