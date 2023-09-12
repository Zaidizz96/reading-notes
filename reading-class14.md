# Password Hashing and bcrypt Overview

## Intro to Password Hashing

**Hashing:**
  Hashing is the process of converting a password into an irreversible, unique string of characters.
  It's akin to a secret code generator for passwords, where the resulting code is specific to the input password.
  
**General Definition to non-technical person**
  It's like turning your password into a secret language that only the computer can understand.
  This secret code is unique to your password, so even a small change in your password will result in a completely different code. 

## bcrypt Overview

**Salting a Password:**
- Salting a password involves appending a random string (the salt) to the original password before hashing it.
- This additional step enhances security by ensuring that even identical passwords will have distinct hash values, thwarting attackers who rely on precomputed tables (rainbow tables) for password cracking.
- For attackers to crack a password, they would need to obtain both the hashed password and its corresponding salt, typically stored together in a database.

**Blowfish Adaptation:**
  Blowfish, the underlying algorithm in bcrypt, maintains security by adapting to the increasing computational speed of modern computers.
  It achieves this by allowing users to specify a work factor or cost factor, which determines how many iterations of the algorithm are performed during hashing.
  

**Issues with Common Java Hashes:**
- When it comes to common password hashing methods in Java, two issues arise.
- Firstly, "Java password hash" often employs fast hashing algorithms that are susceptible to brute force and dictionary attacks due to their speed.
- Secondly, "Java password encryption" may use reversible encryption, making it vulnerable to decryption if attackers gain access to the encryption key.

  To enhance security, it's recommended to utilize bcrypt for robust password storage in Java applications.
