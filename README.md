### README: Text Encryption and Decryption Application

#### Overview
This is a Python-based GUI application that enables users to encrypt and decrypt text using a secret key. The application is built using the `Tkinter` library for the graphical interface and uses the `base64` module for encoding and decoding messages.

---

### Main Steps to Run and Use

1. **Run the Application**:
   - Save the code into a Python file, e.g., `text_encrypt_decrypt.py`.
   - Ensure you have a valid image file named `keys.png` in the same directory (used as the application icon).
   - Run the script using the command:
     ```bash
     python text_encrypt_decrypt.py
     ```

2. **Encrypt Text**:
   - Enter the text to be encrypted in the text box.
   - Provide the secret key (`1234`) in the password field.
   - Click the "ENCRYPT" button to encode the text. The encrypted message will appear in a new window.

3. **Decrypt Text**:
   - Enter the Base64-encoded text in the text box.
   - Provide the secret key (`1234`) in the password field.
   - Click the "DECRYPT" button to decode the text. The original message will appear in a new window.

4. **Reset Fields**:
   - Click the "RESET" button to clear the text box and password field.

---

### License
This application is free to use and modify for educational and personal purposes.

