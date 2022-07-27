<h1>Goldman-Sachs-Engineering-Virtual-Program </h1>

<h1>Crack Leaked Password Database</h1>

## Analyze results and purpose uplifts to controls and policies

## Overview
As a governance analyst it is part of your duties to assess the level of protection offered by implemented controls and minimize the probability of a successful breach. To be successful at your job you often need to know the techniques used by hackers to circumvent implemented controls and propose uplifts to increase the overall level of security in an organization. Gaining valid credentials gives the attackers access to the organization’s IT system, thus circumventing most of perimeter controls in place.

## Objective

`• What type of hashing algorithm was used to protect passwords?`

`• What level of protection does the mechanism offer for passwords?`

`• What controls could be implemented to make cracking much harder for the hacker in the event of a password database leaking again?`

Here is a sample data file containing hashes dumped together:

https://www.github.com/addy100/Goldman-Sachs-Engineer-Virtual-Program/blob/main/passwd_dump.txt

## Project Report

```
After analysis it was determined that the `hashing algorithm` used by the organization was Message Digest `MD5` Algorithm. MD5 is an outdated password hashing algorithm which offers trivial protection from password leaking. I would suggest to apply a stronger alternative for the encryption purposes to create hash for the passwords based on `SHA` which is Secured Hash Algorithm.

After implementing various attack on the leaked hashes, following about organisation’s password policy was figured out:
• No specific requirement of characters for password creation.
• Minimum length of password is set to 6 characters.

You should include following recommendations to your new password policy:
• Include the password mixed of upper and lower case, alphanumeric and special characters. 
• Passwords should not contain any similarities with personal contact details like username, date of birth, or any other relevant information.
• Longer passwords are better, viz minimum of 8 characters.
• Avoid the occurrence of verbs and common nouns.
• Apply a hashing algorithm over another, recursively to have a stronger hashing function.

```

## Resources 

https://en.wikipedia.org/wiki/Salt_(cryptography)

https://en.wikipedia.org/wiki/Cryptographic_hash_function

https://en.wikipedia.org/wiki/Password_cracking#Software

https://hashcat.com

https://howsecureismypassword.net/

https://www.security.org/how-secure-is-my-password/

https://arstechnica.com/information-technology/2013/05/how-crackers-make-minced-meat-out-of-your-passwords/