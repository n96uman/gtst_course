1. Encoding/decoding
    - this method of creating ciphertext with out any key.
2. Encrypting/Decrypting
    - This is method of creating cipher text with key.
3. Hash Function: it is one way algorithm.
    - p vs np relationship look like this mathematical problem.
    - ==Salt==: is a random string used for data modification for password.
    1.==MD5==(message-digest algorithm) 
    command = ==md5sum==
    convert in to 128-bits. means 32 digit.
    there were problem because some value have the same hash cipher text.
    we only use it know for data integrity and confidentiality.
    to check the hash command : - ==sha256sum name.==
## Kinds of encodings/encryptions
1. to identify the hash 
    - hashid
    - cyber chef (web)
    - Tunnelsup (web)
    - some of the hashes salt may be generated by open fire and check it there.
2. decoding/decryption
    hashes
        - craskstation.net(non-salted)
        - own cracking(google he name)
    Encoding
        - cyberchef
    ## wordlists
    1. custom word lsit
        - cewl
        - cupp
        - crunch
            syntax: crunch 4 6 abcd -o test
            -t charchter set : '[,natan^%%%]
            - , for all upper case latter
            - @ for all lower case characters
            - % for  all numeric characters
            - ^ for all special characters
            -p : permutation
# Jhon the ripper
syntax : jhon [option] [pathfile]
options
  - wordlist=<path>: to specify the wordlist
  - format=<hashtype>
