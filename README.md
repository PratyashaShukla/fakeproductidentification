# fakeproductidentification
To check whether a product is real or counterfeit. 
PROPOSED IDEA
The manufacture can add various products where a QR will be attached to the 
products with serial id of the product stored, the QR further will be included with 
packaging and will pass by chain from manufacture to distributer to customer 
which can scan the QR on receiving the
product and compare with the original Serial id if it matches then product is REAL 
otherwise FAKE.
Library Used for Authentication : Passport(NodeJs)
Utility Used for Blockchain Connection : MetaMask
At the homepage the User will be provided with three cards to choose from which 
includes Manufacture,Distributor and Purchaser.
Product Schema
Authentication for Login is done by pbkdf2 algorithm of the node crypto library which 
stores the hash and the salt of the password.
PBKDF2 is a simple cryptographic key derivation function, which is resistant to dictionary attacks and rainbow table attacks. It is based on iteratively deriving HMAC 
many times with some padding. The PBKDF2 algorithm is described in the Internet 
standard RFC 2898 (PKCS #5). 
PBKDF2 takes several input parameters and produces the derived key as output
