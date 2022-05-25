# ledger-workspace

Workspace for ledger development

## Setup workspace

Setup submodules
```
git submodule init
git submodule update
```

## Build app

Build docker image
```
task docker-build
```

* [Build documentation](https://developers.ledger.com/docs/nano-app/build/#21-get-the-ledger-boilerplate-application)

## Speculos - Ledger emulator

* [Speculos setup documentation](https://developers.ledger.com/docs/speculos/installation/build/)
* [WSL X11 setup](https://docs.microsoft.com/fr-fr/windows/wsl/tutorials/gui-apps)

Build
```
task speculos-make
```

Run elf app
```
task speculos-run
```