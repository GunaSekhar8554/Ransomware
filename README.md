# Ransomware

# Don't misuse , Only made for educational use.

 Program that can encrypt any file or folder in the system.

1. Ransomware is a type of malware that encrypts the files of a system and decrypts only after a sum of money is paid to the attacker.

2. We use key derivation functions to derive a key from a password ie we will use Symmetric encryption algorithm[AES algorithm].
         
3. Scrypt algorithm is used in the python program , Scrypt is a password-based key derivation function.

4.Modules used are:
      a. pathlib       -  provides an easier method to interact with the filesystem.
      b. os            -  functions for creating and removing a directory (folder), fetching its contents,
                          changing and identifying the current directory, etc.
      c. secrets       -  Salting is done using the secrets to generate the random bits
      d. base64        -  encoding binary data to printable ASCII characters and decoding such encodings back to
                          binary data
      e. getpass       -  provides a platform-independent way to enter a password in a command-line program
      f. cryptography  -  used to verify the password and creating its hash
      g. Fernet        -  provides symmetric encryption and authentication to data.
      h. Scrypt        -  Scrypt is useful when encrypting password as it is possible to specify a minimum
                          amount of time to use when encrypting and decrypting.
     
 5. The functions present in the program are:
      a. generate_salt()       - Implements the salting ie adding random bits to the password
                                 Uses the secrets module for the salting process
     
     
      b. derive_key()          - Deriving the key from the password using the passed salt
                                 ●  The salt.
                                 ● The desired length of the key (32 in this case).
                                 ● n: CPU/Memory cost parameter, must be larger than 1 and be a power of 2.
                                 ● r: Block size parameter.
                                 ● p: Parallelization parameter.
                                 
                   
      c. load_salt()          - load salt from salt.salt file
      
      d. generate_key()       - Generates a key from a password and the sale.
      
      e. encrypt()            - Given a filename (str) and key(bytes) , it encrypts the file and writes it.
      
      f. decrypt()            - Given a filename (str) and key (bytes), it decrypts the file and write it.
      
      g. encrypt_folder()     - If it's a folder, encrypt the entire folder 
      
      h. decrypt_folder()     - If it's a folder, decrypt the entire folder 
      
                                 
                                 
                                 
                                 
                                 
                                 
                                 
                                 
                                 
                                 
                                 
                                 
                                 
                                 
                                 
                                 
                                 
                                 
                                 
                                 
                                 
                                 
                                 
                                 
                                 
                                 
                                 
                                 
                                 
                                 
                                 
                                 
                                 
                                 
                                 
                                 
                                 
                                 
                                 
