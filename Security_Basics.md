# Security Basics

## CIA Triad

- Confidentiality
- Integrity
- Availability

### Confidentiality

Means to ensure that data is only available and viewable by intended authorized users.

Encryption - Encryption can be used to make information unreadable by unathorized personnel while authorized personnel can decrypt and recover access

Access Controls - Ensure only authorized personnel can access data

1) Identification - unique identifyer code (username, email, ID card) to establish individuality
2) Authentication - proof of identity with something known (password) and/or something held (key card)
3) Authorization - rules that state what information is or is not accessible to a user or group

Obfuscation - hidding or obscuring data

> Encryption is the best means to ensure confidentiality. Access controls can restric access on controled systems. Obfuscation, including steganography can hide information "in plane sight"

### Integrity

Means to ensure that data has not been modified, tampered with, or corrupted

Hashing - a code based on the original information that, when consistent, ensures that the original information has not been modified

Digital Signatures, Certificates, Non-repudiation - Ensure that the information is from the true, intended source and not some imposter

- Digital Signatures (Certificates) - ensure that the source of information is in fact legitimate
- Non-repudiation - ensure that the source of information can not deny being the source

> Hashing can determine if information has been changed since created. Signatures can ensure that the information was created by a trusted source.

### Availability

Redundancy and Fault Tolerance
