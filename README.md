# Learn-String-Manipulation-By-Building-Cipher

🔐 Vigenère Cipher Encryptor/Decryptor
This project is a simple Python implementation of the Vigenère Cipher, a method of encrypting alphabetic text by using a series of Caesar ciphers based on the letters of a keyword.

📌 Features
Encrypt any message using a custom key

Decrypt encrypted messages back to the original

Ignores non-letter characters (like spaces or punctuation) during encryption/decryption

🧠 How It Works
This script defines a vigenere() function that handles both encryption and decryption depending on the direction:

direction = 1: encrypt

direction = -1: decrypt

Helper functions:

encrypt(message, key)

decrypt(message, key)

The cipher uses a repeating key to shift each letter in the message by a number of positions defined by the corresponding letter in the key.

🧪 Example
python
Copy
Edit
text = 'mrttaqrhknsw ih puggrur'
custom_key = 'happycoding'
Output:
pgsql
Copy
Edit
Encrypted text: mrttaqrhknsw ih puggrur
Key: happycoding

Decrypted text: hellotherehow are youdoing
▶️ Usage
Just run the script:

bash
Copy
Edit
python vigenere_cipher.py
Or modify the message and key like so:

python
Copy
Edit
text = 'your encrypted message here'
custom_key = 'yourkey'
decryption = decrypt(text, custom_key)
📁 File Structure
bash
Copy
Edit
vigenere_cipher.py   # Main script file
README.md            # This file
✅ Requirements
No external libraries needed. Works with any basic Python interpreter (Python 3+).

📜 License
This project is open source and available under the MIT License.

