# CoinPayment
API Sample Code


cURL Command Line Example
---

````
curl --request POST \
--url https://www.coinpayments.net/api.php \
--header 'Content-Type: application/x-www-form-urlencoded' \
--header 'HMAC: your_generated_hmac' \
--data 'version=1&cmd=rates&key=your_api_public_key&format=json'
````

Composer
---
To install with composer run the following command
--
```
composer require coinpaymentsnet/coinpayments-php
```
