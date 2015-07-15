# Packer Example - CentOS 7 minimal Vagrant Box

**Current CentOS Version Used**: 7.1

This example build configuration installs CentOS 7 x86_64 minimal and generates a Vagrant box file:

  - VirtualBox

## Requirements

The following software must be installed/present on your local machine before you can use Packer to build the Vagrant box file:

  - [Packer](http://www.packer.io/)
  - [Vagrant](http://vagrantup.com/)
  - [VirtualBox](https://www.virtualbox.org/) (if you want to build the VirtualBox box)

## Usage

Make sure all the required software (listed above) is installed, then cd to the directory containing this README.md file, and run:

    $ packer build centos7.json

After a few minutes, Packer should tell you the box was generated successfully.

## License

MIT license.