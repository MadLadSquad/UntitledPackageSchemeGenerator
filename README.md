# UntitledPackageSchemeGenerator
[![MIT license](https://img.shields.io/badge/License-MIT-blue.svg)](https://lbesson.mit-license.org/)
[![trello](https://img.shields.io/badge/Trello-UDE-blue])](https://trello.com/b/HmfuRY2K/untitleddesktop)
[![Discord](https://img.shields.io/discord/717037253292982315.svg?label=&logo=discord&logoColor=ffffff&color=7389D8&labelColor=6A7EC2)](https://discord.gg/4wgH8ZE)

> WARNING: This application is work in progress, if you're seeing this you're seeing the first commits
that don't function entirely. If you want to contribute open an issue and we can discuss how to start development together
as currently we don't have any platform, only documentation

An application, which uses common installation information for deployment of applications to different package managers

Supported package formats are:
1. DEBs 🚧
1. Ebuilds for Gentoo and Funtoo(includes an autogen script) 🚧
1. Pacman pkgbuilds 🚧
1. Void templates 🚧 
1. Flatpaks 🚧
1. RPMs 🚧
1. Winget 🚧

Outside of the format we also use some other tooling to provide many useful features such as:
1. A system to automatically find dependencies for your distribution using the [repology API](https://repology.org/)
1. When used on Linux, we enable you to test if the package formats work by using containers powered by 
[LXD](https://linuxcontainers.org/lxd/introduction/). On Windows, [WSL](https://en.wikipedia.org/wiki/Windows_Subsystem_for_Linux) is used to test 
Linux packages
1. We're CI/CD friendly and fully support templating in our files. Using these templates you can automate your deployment without having to hardcode
versions, tarball URLs, releases and more
1. We use standard naming for our packages so that they can instantly be deployed and indexed by automatic package updaters

## Installation and usage
Instructions on how to use the software, as well as documentation can be found on the 
[wiki](https://github.com/MadLadSquad/UntitledPackageSchemeGenerator/wiki)
