# whiteheap.github.io

This repository serves [residue](https://github.com/whiteheap/residue-cli)'s signed apt, dnf and pacman repositories at `https://whiteheap.github.io/residue/`, the address every install of them uses.

residue-cli's `packages` workflow publishes `residue/` here for each release. Do not edit it by hand: the workflow replaces the folder, and clients check every file against residue's signing key.

GitHub Pages serves the repository named `whiteheap.github.io` at the root of `whiteheap.github.io`, and a project's own Pages site at `whiteheap.github.io/<repository>/`. So `residue/` keeps its address whatever the project's repository is called.
