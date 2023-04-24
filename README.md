# How to install EasyPON

You can install EasyPON just in a few steps.

1. Register an account in the EasyPON personal cabinet [https://cabinet.easypon.in/login](https://cabinet.easypon.in/login)
2. Login to your EasyPON personal cabinet account, and choose the existing license or add a new license instance.
3. Download the distribution archive of the latest Easypon version from your license.
4. Install or upgrade EasyPON by using `install_ep.sh` bash script.

> cd /path/to/
>
> archive
>
> /
>
> tar
>
> \-xf distribution\_
>
> archive\_name
>
> .tar
>
> \# extract distribution files
>
> cd epv2/
>
> \#
>
> change active directory to
>
> epv2 folder
>
> apt update && apt upgrade
>
> \# upgrade system files to the latest version
>
> chmod +x install\_ep.sh
>
> \# make the installation script
>
> executable
>
> ./install\_ep.sh install # install EasyPON
>
> ./install\_ep.sh upgrade # upgrade EasyPON

OS requirements: Debian 11 _bullseye_.
