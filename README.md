# Caesar Cipher Game

A simple Python command-line project that encrypts and decrypts text using the Caesar Cipher technique.

## About

This project shifts each letter in a message by a fixed number of positions in the alphabet.  
It supports both:
- `encode` to encrypt text
- `decode` to decrypt text

Non-letter characters like spaces, numbers, and symbols are kept unchanged.

## Features

- Encrypt text using a Caesar cipher.
- Decrypt previously encoded text.
- Preserves spaces, numbers, and symbols.
- Uses a simple loop so you can run it multiple times.

## How it works

1. Enter `encode` or `decode`.
2. Enter your message.
3. Enter a shift number.
4. The program prints the result.

## Example

```bash
Type 'encode' to encrypt, type 'decode' to decrypt:
encode
Type your message:
hello world
Type the shift number:
3
Here is the encoded result: khoor zruog
```

## Project Files

- `main.py` — main program file.
- `art.py` — contains the ASCII logo used at startup.

## Requirements

- Python 3.x

## How to run

1. Clone the repository:
```bash
git clone https://github.com/your-username/caeser-chiper-game.git
```

2. Go to the project folder:
```bash
cd caeser-chiper-game
```

3. Run the program:
```bash
python main.py
```

## Notes

- The program uses lowercase letters only.
- Spaces and symbols are not changed.
- The cipher wraps around the alphabet, so shifting past `z` starts again from `a`.

## Author

By HeyNia
