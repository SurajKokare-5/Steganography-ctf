# Steganography-ctf
Creating an SMTP server involves configuring the server to handle email transmission . The use of a 
domain as a key for decryption can enhance security and can decrypt sensitive metadata, which may 
include an encrypted flag. 
To implement this, one must establish the SMTP server, and integrate a mechanism for encrypting 
metadata. This process typically involves: 
Setting Up the SMTP Server 
Implementing TLS: Enable TLS to secure email transmission, ensuring that emails are encrypted 
during transit. 
Domain-Based Encryption: Use the domain as a key for encrypting metadata. This can involve 
generating encryption keys based on the domain name and using them to encrypt sensitive 
information. 
Handling Encrypted Metadata: Ensure that the SMTP server can process incoming emails with 
encrypted metadata, decrypting it using the appropriate domain key. 
Testing and Validation: Conduct thorough testing to ensure that the server operates correctly and 
that the encryption and decryption processes function as intended. 
To accomplish the task, please follow the steps outlined below: 
Decrypt the PDF Notepad Ciphertext: Begin by utilizing the "mile2" key, which is associated with a 
domain name, to decrypt the provided PDF notepad ciphertext. This step is crucial as it will yield a 
new key necessary for the subsequent phase. 
Obtain the New Key: Upon successful decryption of the ciphertext, you will acquire a new key. This 
key is essential for the next step in the process. 
Retrieve the Flag: Finally, use the newly obtained key to access and retrieve the flag. 
