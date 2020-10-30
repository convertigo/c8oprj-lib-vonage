# lib_Vonage
This is the Convertigo connector to Vonage API for SMS, Viber, Whatsapp, Facebook Messenger and MMS messaging services.

## Installation
Use file->import->Convertigo Project and paste

```
lib_Vonage=https://github.com/convertigo/c8oprj-lib-vonage.git
```
In the Project Remote Url field

## Usage
### Configuring symbols
This library needs 2 symbols :
```
lib_Vonage.apiKey
lib_Vonage.apiSecret.secret
```
Configure these symbols to the correct value you find in the Vonage API dashboard

https://dashboard.nexmo.com/

### Sequences

Youc can use the following sequences in your project :

sequence | usage
------------| -------
sendSMS     | send a SMS to anyone
sendWhatspp | send a WhatsApp Message



