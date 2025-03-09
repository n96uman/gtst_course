- it has two main components
1. Encryption: hide.
2. integrity: check if not altered.
- two kind of encryption.
1. symmetric and asymmetric.
## symmetric algorithms
types:
- Block ciphers
    encrypt data one 64 bits or 128 bits.
    used for single message
- stream ciphers
    Encrypt data one bit or one byte at time
    used if data is a constant stream of information.
- ==substitution ciphers==
- ==caesar cipher==: he put the first ABC to the last.
- Using a key to shift alphabet : shift the alphabet based on the word you want to encrypt.
- ==Rot(rotation)==:ROT3 is a simple letter substitution cipher that replaces a letter by rotate.
## Data Encryption standard/DES
Developed by IBM. and it is Symmetric key encryption.it is block cipher.1977.
 - Des operats by taking a 64-bit block of plaintext and encrypting it using the following steps.
## initial and final permutation
    TH initial and final permutationns are straight permutation boxes(p-boxs) that are inverses of each other.
    ## Fiesel Round
    the encryption process that is done by 16 round.
    each round involves several key operations.
    - Expnsion
    - substitution
    - permutation
    - XOR with a subkey
    - Swapping halves
## Advanced Encryption Standard / AES
    is a Symmetric encryption algorithm that is widely used across the globe to secure sensitive data. is block cipher.use bytes more than bit.
    - it support d/f level of key
    128-bits , 192-bit and 256-bit
    AES-s56 is highly secure.
### how AES works
     it operate by using series of operations like substitution , permutatioin and mixing of input data.
     the encryptioin process consist of several rounds, dependingon the key size:
     AES-128:10 rounds
     AES-192:12 round
     AES-256:14 rouond
    each round uses series of steps:
    1.Subbytes:A substitition step where bytes replaced according to a predefined lookup table(s-box).
    2.shiftRows
    3. MixColumns:A matrix multiplication.
    4. Add round key.
## common terms
- secretKey: tis is the 56-bit key.
- IV(initialization vector): A random  or pseudo random value used to isure inqueness in encryption.
- Encryption mode:
    - ECB(Electronic codebook): Each block of plaintext is encrypted independently.
    - CBC(cipher Block chaining):Each plaintext block is xoRed with the previous ciphertext block before encryption.
## Asymmetric Encryption
there are two keys:
- public key for encryption
- private key for decryption
### Types of asymmetric enc.
- Two most popular algorithm are
1. RSA
    - Developed by Ron Rivest , Adi Shamir , Len Adelman
    - both public and private key are interchangable.
    - a variable key size (512,1024 or 2048 bits)
    - most popular public key algorithm
2. EL Gamal
    - Developed by Taher ELGAMAl
    - variable key size (512 or 1024 bits)
    - less common than RSA.
# ssh-Keygen