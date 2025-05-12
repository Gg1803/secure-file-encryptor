
# Secure File Encryptor

Command-line tool to encrypt and decrypt files using Fernet (AES-based) encryption.

## Commands

- Generate a key:
```
python encryptor.py genkey
```

- Encrypt a file:
```
python encryptor.py encrypt test_files/secret.txt
```

- Decrypt a file:
```
python encryptor.py decrypt test_files/secret.txt.enc
```
