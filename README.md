# bajaj_training
This is used to store the common properties in the application.yml file.

Command to create the SSL certificate: keytool -genkeypair -alias localhost_ssl -keyalg RSA -keysize 2048 -storetype PKCS12 -keystore localhost-ssl.p12 –validity 365 -ext SAN=dns:localhost
