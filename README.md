# Caesar Cipher – Python Project
<br>
This project is a simple implementation of the Caesar Cipher, one of the oldest and most widely known encryption techniques. The program allows users to encode or decode messages by shifting letters in the alphabet while preserving non-alphabet characters such as spaces, numbers, and punctuation.

## Features
<br>

**Encode and Decode Messages**<br>
Users can choose whether they want to encrypt a message or decrypt an already encrypted one.

**Shift-Based Encryption**<br>
Each letter in the input message is shifted by a user-defined number of positions in the alphabet.

**Handles Symbols and Numbers**<br>
Non-alphabet characters (numbers, symbols, spaces) are not altered and are carried over as-is.

**Program Restart Option**<br>
After each operation, the user can choose to run the program again without restarting it manually.

**Built-In Logo Support**<br>
Imports and displays an ASCII logo from art.py at the beginning of the program.

## How It Works?
1. When the program starts, it imports a logo from the art.py file and prints it on the screen.<br>
2. The user is asked whether they want to encode or decode a message.<br>
3. The user enters:<br>
   >The message<br>
   >The shift number<br>
4. The program processes each character:<br>
   >Alphabet characters are shifted forward or backward depending on the mode.<br>
   >Non-alphabet characters remain unchanged.<br>
5. The resulting encoded/decoded message is displayed.
6. The user can choose to run the cipher again or exit.
