## Instantiate a CentOS/Fedora VM
This section does not cover the storage configuration, including for the OS images.

1. Make copy of the source image of the OS

2. Modify the copied disk to set up:
   * the hostname
   * a root password
   * a local admin with sudo
   * a SSH-Key injection

3. if a static IP is required:
   * generate a fixed MAC address to use
   * associate a static IP with the MAC and the hostname

