# Encrypt/Decrypt Web Application

A simple web application to encrypt and decrypt textual information that the user inputs. The application uses AES-256-CBC encryption to ensure the security of the data. The encryption key is stored securely using environment variables.

## Features

- **Encrypt Text**: Encrypts user-provided text using AES-256-CBC encryption.
- **Decrypt Text**: Decrypts previously encrypted text.
- **Secure**: Uses a 32-character encryption key stored in an environment variable for strong encryption.

## Requirements

- Node.js
- npm (Node Package Manager)

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/encrypt-decrypt-app.git
   cd encrypt-decrypt-app

2.Install the dependencies:
npm install express body-parser ejs dotenv


3.Create a .env file in the root directory and add your 32-character encryption key:
touch .env
echo "ENCRYPTION_KEY=your-32-character-long-encryption-key" >> .env

4.Ensure your .env file is added to .gitignore to prevent it from being committed:
echo ".env" >> .gitignore

#Usage
1.Start the server:
node server.js

2.Open your browser and navigate to:
http://localhost:3000

3.Use the application to encrypt and decrypt text.
