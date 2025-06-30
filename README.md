# simple-encrypter
🔐 A simple custom Python password encrypter module with 5 randomized encoding methods and key-based decryption. Fun, educational, and great for learning how encryption logic works!

---

## 🚀 Features

- 🔁 **Encrypt & decrypt any text**
- 🎲 **5 unique encoding methods** with randomized selection
- 🔑 **Key-based decryption** — each method uses a unique key to identify how to reverse the transformation
- ✅ Supports **letters, numbers, symbols, and spaces**
- 🔓 Lightweight & pure Python

---

## 📦 How It Works

The program includes five encryption methods (`method_1` to `method_5`) that perform custom character-index transformations using math operations. A random method is picked during encryption, and a unique key is attached to identify it for decryption.

Each method:
- Looks up each character’s index in a defined `alphabet`
- Applies a mathematical transformation
- Returns an encrypted code and a key

---

## 🧠 Example

```python
import simple_encrypter

# Encrypt a piece of text
result = password_encrypter.encrypt("Hi! my name is Kevin.")
print("Encrypted:", result)

# Decrypt it back
original = password_encrypter.decrypt(result)
print("Decrypted:", original)
```
Output:
```text
Encrypted: {'code': '69,19,127,191,27,51,191,29,3,27,11,191,19,39,191,75,11,45,19,29,179', 'key': '#4902192'}
Decrypted: Hi! my name is Kevin.
```
---

## 🧩 Supported Characters
This tool supports:

- Uppercase and lowercase letters (A-Z, a-z)
- Digits (0-9)
- Symbols (!@#$%^&*()-_+=[]{}|;:'",.<>/?\\~`)
- Spaces

--- 
## 👨‍💻 Author
<strong>Kevin Ehab</strong><br><br>
Built as a creative and educational project to explore encryption logic in Python.
