RSA

The Rivest-Shammir-Adleman algorithm, better known as RSA, is now the most widely used asymmetric cryptosystem on the web today. RSA is based on the factorization of prime numbers, because working backwards from two multiplied prime numbers is computationally difficult to do, more so as the prime numbers get larger. The challenge of breaking RSA is known as the ‘RSA problem’.

RSA is a slow algorithm and because of this, it is used to encrypt and decrypt the symmetric keys which in turn, encrypt and decrypt the communications. The symmetric keys perform the bulk of the work, while RSA creates a strong and secure channel.

In 1998, Daniel Bleichenbacher described how he exploited a vulnerability in the PKCS#1 file (used to carry the private key). His attack was able to retrieve the private key and use it to recover session keys and decrypt messages. As a result of his work, RSA Laboratories released new versions of PKCS#1 that are not vulnerable to the same attack. While some attacks to RSA have been attempted, the algorithm remains strong, arguably until quantum computers become mainstream.

In Use Today? – Yes. RSA is the most widely used asymmetric algorithm today.
