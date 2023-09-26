---
description: >-
  This guide will walk you through process of installation EasyPON web
  application in your system.
---

# 🍥 Guide for Debian 11

1. Register an account in the EasyPON personal cabinet [https://cabinet.easypon.in](https://cabinet.easypon.in/login)
2. Login to your EasyPON personal cabinet account, and choose the existing license or add a new license instance.
3. Download the distribution archive of the latest Easypon version from your license.
4. Install or upgrade EasyPON. To install EasyPon, run the following command in your terminal:

{% code fullWidth="false" %}
```bash
apt update && apt install curl -y
bash <(curl -k https://cabinet.easypon.in/install_ep.sh) install
```
{% endcode %}

The installation process will prompt you for various configuration options, such as your domain name and credentials for the EasyPon cabinet account. The app will be installed in `/usr/apps/easypon.`

### Accessing EasyPon

To access EasyPon, open your browser and navigate to your domain name or IP address of your server. You will be prompted to log in with your credentials, which you received in the terminal during installation, or which can be found in `/root/.tmp_ep_users`.

## Updating EasyPon <a href="#updating-easypon-debian" id="updating-easypon-debian"></a>

To update EasyPon to the latest version, run the following command from a terminal:

```bash
bash <(curl -k https://cabinet.easypon.in/install_ep.sh) upgrade
```
