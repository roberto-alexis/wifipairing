# Wifi Pairing Demo
Please use this as an example on how to encrypt and decrypt the HTTP commands to control Wifi Cloud Printers.

## Usage
1. Connect to the printer's Wi-Fi
2. Run the command as follows:
```
./gradlew run --args $'YOUR-PRINTER-ENDPOINT YOUR-ENCRYPTION-KEY \'YOUR-COMMAND\''
```
3. Replace the YOUR-PRINTER-ENDPOINT, YOUR-ENCRYPTION-KEY and YOUR-COMMAND with the corresponding data
4. If the command is successful, this program will show decrypted response in the console.
5. If you are not connected to the right Wi-Fi, this program will eventually time out.
