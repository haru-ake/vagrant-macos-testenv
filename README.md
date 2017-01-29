# vagrant-macos-testenv

Vagrantfile for macOS testenv

## Building the macOS box

Use [boxcutter](https://github.com/boxcutter/macos) macOS's Packer template.

## How to use

```
$ vagrant box add macos1012 <BOXCUTTER_ROOT>/box/virtualbox/<BOX_FILE>
$ git clone https://github.com/haru-ake/vagrant-macos-testenv.git
$ cd ./vagrant-macos-testenv
$ vagrant up
```
