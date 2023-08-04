# 50.042-CTF-Yellow-Veggies-Public

## Instructions:

To solve get the flag, you need to complete Task 1 followed by Task 2.  
Decrypt the secret in Task 1 to get a key and hint for Task 2.

## Contents
* Task 1 
    - publicKey.pem
    - secret.enc
    - Storyline Task 1.pdf
* Task 2
    - Complete Storyline.pdf


## Task 1 (RSA)
You are given an RSA public key and an encoded secret message. Your task is to find a way to decode the message. The message will help with finding the flag in Task 2.
 
 Some starters:
* Understand how RSA uses keys to encrypt and decrypt text, especially the math behind it!
* You can use Kali Linux to help you.
* Feel free to use online calculators and previous codes to help.
* https://cryptography.io/en/latest/hazmat/primitives/asymmetric/rsa/# might be helpful

## Task 2 (Vigenere Cipher)
Read the Storyline. Use the clues from Task 1's encoded secret and the storyline to get the flag.  

Use Vigenere Cipher to solve the flag.  
Ciphertext: (get clues from the text and hint from Task 1)  
Key: (get from Task 1)  
Flag: plaintext   