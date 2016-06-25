# NamePros public keys #

Public keys (PGP, etc.) for NamePros and its staff

# Use of smart cards #

Except where otherwise noted, all keys in this repository were generated on write-only smart cards.  This means that a private key can only be used by a person in physical possession of the associated smart card.  Barring flaws in the hardware of the device, it's impossible--or at least extremely difficult--to retrieve the private key from the smart card.  All cryptographic operations are performed on the smart card itself, meaning that malware can't steal the private key.

Despite strong guarantees of a smart card, it is still possible for an attacker to compromise the security of a smart card-generated key pair.  For example, malware specifically designed to target smart cards could utilize the device after it's unlocked by the user.  As such, care should always be taken to ensure that the current validity of a key is verified before it is used/trusted.
