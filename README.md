Safari-Push-Notifications
=========================

## Download Apple Intermediate Certificates (AppleWWDRCA.cer)
```
https://www.apple.com/certificateauthority/
```
## Convert AppleWWDRCA.cer to AppleWWDRCA.pem
```
openssl x509 -inform der -in AppleWWDRCA.cer -out AppleWWDRCA.pem
```
