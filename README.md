# Questions & Answers
### How to prepare a new development environment?
* PC running with Ubuntu/Windows
* Internet connection
* Install editors (vim, VSCode)
* Install Git
* Configure Git
     - Set Full Name
     - Set Email
     - Set default Git editor
     - Generate ssh key
     - Paste public key in github.com
* Install Python
* Clone git repo
* Write code
* Push code to remote git repo


### How key based authentication works?
Client

* Generate public and private key pair (ssh Key)
* Share public key with server
* Encrypt the message with private key
* Transmit the encrypted message to the server

Server

* Received message from client
* Decrypt the message with public key shared by client
