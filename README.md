# Password Generator and Encryptor using bcrypt (Python)

## Description
This project is a Python-based application that generates a secure password and encrypts it using the bcrypt hashing algorithm. Bcrypt is a one-way encryption method, meaning the hashed password cannot be decrypted back to its original form. This ensures that passwords are securely stored and resistant to reverse engineering.

## Features
- **Password Generation**: Generates a random, secure password with configurable length.
- **Password Hashing**: Hashes the generated password using bcrypt for secure storage.
- **Password Verification**: Verifies if the generated password is strong enough using regular expressions.

## Requirements
Python 3.x

### Install the required libraries by running the following:
- bcrypt
- random
- string

## Google Colab Setup
Open this project in Google Colab by clicking [here](https://colab.research.google.com/drive/1s-lro3I3OUSi9-0krn6mRemwtBBKMhfk?usp=sharing).


**Note:** This project does not integrate with any database services. All data (including generated and hashed passwords) exists only during runtime and is not saved or persisted to a database.

## Contribution

To contribute to this project, follow these steps:

1. Fork the repository.
2. Clone your forked repository:
   ```bash
   git clone https://github.com/ProjectFuritsu/PasswordGeneration.git
   cd PasswordGeneration
3. Create a new branch:
    ```bash
    git checkout -b feature-name
4. Make your changes and commit them:
    ```bash
     git commit -am "Add feature-name"
5. Push to your forked repository:
    ```bash
    git push origin feature-name
6. Open a Pull Request on the original repository.
