## General Usage

To obtain the base image (if you don't have it) and start the VM, do:

      vagrant up

You can then connect to the box via:

      vagrant ssh

Once inside, you should test your Docker installation with:

      docker run hello-world

If there is an error about the Docker daemon, a restart will resolve it:

      sudo reboot now
