# Default 1x1 land in Metropolis City Island

This repository provides the default land content
and can be used as a template to customize your own land.

## Prerequisites

- [Git Annex][git-annex]
- [Git LFS][git-lfs]
- [IPFS][ipfs-install]
- [Unity][unity-dl]

## Build

To open the project, follow these steps:

1. Clone Git repository recursively (with all submodules):

       git clone --recursive https://github.com/Ecilos/ecilos-land-1x1-at-island-metropolis.git

1. Configure Git Annex to use IPFS as special remote store:

       git annex enableremote ipfs

1, Download required assets from IPFS storage:

       git annex copy --from ipfs

1. In _Unity Hub_, _Add project from disk_ and select cloned repository.
1. Open the project.

## Contributing

Before contributing, please read: [CONTRIBUTING.md](CONTRIBUTING.md).

<!-- Named links -->
[git-annex]: https://git-annex.branchable.com/
[git-lfs]: https://docs.github.com/en/repositories/working-with-files/managing-large-files/installing-git-large-file-storage
[ipfs-install]: https://docs.ipfs.tech/install/
[unity-dl]: https://unity.com/download
