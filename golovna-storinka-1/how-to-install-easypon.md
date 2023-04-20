---
title: How to install EasyPON
slug: UXzo-how-to-install-easypon
createdAt: Tue Feb 28 2023 20:58:10 GMT+0000 (Coordinated Universal Time)
updatedAt: Fri Mar 17 2023 20:39:04 GMT+0000 (Coordinated Universal Time)
---

You can install EasyPON just in a few steps.

1.  Register an account in the EasyPON personal cabinet <https://cabinet.easypon.in/login>

2.  Login to your EasyPON personal cabinet account, and choose the existing license or add a new license instance.

3.  Download the distribution archive of the latest Easypon version from your license.

4.  Install or upgrade EasyPON by using `install_ep.sh` bash script.

> cd /path/to/
>
>
>
> archive
>
> /
>
>
> tar
>
>  \-xf distribution_
>
> archive_name
>
> .tar 
>
> \# extract distribution files
>
>
>
>
> cd epv2/ 
>
> \# 
>
> change active directory to 
>
> epv2 folder
>
>
> apt update && apt upgrade 
>
> \# upgrade system files to the latest version
>
>
> chmod +x install_ep.sh 
>
> \# make the installation script 
>
> executable
>
>
> ./install_ep.sh install # install EasyPON
>
>
> ./install_ep.sh upgrade # upgrade EasyPON
>
>

OS requirements: Debian 11 *bullseye*.
