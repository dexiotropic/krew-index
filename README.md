# Dexiotropic Krew Index

This repository is a Krew index for Dexiotropic kubectl plugins.

It currently publishes:

- `kenv` for [`kubenv`](https://github.com/dexiotropic/kubenv)

## Use this index

```sh
kubectl krew index add dexiotropic https://github.com/dexiotropic/krew-index
kubectl krew install dexiotropic/kenv
```

If you already added the index and published a new plugin manifest version, refresh and upgrade with:

```sh
kubectl krew update
kubectl krew upgrade kenv
```
