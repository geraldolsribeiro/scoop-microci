# microCI Scoop Bucket

This repository provides a [Scoop](https://scoop.sh/) bucket for installing
[microCI](https://microci.dev/) on Windows.

## Installation

Open PowerShell and run:

```powershell
scoop bucket add microci https://github.com/geraldolsribeiro/scoop-microci
scoop install microci/microci
```

To refresh the bucket manifest and install or upgrade microCI:

```powershell
scoop update
scoop install microci/microci
```

If microCI is already installed, use `scoop update microci` to update it.
