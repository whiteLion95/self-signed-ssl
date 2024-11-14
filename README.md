openssl.exe req -new -x509 -newkey rsa:4096 -sha256 -nodes -keyout "./server.key" -days 36500
 -out "./server.crt" -config "./openssl.conf"
