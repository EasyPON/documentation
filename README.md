# 1⃣ How to install EasyPON

<details>

<summary>OS requirements:</summary>

OS: Debian 11

RAM: 4GB

Storage: 30GB

</details>

### Demo

[https://demo.easypon.in/login](https://demo.easypon.in/login)

Login: demo Password: epdemo12

### You can install EasyPON just in a few steps.

1. Register an account in the EasyPON personal cabinet [https://cabinet.easypon.in/login](https://cabinet.easypon.in/login)
2. Login to your EasyPON personal cabinet account, and choose the existing license or add a new license instance.
3. Download the distribution archive of the latest Easypon version from your license.
4. Install or upgrade EasyPON To install EasyPon, run the following command in your terminal:

> apt update && apt install curl -y bash <(curl -k
>
> [https://cabinet.easypon.in/install\_ep.sh](https://cabinet.easypon.in/install\_ep.sh)
>
> ) install

The installation process will prompt you for various configuration options, such as your domain name and login password for the EasyPon cabinet. App will be installed in \`/usr/apps/easypon\`

### Accessing EasyPon

To access EasyPon, open your browser and navigate to your domain name or IP address of your server. You will be prompted to log in with your credentials, which you received in the terminal during installation, or which can be found in \`/root/.tmp\_ep\_users\`.

### Updating EasyPon

To update EasyPon to the latest version, run the following command:

> bash <(curl -k
>
> [https://cabinet.easypon.in/install\_ep.sh](https://cabinet.easypon.in/install\_ep.sh)
>
> ) upgrade
