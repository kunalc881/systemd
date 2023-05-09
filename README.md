# systemd
container service

create a container mysystemd from an image rhelimg
configure the container with systemd service by an existing user "openshift"
service name should be "myunnati-service" , and configure it to start automically across reboot
attach /mnt/incoming directory as a volume to container's redhat/test/input
and /mnt/outgoing directory as  a volume to container's /access/system directory
