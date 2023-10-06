---
description: >-
  The Integration section of the EasyPON web application empowers users to
  seamlessly connect various external components to enhance their experience
  with EasyPON.
---

# Integration

## **Integration Section Overview**

This guide will walk you through the steps to integrate Google services, UserSide integration, and create public API keys for interfacing with external EasyPON API.

<figure><img src="../.gitbook/assets/Screenshot 2023-10-04 at 12.30.29.png" alt=""><figcaption><p>Integration section page</p></figcaption></figure>

### **1. Connecting Google Authentification Integration**

The Google Integration feature allows you to streamline your operations by linking your EasyPON account with Google corporate services. Follow these steps to set up this integration:

{% hint style="info" %}
Please notice, Google Authentification Integration works only by HTTPS protocol.
{% endhint %}

<figure><img src="../.gitbook/assets/Screenshot 2023-10-04 at 12.30.35.png" alt=""><figcaption><p>Google authentification integration options</p></figcaption></figure>

1. **Log in to EasyPON Dashboard**: Navigate to the EasyPON dashboard and log in using your credentials.
2. **Access Integration Section**: From the dashboard, locate and click on the 'Integration' section.
3. **Google Integration**: In the Integration section, select the **Turn on Google Authorization?** option.
4.  **Authenticate Google Account**: You will be prompted to authenticate your Google account. Fill in the

    * Client ID - your Google client ID
    * API key - API key from Google corporate account
    * Allowed corporate domains. You can add multiple allowed domains by clicking  **Add domain**

    You can **Cancel** or **Save** changes.
5. **Authorization**: Grant the necessary permissions to allow EasyPON to access your Google services.
6. **Confirmation**: Once authenticated, you will receive a confirmation message indicating successful integration.

### **2. UserSide Integration**

UserSide integration is a vital aspect of the EasyPON ecosystem, enabling a seamless interaction between UserSide and EasyPON. Follow these steps to implement UserSide integration:

<figure><img src="../.gitbook/assets/Screenshot 2023-10-04 at 12.30.54.png" alt=""><figcaption><p>UserSide integration options</p></figcaption></figure>

1. **Access Integration Section**: From the EasyPON dashboard, navigate to the 'Integration' section.
2. **UserSide Integration**: Select the 'UserSide Integration' option.
3. **Configuration Settings**: Fill in the required configuration settings based on your application's requirements. Ensure accuracy in the provided information.
4. **Integration parameters:**
   * Integration type: Import or Synchronization. Import for one-time synchronization or periodical.&#x20;
   * Domain (API URL)  - your UserSide domain
   * API key - public API key of your UserSide account
5. **Test connection.** It's advisable to conduct thorough testing to confirm the successful implementation of UserSide integration.
6. **Select data to display in ONU information.** You can choose options that should be synchronized with UserSide integration:
   * ID
   * User Name
   * User full Name
   * User Login
   * Contacts
   * Contract ID
   * User ID
   * User Address
   * Status
   * Balance
   * Tariff
   * Network activity
   * Internet activity
   * Connection date
   * Comment
   * Incoming traffic
   * Outgoing traffic
   * Group
   * Billing ID
   * Creation date
   * Positive balance date
7. **Cancel or Save Changes**: Click on 'Save' to apply the integration settings or Cancel them.

### **3. Creating Public API Keys**

Public API keys are essential for secure communication between your application and the external EasyPON API. Follow these steps to generate API keys:

<figure><img src="../.gitbook/assets/Screenshot 2023-10-04 at 12.31.14.png" alt=""><figcaption><p>Creating public API key</p></figcaption></figure>

1. **Access API Keys Panel**: In the Integration section, locate and click on the 'API Keys' panel.
2. **Generate New API Key**: Click on the 'Generate New Key' button.
3. **Define Expiry date**: Specify the expiry date for the API key. You can also make it last indefinitely by checking the "Make it last indefinitely" option.
4. **Save API Key**: Click 'Save' to generate and save the API key or Cancel changes.
5. **Copy and Store Securely**: Once generated, copy the API key and store it securely, it will not be invisible for copying for the second time. Treat it as confidential information.

#### **External EasyPON API Documentation**

For detailed information on utilizing the EasyPON API, please refer to the External EasyPON API Documentation by following the **API documentation** link.

<figure><img src="../.gitbook/assets/Screenshot 2023-10-04 at 12.31.07.png" alt=""><figcaption><p>API keys panel</p></figcaption></figure>

This guide provides comprehensive instructions for integrating Google services, UserSide integration, and creating public API keys in the EasyPON web application. For further assistance or inquiries, please refer to the EasyPON support resources.
