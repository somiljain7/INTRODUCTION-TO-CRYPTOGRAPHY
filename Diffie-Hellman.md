Diffie-Hellman

Diffie-Hellman is one of the first recorded examples of asymmetric cryptography, first conceptualized by Ralph Merkle and put into fruition by Whitfield Diffie and Martin Hellman. Traditionally, secure encrypted communication would require both parties to first exchange their keys by some secure physical channel. Diffie-Hellman eliminated the need for the secure exchange by creating an additional key, the public key.

At this moment in time, Deffie-Hellman is no longer the standard cryptographic algorithm because it has been found to be vulnerable to several attacks. A Logjam attack, for example, can allow man-in-the-middle attacks where the hacker can read and modify any data sent over the connection.

In Use Today? – Yes. For general PKI security and digital signing, NIST recommends RSA (see below) because Diffie-Hellman requires more CPU power and larger data exchange for Digital Signing and SSL in particular. But there are still some uses of Diffie-Hellman in the public sphere today for example, in Elliptic Curve Cryptography
