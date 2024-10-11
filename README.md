# barr4crypt

barr4crypt is a simple rotation-based encryption tool that provides a unique way to encrypt text.

## Installation

You can install barr4crypt using pip:

```py
pip install barr4crypt
```

## Usage

Here's a quick example of how to use Rotocrypt:

```python
from barr4crypt import encrypt

# Encrypt a message
message = "Hello, World!"
rot_value = 3
encrypted = encrypt(message, rot=rot_value)
print(f"Encrypted message: {encrypted}")
```

## License

This project is licensed under the MIT License - see the LICENSE file for details.
