# maas-packer
packer image builds for maas

This repo is based on code from [Canonical's packer-maas repo](https://github.com/canonical/packer-maas)

## Building the RKE image for maas

cd to the `packer/ubuntu` directory and run `make`

### Updating image configuration
You can update software installation and image configuration by adding installation steps in the `user-data-cloudimg` file in the `packer/ubuntu` directory.
