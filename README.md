# Electronic Health Record

## Summary

This repo uses git submodules to manage several different microservices that comprise the functionality of an EHR.

## Useful commands

### Adding an additional submodule using an existing repo

```console
git submodule add https://github.com/J0hnG4lt/patient
```

### Working with this repo when it has been first cloned

```console
git submodule init
git submodule update
```

### Checking for new work in submodules

```console
git submodule update --remote patient
```

## Sources

1. [Docker docs](https://docs.docker.com/get-started/)