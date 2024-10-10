# Caesar Cipher

The **Caesar Cipher** is a simple Python program that implements the classic encryption technique known as the Caesar Cipher. The program allows you to either encrypt (encode) or decrypt (decode) messages by shifting the letters of the alphabet by a specified amount.

## Features
- Supports both encoding and decoding of messages.
- Preserves non-alphabetic characters (spaces, punctuation, etc.).
- Allows the user to input a custom shift value for the cipher.
- Repeats the process if the user chooses to continue.

## How to Use
1. The program asks the user whether they want to **encode** (encrypt) or **decode** (decrypt) a message.
2. Enter the message to be processed.
3. Specify the shift value (the number of positions by which the letters will be shifted in the alphabet).
4. The program outputs the encoded or decoded result.
5. The user can then choose to run the program again or exit.

## Example
```bash
Type 'encode' to encrypt, type 'decode' to decrypt:
encode
Type your message:
hello
Type the shift number:
5
Here is the encoded result: mjqqt
Type 'yes' if you want to go again. Otherwise, type 'no'.
no
Goodbye
