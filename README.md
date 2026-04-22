# Nix package for FreeCAD

This flake provides a package for FreeCAD, as well as a development shell.

To run the FreeCAD temporarily, you can use the following:

```
# Latest stable
nix run github:FreeCAD/Nix-packaging
# Latest development version
nix run github:FreeCAD/Nix-packaging#FreeCAD-devel
```

To enter the development shell, you can either run `direnv allow` in the
FreeCAD source directory, if you have nix-direnv, or you can run the following:
```
nix develop github:FreeCAD/Nix-packaging
```

## Disclaimer

This flake is still in development and some things may outright be missing.
Keep this flake up to date in your lock file if you are going to use it!

