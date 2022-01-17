# Cuberite

[![Jenkins Build Status](https://img.shields.io/jenkins/build?jobUrl=https%3A%2F%2Fbuilds.cuberite.org%2Fjob%2Fcuberite%2Fjob%2Fmaster&label=Jenkins)](https://builds.cuberite.org/job/cuberite/job/master/)
[![AppVeyor Build Status](https://img.shields.io/appveyor/ci/cuberite/cuberite/master.svg?label=AppVeyor)](https://ci.appveyor.com/project/cuberite/cuberite)

Cuberite is a Minecraft-compatible multiplayer game server that is written in C++ and designed to be efficient with memory and CPU, as well as having a flexible Lua Plugin API. Cuberite is compatible with the Java Edition Minecraft client.

Cuberite runs on Windows, *nix and Android operating systems. This includes Android phones and tablets as well as Raspberry Pis.

Currently we support Release 1.8 - 1.12.2 Minecraft protocol versions.

Subscribe to [the newsletter][1] for important updates and project news.

## Installation

There are several ways to obtain Cuberite.

### Binaries

- The easiest method is downloading for Windows or Linux from the [website][2].
- You can use the EasyInstall script for Linux and macOS, which automatically downloads the correct binary. The script is described below.

#### The EasyInstall script

This script will download the correct binary from the project site.

    curl -sSfL https://download.cuberite.org | sh

### Compiling

- You can compile automatically for Linux, macOS and FreeBSD with the `compile.sh` script. The script is described below.
- You can also compile manually. See [COMPILING.md][4].

Compiling may provide better performance (1.5-3x as fast) and it supports more operating systems.

#### The compile.sh script

This script downloads the source code and compiles it. The script is smart enough to notify you of missing dependencies and instructing you on how to install them. The script doesn't work for Windows.

Using curl:

    sh -c "$(curl -sSfL -o - https://compile.cuberite.org)"

Or using wget:

    sh -c "$(wget -O - https://compile.cuberite.org)"

### Hosted services

- Hosted Cuberite is available via [Gamocosm][5].

## Contact

You may fin 

