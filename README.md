Packer configuration to build a Rapsberry Pi image for an OARC packet node.

## Build

Build through Github Actions or

    sudo packer build raspbian.pkr.hcl

## Basis

This configuration is based upon the LinBPQ instructions at https://wiki.oarc.uk/packet-linbpq
and implemented in packer utilising the tutorial at
https://linuxhit.com/build-a-raspberry-pi-image-packer-packer-builder-arm/
