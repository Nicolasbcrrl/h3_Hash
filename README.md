# h3_Hash
## Applied Cryptography

### 2.3 One-Way Functions

- The **one-way function** is the central element to the understanding and operation of public-key cryptography.
- The **one-way** function works as follows. We take an element x and convert it into a function (f(x)). 
- It can be used to encrypt passwords, files, folders, messages, etc.
- It is a simple function to set up, but it is very complicated to solve. Because as seen in the previous point, it is simple to transform an element x into f(x), but it is more complicated to solve f(x) to find x without any information.
- It can take millions of years to solve x starting from f(x).
- Public key cryptography has another element in its setup. A secret information that allows the function to be solved provided it is known, in other words **a backdoor**.

### 2.4 One-Way Hash Functions

- Compression function, contraction function, message digest, figerprint, etc., are the names for the **one-way hash function**.
- It is inseparable from modern crypthography methods
- A hash function will ask for an input string of variable length, which is also called a **pre-image**. Then it will convert it into a fixed length string, which is called the **hash value**.
- The hash of a pre-image can also be used to ensure the authenticity of a copy of the original pre-image. To do this, the user will only have to compare the two hashes. If there is a difference it means that the copy may have been modified. So it would be potentially less secure.
- It is almost impossible to generate the same hash for two different images. 
- Changing a single bit in the original pre-image completely changes the hash.
- **MAC** and **DAC** are one-way hash functions to which the encryption key is added to the pre-image. This way, only the desired person can check the hash value.

MAC : Message Authentication Codes A message authentication code

DAC : data authentication code

### Sources

[ Applied Cryptography, chapter 2 : Protocol Building Blocks](https://learning.oreilly.com/library/view/applied-cryptography-protocols/9781119096726/10_chap02.html#chap02)

-----
## Install Hashcat
### Source
-----
## Hash Cracking
### Sources
------
## Installation of John the Ripper
### Sources
------
## Zip file password cracking
### Sources
------
