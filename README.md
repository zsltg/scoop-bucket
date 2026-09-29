# zsltg/scoop-bucket

Scoop bucket for the command-line tools of [zsltg](https://github.com/zsltg).

## Install

```powershell
scoop bucket add zsltg https://github.com/zsltg/scoop-bucket
scoop install <name>
```

To upgrade an installed tool to its latest release:

```powershell
scoop update <name>
```

## Manifests

| Name | Description | Architectures |
|---|---|---|
| [iq](https://github.com/zsltg/iq) | jq for NoSQL databases | x64, ARM64 |

The manifests are in `bucket/`. The release workflow of each tool writes its manifest with GoReleaser. Do not edit a manifest by hand, because the next release replaces it.

## Problems

Report a problem in the issue tracker of the tool, not in this repository.
