# lemonade
basic encryption algorithm that you can use to learn from

# features 
## encryption function (zitronenpflucker) - 
  * encrypts a given string by adding a code value to each character and converting the sums to hexadecimal strings
  * returns a vector of encrypted strings

## decryption function (zitruspress) - 
  * decrypts a vector of hexadecimal strings by subtracting a code value from each converted integer and converting them back to characters
  * returns the decrypted string

## main function -
  * demonstrates the usage of encryption and decryption functions
  * encrypts a message using zitronenpflucker and prints the encrypted message
  * decrypts the encrypted message using zitruspress and prints the decrypted message

# analyzing the code

1. encryption mechanism - the lemonade algorithm performs a simple additive encryption by adding a code value to each character and converting the sums to hexadecimal strings. this encryption mechanism is relatively basic and can be considered weak in terms of cryptographic strength. it lacks fundamental security features such as key management, strong randomness, and complex mathematical operations typically found in more secure encryption algorithms.

2. key derivation - the code value used for encryption and decryption is derived from the "limonadezaad" string. The security of the algorithm heavily relies on the strength and secrecy of this seed. If an attacker can determine or guess the seed, they can easily decrypt the messages. 
