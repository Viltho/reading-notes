# Things i would like to know more about

- The Caesar Cipher is a substitution cipher named after Julius Caesar. It operates by shifting each letter in the plaintext by a fixed number of positions down the alphabet. For example, with a shift of 3, 'A' becomes 'D,' 'B' becomes 'E,' and so on. The principle behind the cipher is quite simple—the letters of the alphabet are shifted by a predetermined key, and the resulting ciphertext is produced.

- Historically, Caesar Cipher was used by Julius Caesar for military communications. He would shift the letters by three positions, allowing his generals to decipher the message by shifting the letters back by the same amount. The Caesar Cipher is a relatively weak form of encryption, as it has a limited key space and can be easily deciphered through brute force or frequency analysis. Nonetheless, it laid the foundation for more advanced cryptographic techniques.

- Symmetric encryption involves using the same key for both encryption and decryption. The sender and the receiver must possess the same key to encrypt and decrypt messages. This makes symmetric encryption efficient and faster than asymmetric encryption. However, it requires a secure method for key exchange since both parties need to agree on the same key.

- Asymmetric encryption, also known as public-key encryption, uses a pair of keys: a public key and a private key. The public key is widely distributed and can be used to encrypt messages, while the private key is kept secret and used for decryption. The key difference is that the private key cannot be derived from the public key. This enables secure communication without requiring a secure key exchange process. Asymmetric encryption is often used for key exchange, digital signatures, and securing communication channels.

- Computers generate random numbers using algorithms known as random number generators (RNGs). Pseudo-random number generators (PRNGs) are deterministic algorithms that use a starting point called a seed to generate a sequence of numbers that appear random but are actually predictable. They are commonly used in computer programs and simulations. However, PRNGs are not suitable for cryptographic purposes since their output can be recreated if the seed is known.

- True random number generators (TRNGs) rely on physical processes to generate randomness. They capture unpredictable physical phenomena such as atmospheric noise, radioactive decay, or mouse movements to produce random numbers. TRNGs provide a higher level of randomness and are used in cryptographic applications that require strong security guarantees.

- In cryptography, PRNGs are often used for generating encryption keys, session keys, or initialization vectors. TRNGs, on the other hand, are used for generating cryptographic seeds, nonces, or random values in cryptographic protocols where unpredictability is crucial.

- Encryption is the process of converting plaintext into ciphertext using an encryption algorithm and a secret key. It obscures the original message, making it unreadable to unauthorized individuals. In an analogy, encryption can be likened to putting a message into a locked safe. Only those with the key can unlock the safe and read the message.

- Decryption is the reverse process of encryption. It involves converting ciphertext back into plaintext using the decryption algorithm and the same secret key. Decryption essentially retrieves the original message from the safe by unlocking it with the correct key.