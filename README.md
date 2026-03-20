# AIS Minecraft

Declarative configuration for a simple Minecraft server setup utilizing a [Flux CD](https://fluxcd.io/) GitOps pipeline deploying a Helm release of [itzg/minecraft-server-charts](https://github.com/itzg/minecraft-server-charts) into a Kubernetes cluster for simple containerized setup of a Minecraft server.

## GitOps: Flux CD

This repository can be used as a template for a modular include in a multi-repo Flux setup. Similar to how this repo is an external extension of the primary [Flux Fleet](https://github.com/Constellera/flux-fleet) management of the Constellera Project.

## Whitelist

The whitelist is included as a separate configuration for easy inclusion via PR.

