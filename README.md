## File Encryption and Decryption using Fernet

## Overview

This Python script provides a basic example of file encryption and decryption using the Fernet symmetric key encryption algorithm from the cryptography library.

## Prerequisites

Make sure you have Python installed on your system.

```
pip install cryptography
```

## Usage

1. Run the script
```
python main.py
```

2. Generate a Key:
The generated key will be saved to a file named encrypted_key.key.

3. Encrypt a File:
Replace something.txt with the path to the file you want to encrypt.
The encrypted file will be saved as encrypted_file.txt.

4. Decrypt a File:
After encryption, you can decrypt the file using the same key.
The decrypted file will be saved as decrypted_file.txt.

## File Structure

- main.py: The main Python script containing functions for key generation, key saving/loading, file encryption, and file decryption.
- encrypted_key.key: The file containing the generated encryption key.
- something.txt: The input file you want to encrypt.
- encrypted_file.txt: The encrypted output file.
- decrypted_file.txt: The decrypted output file.
