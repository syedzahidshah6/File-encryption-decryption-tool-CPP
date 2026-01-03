# Simple File Encryption/Decryption Tool (C++)

A beginner-friendly C++ console program that encrypts and decrypts files using an XOR cipher.

## Features
- Encrypt any file into an output file
- Decrypt the encrypted file back using the same key
- Works with text files and binary files (images, PDFs, etc.)
- Validates user input (menu + Y/N prompts)

## How it works
This tool uses XOR encryption:
- Encryption and decryption are the same operation.
- Using the same key on the encrypted file restores the original file.

> Note: XOR encryption is **not secure for real-world use**. This project is intended for learning file I/O and basic encryption concepts.

## Build and Run (Windows)
```bash
g++ file_cipher.cpp -o file_cipher
file_cipher
