# docker-tutorial
A tutorial about docker and docker-compose.

### Presentations
* 04/23/2019 - Texas State University EXE

## Setup
1. [Download and install `vagrant`](https://www.vagrantup.com/downloads.html)
   a. Windows Users - You'll need to reboot after this step.
2. [Download and install `VirtualBox`](https://www.virtualbox.org/wiki/Downloads)
   a. Windows Users - If you have HyperV installed you will need to uninstall it while we do the demo.
3. Clone this repository
4. `cd` into this directory and run `vagrant up` from the command line
5. After the vm is up and provisioned, run `vagrant ssh`
6. Once in the machine run `docker run hello-world` to confirm `docker` works
7. Run `docker-compose` to make sure the command is installed properly

## Troubleshooting
If your machine complains about **This kernel requires an x86-64 CPU, but only detected an i686 CPU** you may need to enable virtualization in your bios https://askubuntu.com/questions/41550/how-do-i-run-a-64-bit-guest-in-virtualbox. To fix this:
1. Reboot your machine and boot into the bios (usually a function key hold at a logo screen)
2. Search your CPU configuration for something around virtualization. It is probably disabled. Enable it
3. Continue booting as normal.

## Tutorial
We're going to walk through `docker`. What it is, how to use it, etc. Then 
we'll do the tutorial [here](https://docs.docker.com/compose/gettingstarted/)
