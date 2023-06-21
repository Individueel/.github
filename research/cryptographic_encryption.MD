# Onderzoek cryptographic failures - Mike van den Hoef (Fontys ICT)

## Table of contents
- [Which type of cryptographic algorithm in software systems is most secure?](#which-type-of-cryptographic-algorithm-in-software-systems-is-most-secure)
- [What is a cryptographical algorithm?](#what-is-a-cryptographical-algorithm)
- [What are the essential features of cryptographic algorithms?](#what-are-the-essential-features-of-cryptographic-algorithms)
- [What are the different types of cryptographic algorithms?](#what-are-the-different-types-of-cryptographic-algorithms)
- [How do symmetric and asymmetric cryptographic algorithms differ?](#how-do-symmetric-and-asymmetric-cryptographic-algorithms-differ)
- [Which are the most commonly used cryptographic algorithms?](#which-are-the-most-commonly-used-cryptographic-algorithms)
- [What are the strengths and weaknesses of each cryptographic algorithm?](#what-are-the-strengths-and-weaknesses-of-each-cryptographic-algorithm)
- [Which cryptographic algorithm provides the best security for specific applications?](#which-cryptographic-algorithm-provides-the-best-security-for-specific-applications)
- [How does the key length affect the security of cryptographic algorithms?](#how-does-the-key-length-affect-the-security-of-cryptographic-algorithms)
- [What are the potential threats and vulnerabilities of cryptographic algorithms?](#what-are-the-potential-threats-and-vulnerabilities-of-cryptographic-algorithms)
- [Which cryptographic algorithm would I use in my projects?](#which-cryptographic-algorithm-would-i-use-in-my-projects)
- [Sources](#sources)

## Which type of cryptographic algorithm in software systems is most secure?
Cryptographic algorithms play a crucial role in securing data in various applications. With the increasing number of cyber-attacks, it is essential to determine which cryptographic algorithm is the most secure. In this research, I will compare and analyze some of the most commonly used cryptographic algorithms in terms of their security features (Stubbs, n.d.). By evaluating their strengths and weaknesses, I aim to identify the algorithm that provides the highest level of security for software systems.

## Research Methods
To address my research questions, I will employ the method of internet research as a primary means of retrieving information. The internet serves as a vast repository of knowledge, offering a wide range of resources and data related to my research topic. By utilizing search engines, online databases, scholarly articles, and reputable websites, I will be able to access a wealth of information relevant to my study. Internet research enables me to explore different perspectives, analyze existing studies, gather statistical data, and review previous research findings. Through systematic and thorough internet research, I aim to acquire a comprehensive understanding of the subject matter and obtain the necessary information to answer my research questions effectively.

## What is a cryptographical algorithm?
A cryptographic algorithm is a mathematical formula used for data encryption, authentication, and digital signatures. It transforms plain text into unintelligible data through encryption techniques, ensuring confidentiality and security (What Is Cryptography or a Cryptographic Algorithm? | DigiCert FAQ, n.d.).

## What are the essential features of cryptographic algorithms?
The essential security features of cryptographic algorithms include confidentiality, integrity, authenticity, and non-repudiation. Confidentiality ensures that data remains secure and inaccessible to unauthorized individuals. Integrity guarantees that the data remains unaltered during transmission. Authenticity verifies the origin of the data and ensures it has not been modified by a third party. Non-repudiation prevents the sender from denying the transmission of data (Stubbs, n.d.).

## What are the different types of cryptographic algorithms?
Cryptographic algorithms can be categorized into two main types: symmetric and asymmetric. Symmetric algorithms use the same secret key for both encryption and decryption processes. In contrast, asymmetric algorithms employ a pair of keys: a public key for encryption and a private key for decryption. Various subcategories exist within these types, including block ciphers, stream ciphers, and hash functions (Stubbs, n.d.).

## How do symmetric and asymmetric cryptographic algorithms differ?
Symmetric and asymmetric cryptographic algorithms differ primarily in terms of key management and security levels. Symmetric algorithms are more efficient for encrypting large amounts of data as they employ a single shared key for encryption and decryption. Asymmetric algorithms, on the other hand, use a pair of keys, making them more secure but slower due to the additional computational complexity (Stubbs, n.d.).

## Which are the most commonly used cryptographic algorithms?
The most commonly used cryptographic algorithms include AES (Advanced Encryption Standard), RSA (Rivest-Shamir-Adleman), and SHA (Secure Hash Algorithm). AES is a symmetric algorithm widely used for encrypting data in various applications. RSA, an asymmetric algorithm, is commonly employed for secure data transmission and digital signatures. SHA, a hash function, is frequently used for ensuring data integrity and authentication (Stubbs, n.d.).

## What are the strengths and weaknesses of each cryptographic algorithm?
Each cryptographic algorithm possesses its own strengths and weaknesses. AES is known for its speed, efficiency, and widespread adoption but may be susceptible to side-channel attacks. RSA is widely recognized for its security but is slower and requires more computational power. SHA is fast, efficient, and commonly used for a variety of projects, but it may be vulnerable to collision attacks (Stubbs, n.d.).

## Which cryptographic algorithm provides the best security for specific applications?
The choice of the best cryptographic algorithm depends on the specific application's security requirements, performance needs, and key management considerations. AES is suitable for encrypting large volumes of data, while RSA is well-suited for secure data transmission and digital signatures. SHA is commonly used for ensuring data integrity and authentication (Stubbs, n.d.).

## How does the key length affect the security of cryptographic algorithms?
Stubbs, R. (n.d.). Classification of Cryptographic Keys. https://www.cryptomathic.com/news-events/blog/classification-of-cryptographic-keys-functions-and-properties

The key length affects the security of cryptographic algorithms because longer keys provide more security against brute force attacks. For example, a 128-bit key provides more security than a 64-bit key. However, longer keys also require more processing power and can affect the performance of the algorithm.

## What are the potential threats and vulnerabilities of cryptographic algorithms?
Cryptographic algorithms are susceptible to various threats and vulnerabilities. Brute force attacks involve systematically trying all possible keys to decrypt encrypted data. Side-channel attacks exploit implementation weaknesses, such as timing information or power consumption, to extract confidential information. Key management issues, such as inadequate key storage or unauthorized access, can compromise the security of the algorithm. Implementation flaws, such as design errors or coding mistakes, can introduce vulnerabilities (Stubbs, n.d.).

## Which cryptographic algorithm would I use in my projects?
For my projects, I would choose to use SHA cryptographic algorithms. SHA algorithms are widely available and relatively easy to use. They provide fast and efficient data integrity and authentication, which aligns with the requirements of my school projects. Additionally, SHA algorithms have been extensively tested and widely adopted, making them a trusted choice for many applications.

## Sources
Stubbs, R. (n.d.). Classification of Cryptographic Keys. https://www.cryptomathic.com/news-events/blog/classification-of-cryptographic-keys-functions-and-properties
(What Is Cryptography or a Cryptographic Algorithm? | DigiCert FAQ, n.d.). https://www.digicert.com/kb/what-is-cryptography-or-a-cryptographic-algorithm/