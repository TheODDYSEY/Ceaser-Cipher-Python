# Caesar Cipher Encryption/Decryption Script

This Python script implements the Caesar cipher, a classic encryption technique that shifts each letter in the text by a fixed number of positions down the alphabet. The script allows users to encrypt a message with a specified shift length or decrypt it by providing the original message and the negative shift length.

## Prerequisites

Before running the script, make sure you have Python installed on your machine. Additionally, install the `colorama` module by executing:

```bash
pip install colorama
```

## How to Use

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/TheODDYSEY/Ceaser-Cipher-Python
   ```

2. **Navigate to the Project Directory:**

   ```bash
   cd your-repository
   ```

3. **Run the Script:**

   Execute the script in your terminal.

   ```bash
   python caesar_cipher.py
   ```

4. **Enter Text and Shift Length:**

   The script will prompt you to enter the text or message you want to encrypt or decrypt and specify the shift length (key).

5. **View Encrypted/Decrypted Text:**

   The script will display the result based on your input.

## Example

Suppose you want to encrypt the message "Hello, World!" with a shift length of 3. The script will output:

```bash
[?] Please Enter your text/message: Hello, World!
[?] Please specify the shift length: 3
[+] Hello, World! has been encrypted as [encrypted_text]
```

To decrypt the message, you can input the encrypted text and use a negative shift length.

## Note

Ensure that you provide a valid shift length (between 0 and 25). The script will display an error message and exit if an invalid key is provided.

