# nabels-xenial64

This repository is based on the following repository:
- https://github.com/cbednarski/packer-ubuntu

# Purpose

This repository attempts to store the minimum amount of code that is required to create a Ubuntu Xenial64 box using Packer, hosted on Atlas.

# Technologies

## Packer

https://www.packer.io/intro/

Packer is a tool that allows you to create identical machine images using a single definition. 

## Atlas

https://atlas.hashicorp.com/help/intro/getting-started

Atlas is used to host the definition of the machine image we are creating, and the outputs (the actual images), on [nabels/xenial64](https://atlas.hashicorp.com/nabels/boxes/xenial64/).
