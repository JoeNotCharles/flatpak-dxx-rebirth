# flatpak-dxx-rebirth
Flatpak packaging for DXX-Rebirth

This contains the flatpak build manifest file for DXX-Rebirth.

The DXX-Rebirth source code from https://github.com/JoeNotCharles/dxx-rebirth, which is a fork of https://github.com/dxx-rebirth/dxx-rebirth containing minimal changes needed for the flatpak build.

## Cloning

This includes submodules, so clone with `git clone --recursive`. If you've already cloned and the `shared-modules` subdir is empty, use `git submodule update --init` to fetch them.

## Building

To build, use the `flatpak-builder` command as described at https://docs.flatpak.org/en/latest/first-build.html. 
