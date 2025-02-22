# 🕵️‍♂️ Image Steganography: Hide & Reveal Secret Messages  

## 🔐 About This Project
This project uses image steganography to hide a secret message within an image and later decrypt it using a passkey. By embedding the message within pixel values, this method provides a fun and secure way to share hidden information. 

## 🚀 How It Works
1. The user provides a **Secret Code** to encode within an image.
2. A **Passkey** is required for encryption and decryption.
3. The message is embedded within the image's pixel values.
4. The encoded image is saved as `encryptedImage.jpg`.
5. Only users with the correct **Passkey** can decrypt and retrieve the hidden message.

## 🔎 Usage Instructions
### 🛠 Prerequisites
Ensure you have Python installed along with OpenCV (`cv2`). You can install OpenCV using:
```bash
pip install opencv-python
```

### 🔏 Encryption (Hiding the Message)
1. Run the script:
   ```bash
   python script.py
   ```
2. Enter the **Secret Code** to hide within the image.
3. Provide a **Passkey** for protection.
4. The program will generate `encryptedImage.jpg`, which contains the hidden message.

### 🔓 Decryption (Revealing the Message)
1. Run the script again.
2. Enter the **Passkey** when prompted.
3. If the passkey matches, the hidden message will be revealed!

## 🎭 Example Walkthrough
```plaintext
Secret Code To Unlock: Praveen K
Enter The passkey: Test@123

Encrypted image saved as encryptedImage.jpg

Enter passcode for Decryption: Test@123
Decryption message: Praveen K
```

## 🛡 Security Note
- Ensure that the correct passkey is used to retrieve the message.
- Do not share the passkey openly to maintain secrecy.

## 🌟 Have Fun With Steganography!
Let the mystery unfold! Encrypt your messages secretly and reveal them only to those who have the right key. 🚀✨