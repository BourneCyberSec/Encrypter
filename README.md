# Encrypter
Requires Openssl && Shred

Encrypts Files using AES-256-CBC

To use this script run "keygen {K1}" this generates the 256 bit key. - Probably should keep this safe?
K1 being what u want to call the key.

Run "encrypt {F1} {F2} {K1"} this encrypts and destroys the origional file.
F1 being the file you want to encrypt.
F2 being the name you want to call the encrypted file.

Run "decrypt {F2} {D1} {K1}" this decrypts the file.
D1 - what you want to name the decrypted file.

