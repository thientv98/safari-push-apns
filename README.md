Safari-Push-Notifications
=========================

Download AppleWWDRCA.cer form https://www.apple.com/certificateauthority/
Convert AppleWWDRCA.cer to AppleWWDRCA.pem
- openssl x509 -inform der -in AppleWWDRCA.cer -out AppleWWDRCA.pem