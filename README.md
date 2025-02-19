# Image-Based Text Steganography

## 📌 Introduction
This project implements a simple **steganography technique** to hide a secret message inside an image by modifying pixel values. The hidden message can be retrieved only if the correct passcode is provided.

## 🚀 Features
- 🔐 **Message Encryption** – Hides text within image pixel values.  
- 🔑 **Passcode Protection** – Ensures only authorized users can decrypt.  
- 🎨 **Uses OpenCV** – For reading, modifying, and saving images.  
- ⚡ **Lightweight & Fast** – No heavy cryptographic dependencies.  
- 🖼️ **Automatic Image Opening** – Encrypted image is displayed after processing.  

## 🛠️ Technologies Used
- **Programming Language**: Python 🐍  
- **Libraries**: OpenCV (`cv2`), OS (`os`), String (`string` - though not used)  

## 📂 Installation & Usage

### 1 Install Dependencies
Make sure you have Python installed. Then, install OpenCV:

```sh
pip install opencv-python
```

## 2. Run the Script

python steganography.py

Enter the secret message you want to hide.

Provide a passcode to secure the message.

The encrypted image (encryptedImage.jpg) will be saved and opened automatically.

For decryption, enter the correct passcode to retrieve the message.

## 🎯 Use Cases

🔍 Forensic Investigations – Extract hidden data from images.

🛡️ Cybersecurity – Securely store confidential messages.

🕵️ Stealth Messaging – Hide text without raising suspicion.

📚 Learning & Research – Understand basic steganography concepts.

## 🔮 Future Scope

🔒 Enhance Security – Implement stronger encryption like AES/RSA.

📦 Optimize Storage – Improve efficiency for storing longer messages.

🎥 Video Steganography – Extend to video frames for more data capacity.

🤖 AI-Powered Detection – Detect hidden messages using machine learning.

## 📜 License

This project is open-source and available under the MIT License.

## 🤝 Contributing

Contributions are welcome! Feel free to fork the repo, improve the project, and submit a pull request.

## 📧 Contact

For any queries or suggestions, feel free to reach out!
