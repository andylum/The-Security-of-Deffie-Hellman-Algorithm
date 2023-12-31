# The-Security-of-Deffie-Hellman-Algorithm
Andy Lum, Zach Coomer, Jonathan Bess

## Abstract
The Diffie-Hellman protocol facilitates secure key exchange for message encryption but lacks entity authentication, rendering it susceptible to security threats like man-in-the-middle and impersonation attacks. This project explores discrete logarithm problem (DLP) resolution steps, state-of-the-art findings, SUN NFS cryptosystem assessment, and prime number size recommendations for a secure Diffie-Hellman implementation.

## Introduction
In this project for, we assume a foundational understanding of number theory and abstract algebra. Cryptosystems heavily rely on public key cryptography and key exchange protocols for safeguarding data. These systems are underpinned by one-way functions, where the seminal work of Diffie and Hellman introduced the discrete logarithm problem (DLP) as a robust source of such functions. We delve into the intricacies of DLP resolution and present state-of-the-art breakthroughs in this context. While solving DLP is feasible, the challenge lies in achieving a quick resolution, especially for sufficiently large prime numbers (p) crucial for security. The project also addresses key exchange, an early cryptographic concern, and underscores the growing importance of data security amid the pervasive internet landscape. We explore the SUN NFS cryptosystem's use of directories to manage data efficiently. Additionally, the selection of secure prime numbers for Diffie-Hellman security is a central focus of this project.

## Goals
- Develop a secure implementation of the Diffie-Hellman key exchange algorithm, addressing known vulnerabilities such as man-in-the-middle attacks.
- Create a user-friendly interface to make the algorithm more accessible to a broader range of users.
- Research and implement state-of-the-art cryptographic techniques to enhance the algorithm's security in modern cryptographic environments.
- Conduct rigorous testing and validation to assess the algorithm's security, efficiency, and scalability.
- Provide comprehensive documentation and tutorials to facilitate implementation for users of varying expertise levels.
- Promote the project as a valuable resource for the field of cryptography and key exchange, emphasizing its multifaceted contributions to the discipline.

## Results
The investigation reveals that solving the discrete logarithm problem (DLP) is inherently variable due to factors like group type and prime size. While there's no universal equation for DLP, using sufficiently large primes makes practical solutions improbable in today's cryptographic landscape. State-of-the-art DLP results are characterized by extreme time requirements, reinforcing the effectiveness of DLP as a one-way function for security and encryption. Network File System (NFS) succeeded due to its robustness and adaptability, offering close-to-open consistency and cache re-validation. Ensuring secure prime numbers for Diffie-Hellman involves using a good DH modulus, generating safe primes, and balancing size for optimal security without becoming counterproductive.
