# 🔐 Caesar Cipher

A Python implementation of the Caesar cipher — one of the oldest and
simplest encryption techniques. Shifts each letter in a text by a fixed
number of positions in the alphabet.

## Features

- Encrypts any text with a shift value between 1 and 25
- Decrypts previously encrypted text
- Preserves spaces, punctuation, and capitalisation
- Input validation with clear error messages

## How to Run

```bash
python caesar_cipher.py
```

## Sample Output

```
==========================================
         CAESAR CIPHER DEMO
==========================================
  Original  : Courage is found in unlikely places.
  Shift     : 13
  Encrypted : Pbhentr vf sbhaq va hayvxryl cynprf.
  Decrypted : Courage is found in unlikely places.
==========================================
```

## How It Works

Each letter is shifted forward in the alphabet by the shift amount.
A shift of 13 is known as ROT13 — a special case where encrypting
twice gives back the original text.

```
A → N  (shift 13)
B → O
...
Z → M
```

## What I Learned

- Python functions with default parameters
- String translation tables using `str.maketrans()`
- Input validation and error handling
- The `if __name__ == "__main__"` pattern

## Author

Harshwardhan Kumar Paswan
