# Caesar Cipher Encryption Tool

A Python GUI application that encrypts and decrypts text using the Caesar cipher.
Built as part of my cybersecurity internship at Prodigy InfoTech.

## What it does
- Takes plaintext input from the user
- Applies a configurable shift value (1–25)
- Outputs encrypted or decrypted text
- Built with Tkinter for a simple desktop interface

## Why I built this
This was my first project exploring classical cryptography. Caesar cipher is broken by modern 
standards (brute-forceable in 25 tries), but understanding why it fails is foundational to 
understanding modern symmetric encryption.

## How to run
pip install tkinter  # usually pre-installed with Python
python Cipher.py

## What I learned
- How substitution ciphers work mechanically
- Why key space size matters in encryption
- Basics of Python GUI programming with Tkinter

## Limitations
Caesar cipher offers no real security. For production use, look at AES-256 (via PyCryptodome).
