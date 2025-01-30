FTP Login Bruteforce

Overview

FTP Login Bruteforce is a penetration testing tool designed to test the security of FTP (File Transfer Protocol) servers by attempting to gain unauthorized access through brute-force attacks. The script automates login attempts using a list of common usernames and passwords.

Features

Supports dictionary-based brute-force attacks

Customizable username and password lists

Multithreading for faster execution

Logging of successful attempts

Error handling for connection issues

Requirements

Python 3.x

socket module (built-in)

ftplib module (built-in)

Installation

Clone the repository:

git clone https://github.com/yourusername/FTP_Login_Bruteforce.git
cd FTP_Login_Bruteforce

Install required dependencies (if any):

pip install -r requirements.txt

Usage

Prepare a username list and password list.

Run the script with the following command:

python ftp_bruteforce.py -t <target_ip> -u <username_list> -p <password_list>

Example:

python ftp_bruteforce.py -t 192.168.1.10 -u usernames.txt -p passwords.txt

Disclaimer

This tool is intended for educational and security testing purposes only. Unauthorized access to FTP servers is illegal and punishable under law. The author is not responsible for any misuse of this tool.

License

This project is licensed under the MIT License - see the LICENSE file for details.

Contribution

Feel free to fork, modify, and contribute to this project. Submit pull requests for any improvements or feature additions.
