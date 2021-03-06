# EATS
Encryption And Text Steganography

PROJECT AIM:  
To send messages which are encrypted using end-to-end encryption and steganographically encoded in an image over WiFi
with the condition that both should be connected to the same WiFi
network

DESCRIPTION:  
This project uses both end-to-end encryption and Image steganography to transfer messages from a client to server,
Image steganography refers to hiding any kind of information be it text, another image inside an image.
Here are some links to read more about Steganography:
(https://towardsdatascience.com/steganography-hiding-an-image-inside-another-77ca66b2acb1)
(https://en.wikipedia.org/wiki/Steganography)

The project implements end-to-end encryption using RSA encryption provided by the module [PyCryptodome](https://pycryptodome.readthedocs.io/en/latest/).
The database used is MySQL and I am using [mysql-connector-python](https://dev.mysql.com/doc/connector-python/en/) for establishing connection to database.

INSTALLATION:
1. Clone the repository
2. Open terminal and move to the directory Steganography-Based-Message-Transfer/SE_Proj
3. Type chmod a+x install.sh
4. Type ./install.sh

DEMO:
1. Normal Image:  




    ![](cat.png)

2. Text-encoded Image:




    ![](new.png)
