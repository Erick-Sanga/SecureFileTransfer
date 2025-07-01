# SecureFileTransfer
🔒 End-to-end encrypted file transfers tool created by Dr3amy

🚀 Quick Start
# Install dependencies
pip install cryptography tkinter

# Run the application
python secfiletransfer.py


✨ Key Features

    Military-grade encryption (AES-256)

    Secure key handling (PBKDF2 with salt)

    Cross-platform - works anywhere Python runs

    No cloud storage - direct peer-to-peer transfers

    Preserves file integrity - name and content protected


   Installation
Clone the Repository:
git clone https://github.com/Erick-Sanga/securefiletransfer.git
cd SecureFileTransfer

Install the Required Libraries:
pip install cryptography
pip install socket
pip install tkinter

Usage
Run the Tool:
python secfiletransfer.py

Sending a File:

Open SecureFileTransfer and select "Send".
Enter the recipient's host address and port.
Choose the file you want to send.
Enter a secure password.
Click "Execute" to send the file.

Receiving a File:

Open SecureFileTransfer and select "Receive".
Enter the port to listen on.
Enter the password that the sender will use.
Click "Execute" to start listening for incoming files.

Security
SecureFileTransfer employs several security mechanisms to ensure your files are safe:

AES-256 Encryption: Strong encryption standard to protect your files.
PBKDF2 with HMAC-SHA256: Robust key derivation function to secure your password.
IV (Initialization Vector): Random IV for each encryption session to ensure uniqueness.



















