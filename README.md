### MUXCBS

A simple project which demonstrates on how to use the WinUI CBS package that's built into every Windows 11 installation

## Background
Every Windows 11 installation contains a WinUI2 CBS package at (%SYSTEMROOT%\SystemApps\Microsoft.UI.Xaml.CBS_8wekyb3d8bbwe).

This package is used by the Windows Shell to style it with the modern WinUI styles instead of the default Windows 10 era styles provided by Windows.UI.Xaml.

This project showcases on how every app can utilize it, because why not.
It also allows for a dependency free deployment, as everything your app needs is already included.

## Limiations:
You currently cannot cross compile to another architecture, you need to aquire the files for arm32, arm64 or x86(32-bit) yourself
