---
description: 'To install EasyPON, run the following command in your terminal:'
---

# Install EasyPON

{% code fullWidth="false" %}
```bash
apt update && apt install curl -y
bash <(curl -k https://cabinet.easypon.in/install_ep.sh) install
```
{% endcode %}

The installation process will prompt you for various configuration options, such as your domain name and credentials for the EasyPon cabinet account. Also, it is required to choose the EasyPON license which will be installed. Once installed it can not be reinstalled again.

{% hint style="info" %}
Please contact technical support if you want to reset your EasyPON license for new installation.
{% endhint %}

The EasyPON app will be installed in `/usr/apps/easypon` and `superuser` will be created for your convenience for accessing EasyPON.&#x20;
