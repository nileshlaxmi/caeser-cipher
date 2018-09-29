# Caeser Cipher
Caesar cipher, also known as a shift cipher. In a shift cipher the meanings of the letters are shifted by some set amount.

A common modern use is the ROT13 cipher, where the values of the letters are shifted by 13 places. Thus 'A' ↔ 'N', 'B' ↔ 'O' and so on.

Caesar cipher is one of the earliest known and simplest ciphers. It is a type of substitution cipher in which each letter in the plaintext is shifted to a certain number of places down the alphabet. For example, with a shift of 1, A would be replaced by B, B would become C, and so on. The method is named after Julius Caesar, who allegedly used it to communicate with his generals.

Here is a quick example of the encryption and decryption steps involved with the Caesar cipher. The text we will encrypt is "defend the east wall of the castle," with a shift (key) of 1.

```
Plaintext: "defend the east wall of the castle"
Ciphertext: "efgfoe uif fbtu xbmm pg uif dbtumf"
```

It is easy to see how each character in the plaintext is shifted up the alphabet. Decryption is just as easy, by using an offset of -1.

```
Another example:
Plaintext: "abcdefghijklmnopqrstuvwxyz"
Ciphertext: "bcdefghijklmnopqrstuvwxyza"
The text above is shifted by 1 offset.
```