# payment-gateway-php-paytm-payment-gateway
Paytm payment Gateway is very simple process in php. this payment gateway is use to receive our business payments by Paytm business account.

1. Copy PaytmKit folder in document root of your server (like /var/www/html)
2. Open config_paytm.php file from the PaytmKit/lib folder and update the below constant values
  a)-PAYTM_MERCHANT_KEY – Provided by Paytm
  b)-PAYTM_MERCHANT_MID - Provided by Paytm
  c)-PAYTM_MERCHANT_WEBSITE - Provided by Paytm
3. PaytmKit folder is having following files:
  -TxnTest.php – Testing transaction through Paytm gateway.
  -pgRedirect.php – This file has the logic of checksum generation and passing all required parameters to Paytm PG.
  -pgResponse.php – This file has the logic for processing PG response after the transaction processing.
  -TxnStatus.php – Testing Status Query API
