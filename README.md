🔐 Secure Data Hiding in Images Using Steganography
Overview
This project is a Steganography-based encryption tool that allows users to hide secret messages inside images and retrieve them securely using a passcode. The system modifies the Least Significant Bits (LSB) of the image pixels to embed data without noticeable visual changes. It features an easy-to-use Streamlit UI for encrypting and decrypting messages.

📌 Features
✅ Hide text messages inside images using LSB steganography.
✅ Protect hidden messages with a passcode.
✅ Securely retrieve hidden messages by entering the correct passcode.
✅ Simple and intuitive Streamlit web interface.

🚀 Installation
Step 1: Clone the Repository
git clone https://github.com/bujjichanga/secure-data-hiding-in-images-using-steganography.git
cd secure-data-hiding-in-images-using-steganography

Step 2: Install Dependencies
Ensure you have Python installed, then install the required libraries:
pip install -r requirements.txt

Step 3: Run the Application


streamlit run app.py
🛠 How It Works
🔏 Encryption Process
Upload an image (PNG, JPG, JPEG).
Enter a secret message to hide.
Set a passcode to protect the message.
Click Encrypt to generate a new image containing the hidden message.
Download the encrypted image.
🔓 Decryption Process
Upload the encrypted image.
Enter the correct passcode.
Retrieve and read the hidden message.
📂 Project Structure
bash
Copy
Edit
📁 Secure-Data-Hiding-In-Images-Using-Steganography
│── app.py                  # Main Streamlit app
│── requirements.txt         # Required dependencies
│── README.md                # Project documentation
📜 License
This project is open-source and available under the MIT License.

🤝 Contributing
Contributions are welcome! If you'd like to improve this project, feel free to fork the repository and submit a pull request.

