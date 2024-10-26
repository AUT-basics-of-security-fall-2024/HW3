Diffie-Hellman Key Exchange with HMAC Authentication 🛡️
This project is part of Homework 3 (HW3) for the Information Security course at Amirkabir University of Technology. It demonstrates the practical implementation of secure key exchange using Diffie-Hellman and message authentication with HMAC (Hash-based Message Authentication Code) to ensure message integrity and authenticity.

Features
Secure Key Exchange: Uses Diffie-Hellman to generate a shared secret key without direct transmission of private keys.
Message Authentication: Implements HMAC with SHA-256 to verify the integrity and authenticity of exchanged messages.
Step-by-Step Notebook: Interactive Jupyter Notebook with detailed explanations for each step.
Real-World Cryptography: Demonstrates essential cryptographic techniques used in secure communications.
Prerequisites
Make sure you have the following installed:

Python 3.8+
Jupyter Notebook
cryptography library
To install the required library:

pip install cryptography
How to Run the Notebook
Clone the Repository:

git clone https://github.com/srvn-nm/diffie-hellman-hmac.git
cd diffie-hellman-hmac
Launch the Jupyter Notebook:

jupyter notebook
Open the diffie_hellman_hmac.ipynb notebook.

Follow the Instructions:
Run each cell sequentially and follow the explanations to understand the key exchange process and HMAC calculation.

Expected Output
The notebook walks through the process of:

Generating a shared key using Diffie-Hellman.
Computing the HMAC of a message to ensure its integrity and authenticity.
Verifying consistency between the keys and HMAC values.
Example Output:

Shared Key: [A numerical value]
HMAC: [A hexadecimal hash value]
Folder Structure

📂 diffie-hellman-hmac
│
├── 📄 HW3_project.ipynb  # Jupyter notebook with explanations
├── 📄 README.md                  # Project documentation

How to Verify the Results
Check Shared Key Consistency: Ensure both parties derive the same shared key.
Validate HMAC Calculation: Use the provided shared key and message to confirm that the generated HMAC matches the expected value.
Contributing
If you want to contribute to the project:

Fork the repository.
Create a branch: git checkout -b feature-branch.
Make your changes and commit: git commit -m "Describe your change".
Push to your branch: git push origin feature-branch.
Open a pull request.
Author
srvn-nm

Course and Assignment Information
This project is submitted as part of HW3 for the Information Security course at Amirkabir University of Technology.

License
This project is licensed under the MIT License. See the LICENSE file for details.

Acknowledgments
Cryptography Library: cryptography.io
Inspired by core cryptographic principles like Diffie-Hellman and HMAC for secure communication.
