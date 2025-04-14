**Lecture Summary: Ethical Treatment of Personal Information (CS 120 - April 11, 2025)**

Today we continued our discussion of **privacy and informed consent**, examining ethical guidelines and technical methods for collecting and protecting personal information. The lecture included ethical considerations, software design principles, and technical strategies like encryption and access control.

---

### Informed Consent (Review)
- **Definition**: Full knowledge of what will be done with collected information, and agreeing to volunteer that information.
- Two parts:
    - **Disclosure**: Know what will be done
    - **Voluntariness**: Agreeing to it without coercion

---

### Ethical Guidelines for Working with Personal Information

1. **Get Informed Consent**
    - Always seek voluntary and informed participation when collecting personal data.

2. **Inform When Collecting Personally Identifiable Information (PII)**
    - Examples of PII: Name, SSN, birthday, address, driver's license number, etc.

3. **Collect Only Necessary Data**
    - Don’t over-collect. If your app is a jigsaw puzzle, it doesn’t need GPS or health data.
    - Avoid apps that ask for unnecessary permissions—some even abuse devices for crypto mining!

4. **Ensure Strong Protection for Sensitive Data**
    - Use updated software
    - Avoid using outdated systems (e.g., Windows XP)
    - Encrypt sensitive data, restrict access
    - Governments and healthcare orgs have been notoriously bad at this (e.g., HealthPartners breach)

5. **Retain Data Only As Long As Necessary**
    - Holding on to data too long increases risk of breach
    - Old data is often inaccurate or outdated (e.g., mail to previous residents)

6. **Ensure Data Accuracy**
    - Keep contact information and personal records up to date
    - Inaccuracies can result in security and privacy breaches

7. **Have a Plan for Law Enforcement Requests**
    - Case Study: **Liberty Safe** gave FBI a gun safe code under a warrant — huge controversy
    - Understand the difference:
        - **Warrant**: Seize physical property
        - **Subpoena**: Request for information
    - Companies should have clear internal policies on how to respond

---

### Techniques to Protect Data in Databases

1. **Access Restriction**
    - Passwords, two-factor authentication (2FA), biometrics
    - Systems are only as secure as the weakest password or lax policy
    - 2FA adds a layer of external verification

2. **Cryptography**
    - **Definition**: Obscuring data using mathematical algorithms (encryption)
    - Example: Substitution cipher (e.g., Caesar cipher)
    - **Plaintext**: Original message
    - **Ciphertext**: Encrypted message
    - **Key**: The secret used to encrypt/decrypt
    - Alan Turing and the foundations of computer science were rooted in cryptography (e.g., breaking Nazi codes)

---

### Key Takeaways
- Ethical data collection is grounded in transparency, necessity, and protection
- Users must be empowered to control their data
- Technical literacy (e.g., understanding permissions, passwords, and encryption) is a form of digital self-defense
- Ethics, law, and software design intersect constantly in the tech industry

---

Next time, we will continue with cryptography and explore more real-world scenarios involving data misuse and ethical dilemmas in computing.

---

**End of Lecture**

