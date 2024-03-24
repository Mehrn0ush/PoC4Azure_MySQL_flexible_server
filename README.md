# Proof of Concept (PoC) for MySQL Database Connection

## Description
This repository contains a simple proof of concept (PoC) script for establishing a connection to a MySQL database hosted on Azure using Python.

## Prerequisites
- Python 3.x
- Pip package manager

## Installation
1. Clone this repository to your local machine.
2. Navigate to the cloned directory.
3. Install the required dependencies using pip:

pip install -r requirements.txt



## Usage
Run the PoC script `poc.py` with the following command:

python3 poc.py -H test.mysql.database.azure.com -U u.txt -p p.txt -P 3306 --tls --tls-cert=DigiCertGlobalRootCATEST.crt.pem


Replace the placeholders accordingly:
- `-H`: Hostname or IP address of the MySQL database.
- `-U`: Path to a file containing the username.
- `-p`: Path to a file containing the password.
- `-P`: Port number (default is 3306).
- `--tls`: Enable TLS/SSL encryption.
- `--tls-cert`: Path to the TLS certificate file.

## Disclaimer
This PoC script is provided for educational and testing purposes only. Use it responsibly and ensure that you have the necessary permissions before attempting to connect to any database.
