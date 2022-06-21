# Paysolutions-SDK

Paysolutions-SDK Usage :

Merchant should change a attribite in tag button for call paysolutions sdk

## Button Attribute

| Attribute   |      Description      |Mandatory|  Type |  Sample |
|----------|:-------------:|------:|------:|------:|
| merchantid |  Merchant ID |M| (Numeric 8 Digit) | 12345678 |
| msecretkey |  Merchant Secret Key |M| String | ERWRWERWTWETWETW |
| prdrefno |  Reference No. |M| (Numeric 12 Digit) | 123456789012 |
| prddet |  Product Detail |M| String (255) | Simple Product |
| prdtotal |  Total |M| Float 2 percision (00.00) | 123.45 |
| prdcc |  Currency Code |M| String (2 Charactor) | 00 |
| prdlang |  Language |M| String (2 Charactor) | TH |
| prdcustemail |  Customer E-Mail |M| e-mail | customer@email.com |
| merlogo |  merchant logo |M| logo url | https://www.m-logo.com/logo.jpg |
| mername |  merchant name |M| String | Shop Name |
| paychannel |  Display Payment Channel  |M| String Comma Separate | FULL,PP,TW |
| prdpburl |  Postback URL  |O| URL | https://www.merchant.com/pb?param1=1&param2=1 |
| prdrturl |  Return URL  |O| URL | https://www.merchant.com |
| prdcusttel |  Customer Tel. No.  |O| Tel. No. | 082123456 |

## Payment Channel 

| Code   |      Description      |
|----------|:-------------:|
|FULL|Credit card full payment|
|AMEX|American Express|
|CUP|China Union Pay|
|INS| Installment|
|PP|Promptpay|
|BILL|Bill Payment|
|IB|Internet Banking|
|WC|We Chat|
|AL|Alipay|
|TW|True Money|

## Currency Code

| CODE   |      Currency     |
|----------|:-------------:|
|00|Baht|
|01|USD|
|02|Yen|
|03|Singapore Dollar|
|04|Hongkong Dollar|
|05|Eur Dollar|
|06|GBP (Pound)|
|07|Australian Dollar|
|08|Swiss Franc|

## SDK Step

### Button

![](https://s3-payso-images.s3.ap-southeast-1.amazonaws.com/sdk-button.png "Paysolutions Button")

### Popup

![](https://s3-payso-images.s3.ap-southeast-1.amazonaws.com/sdk-popup.png "Paysolutions Popup")


### Credit Input

![](https://s3-payso-images.s3.ap-southeast-1.amazonaws.com/sdk-credit.png "Paysolutions Credircard")