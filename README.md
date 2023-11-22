# AES_Encrypt_Decrypt
Performing AES encryption and decryption

The provided C code implements a simple encryption and decryption scheme using the Advanced Encryption Standard (AES) algorithm. It utilizes several functions to perform the encryption and decryption operations:

encrypt Function: This function encrypts the provided data using the specified key and initialization vector (IV). It iterates through the data in blocks of 16 bytes (BLOCK_SIZE), XORs each block with the key, and then encrypts each block using the AES encryption algorithm.

decrypt Function: This function decrypts the encrypted data using the same key and IV. It works in reverse order, decrypting each block using the AES decryption algorithm and then XORing each block with the key.

xorBlock Function: This function performs an XOR operation between two blocks of data of the same length. It iterates through each byte in the blocks and performs a bitwise XOR operation.

aesEncryptBlock Function: This function represents the core of the AES encryption algorithm. It takes a block of data and the encryption key and applies the AES encryption algorithm to transform the data. The specific implementation of this function is not provided in the given code.

aesDecryptBlock Function: This function represents the core of the AES decryption algorithm. It takes a block of encrypted data and the decryption key and applies the AES decryption algorithm to recover the original data. The specific implementation of this function is not provided in the given code.
