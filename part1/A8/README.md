### Encrypted Communication in Bluetooth IoT Devices
- Internet of Things devices such as wireless earbuds, smart watches and Bluetooth speakers use cryptographic techniques to secure communication with smartphones and other devices
- During the pairing process devices exchange cryptographic keys and establish a trusted connection using secure protocols such as Bluetooth Secure Simple Pairing (SSP)
- Once paired, a shared encryption key is generated which is used to encrypt all data transmitted between the devices
- The encryption algorithm (such as AES-based encryption used in Bluetooth) ensures that the transmitted data cannot be read or intercepted by unauthorised devices
- This protects sensitive information such as audio data, device commands and control signals from being accessed by attackers
- Additionally, authentication mechanisms ensure that only trusted and previously paired devices can reconnect, preventing unauthorized access
- Security Concept: Encryption, Key Exchange and Secure Communication

Evidence:
![Bluetooth Encrypted Connection](iot_device.png)

Even if encryption is not shown explicitly, bluetooth connections use encryption protocols to secure communication between paired devices

## Reflection
This example demonstrates how cryptography is embedded in everyday IoT devices to protect communication between systems. Even simple devices such as Bluetooth earphones rely on encryption and authentication to ensure secure data exchange. It highlights the importance of cryptographic protocols in preventing unauthorized access and maintaining privacy in connected environments.

## Conclusion
Cryptography plays a critical role in securing IoT devices by ensuring that data is encrypted and communication is authenticated. Technologies such as Bluetooth encryption and secure key exchange help protect user data from interception and misuse. As IoT devices continue to grow, the use of strong cryptographic techniques becomes essential for maintaining security and trust.
