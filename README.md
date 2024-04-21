# Kashier-Whmcs-Plugin
Kashier Whmcs Plugin

 * Version: 1.0.0
 * Tested up to: 18.5.1

![](https://raw.githubusercontent.com/Kashier-payments/Kashier-Whmcs-Plugin/main/steps/kashier-logo.png)
![](https://raw.githubusercontent.com/Kashier-payments/Kashier-Whmcs-Plugin/main/steps/whmcs-logo.png)

### Features

- Fully PCI DSS compliant as a Level 1 Service for merchant operating in Egypt.

- 3D secure cards authentication support.

- Support multiple payment method.

      1. Card Payments
      2. Wallet Payments 
      3. Bank Installments Payment
      4. Fawry Payments

- Support acquiring multiple currencies "EGP, USD, GBP, EUR".

- Plug and play.


### Installation

- Download [kashier.zip](https://raw.githubusercontent.com/Kashier-payments/Kashier-Whmcs-Plugin/main/kashier_whmcs.zip) 

- unzip the downloaded file.

- Upload the following files to your WHMCS `modules/gateways` folder.

      1. modules/gateways/kashier.php
      2. modules/gateways/kashier
      3. modules/gateways/callback/kashier.php
      
- Navigate to `Addons->Browse->Payments`

![](https://raw.githubusercontent.com/Kashier-payments/Kashier-Whmcs-Plugin/main/steps/whmcs_1.png)

### Obtain Test Credentials

- Login or Sign up on kashier.io https://merchant.kashier.io/

- Navigate to Integrate now section > payment api keys.

- Navigate to Integrate now section > Secret keys.

- Generate a new api key with your prefered name that describes your integration channel, there is 1 default api key you could use that is created when signing up.

- Copy Merchant ID visible under your user name "MID-xx-xx".

![](https://raw.githubusercontent.com/Kashier-payments/Kashier-Whmcs-Plugin/main/steps/apikey_mid_test.png)

- there is Kashier Payment gateway added to `Addons > Browse > Payments` section

- Activate Kashier payment gateway to accept payment via kashier.

![](https://raw.githubusercontent.com/Kashier-payments/Kashier-Whmcs-Plugin/main/steps/whmcs_2.png)

- Insert the MID, Test Api Key in the Configuration page of each payment method. 

![](https://raw.githubusercontent.com/Kashier-payments/Kashier-Whmcs-Plugin/main/steps/whmcs_3.png)

- Make sure you are on test mode.

- Customize the displayed title that will show up to your users.

- Choose which payment method you want to allow your customers to pay with via Kashier

- Save configuration.

### Test plugin 

- Proceed to make an order on your shop, a new payment method is added . it could be changed from module configuration.

- After proceeding you will find a Kashier Payment. choose it and proceed to make a payment.

### Go live

- After activating your account.

- Make sure you are on live mode.

- Navigate to Integrate now section > payment api keys.

- Generate a new api key with your prefered name that describes your integration channel, there is 1 default api key you could use that is created when signing up.

![](https://raw.githubusercontent.com/Kashier-payments/Kashier-Whmcs-Plugin/main/steps/apikey_mid_live.png)

- Insert Live Api Key in the Configuration page of each module.

- change the mode from test to live.

- Save configuration.

![](https://raw.githubusercontent.com/Kashier-payments/Kashier-Whmcs-Plugin/main/steps/whmcs_4.png)


### Support

- Leave us an inquiry ticket on https://kashier.io for questions.


