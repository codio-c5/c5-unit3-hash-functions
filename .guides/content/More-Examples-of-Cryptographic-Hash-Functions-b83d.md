- **SHA-3**
  - Designed by Bertoni, Daemen,Peeters, Van Assche 
  - Published by NIST in 2015 as the new standard
  - Not meant to replace SHA-2 as SHA-2 has not been broken
- **MD, Message Digest Algorithms**
  - **MD4**
    - Designed by Rivest in 1990
    - 128 bit digests; used in TLS certificates
    - Practical collision attacks were developed against it
   - **MD5**
     - Similar to MD4; security severely compromised, so not suitable for cryptographic use.

|||guidance
## guidance
The MD family of hashes are not suitable for cryptographic use, but they can still be used for checksums when adversaries are not present.

|||
