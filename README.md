# systemd
container service

1. build an container image using Dockerfile name of image should be rhelimg
   use the link to download dockerfile  https://github.com/kunalc881/systemd


2.  create a container service from an image rhelimg
    configure the container with systemd service by an existing user "openshift"
    service name should be "myunnati-service" , and configure it to start automically across reboot
    attach /mnt/incoming directory as a volume to container's redhat/test/input
    and /mnt/outgoing directory as  a volume to container's /access/system directory
