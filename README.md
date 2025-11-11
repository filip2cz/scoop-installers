# Scoop Bucket Template

<!-- Uncomment the following line after replacing placeholders -->
[![Tests](https://github.com/<username>/<bucketname>/actions/workflows/ci.yml/badge.svg)](https://github.com/<username>/<bucketname>/actions/workflows/ci.yml) [![Excavator](https://github.com/<username>/<bucketname>/actions/workflows/excavator.yml/badge.svg)](https://github.com/<username>/<bucketname>/actions/workflows/excavator.yml)

Bucket with manifest that acts basically same way as winget - just download latest installation package and run it. Nothing more.

## Why? Winget already exists

I just do not like winget, it tries to manage apps that were not installed by it, etc. If you find winget better for you, just use winget. But if you have same opinion as me, maybe this suits you better.

## How do I install these manifests?

After manifests have been committed and pushed, run the following:

```pwsh
scoop bucket add filip2cz_scoop-installers https://github.com/filip2cz/scoop-installers
scoop install filip2cz_scoop-installers/<manifestname>
```

## How do I contribute new manifests?

To make a new manifest contribution, please read the [Contributing
Guide](https://github.com/ScoopInstaller/.github/blob/main/.github/CONTRIBUTING.md)
and [App Manifests](https://github.com/ScoopInstaller/Scoop/wiki/App-Manifests)
wiki page.
