# Homomorphic Encryption Protocols
This package implements a set of secure delegation of computation protocols based on 
Homomorphic Encryption systems. 

The implemented protocols are:
* [Homomorphic Addition](docs/add.md): the client encrypts and sends an arbitrarily long list of numbers
  to the server. The server performs the homomorphic addition and produces an encrypted sum. This result 
  can only be decripted by the client.
* [Homomorphic Multiplication](docs/mul.md): the client encrypts and sends an arbitrarily long list of 
  numbers to the server. The server performs the homomorphic multiplication and produces an encrypted 
  result that can only be decripted by the client.
* [Homomorphic Newton-Raphson Division](docs/div.md): the client encrypts and sends to numbers to the server.
  The server performs the homomorphic addition and produces an encrypted result that can 
  only be decripted by the client.
* [Homomorphic Mean](docs/mean.md): the client encrypts and sends an arbitrarily long list of numbers
  to the server. The server runs the addition protocol and the interactive division protocol.
