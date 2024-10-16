# barr4crypt

barr4crypt is a simple rotation-based hashing tool that provides a unique way to encrypt text.
This method uses a dict like based system to encrypt and for addicional security hashes the final product in sha256.

## Installation

You can install barr4crypt using pip:

```py
pip install barr4crypt
```

## Usage

Here's a quick example of how to use barr4crypt:

```python
from barr4 import encrypt, verify

# Encrypt a message
message = "Hello, World!"
rot_value = 3
encrypted = encrypt(message, rot_value) # Output: 
print(f"Encrypted message: {encrypted}")

# Verify a string
string = "Hello, World!"
verify_string = verify(encrypted, string, rot=3)
print(verify_string) # Outputs: True
```

## License

This project is licensed under the MIT License - see the LICENSE file for details.
