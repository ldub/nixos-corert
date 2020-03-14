# nixos-corert
Attempting to build and run a CoreRT program on NixOS

Code taken from [dotnet/corert](https://github.com/dotnet/corert/tree/master/samples/HelloWorld) and slightly modified.

## Build Instructions

Ubuntu:
```
sudo apt-get install clang zlib1g-dev libkrb5-dev libtinfo5
nix-shell -p dotnet-sdk
make build
```

Ubuntu without using `apt-get`:
```
TODO
```

NixOS:
```
TODO
```
