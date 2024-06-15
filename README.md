# AES Simplified Encryption and Decryption

## Overview

This project implements a simplified version of the AES (Advanced Encryption Standard) algorithm. It includes key components such as the multiplication inverse table, S-box construction, and encryption/decryption operations. The implementation is done in Java.

## Features

- AES Encryption and Decryption
- 128-bit key size
- 10 rounds of processing
- Byte substitution (SubBytes)
- Row shifting (ShiftRows)
- Column mixing (MixColumns)
- Round key addition (AddRoundKey)

## Project Structure

- **MultiplicationInverseTable.java**: Contains methods to generate the multiplication table and compute its multiplicative inverse.
- **SBOXConstruction.java**: Constructs the S-box used in the encryption process.
- **SimplifiedAES_Encryption.java**: Implements the simplified AES encryption process.
- **SimplifiedAES_Decryption.java**: Implements the simplified AES decryption process.

## How to Use

1. **Clone the Repository**
    ```bash
    git clone https://github.com/502ermira/aes-simplified.git
    cd aes-simplified
    ```

2. **Compile the Java Files**
    ```bash
    javac AES/*.java
    ```

3. **Run the Main Program**
    ```bash
    java AES.SimplifiedAES_Encryption
    java AES.SimplifiedAES_Decryption
    ```
    
**Note:** To encrypt a different plaintext message, you can modify the `plaintext.txt` file. Simply replace the contents of `plaintext.txt` with your desired message.
