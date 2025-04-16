# CS 120 – April 16, 2025

## Lecture Topic: Cryptography – History, Principles, and Impact

### Recap of Key Concepts
- **Cryptography** is the science of hiding or securing information.
- A **simple substitution cipher** shifts plaintext characters by a fixed number (e.g., shifting "HELLO" by 1 gives "IFMMP").
- Such ciphers are easy to crack with tools like **frequency analysis**.

### Historical Origins
- **Julius Caesar** used a substitution cipher—this is now known as the **Caesar Cipher**.
- In the **9th century**, Al-Kindi introduced **frequency analysis**, a method for cracking substitution ciphers based on letter frequency.
- During the **American Revolution**, cryptography was used by revolutionaries to conceal messages from the British (e.g., with invisible ink or cipher disks).

### The Enigma Machine
- Used by the **Germans in WWII** to encode military communications.
- The machine included:
    - **Plugboard** for substitution ciphers
    - **Rotors** that changed position with each keystroke, altering the cipher dynamically
- This resulted in **150 trillion possible configurations**.

### Alan Turing and the Bombe
- **Alan Turing**, considered the father of modern computer science, developed the **Bombe** at **Bletchley Park** to break Enigma.
- The Bombe tried different rotor settings rapidly to find decipherable messages.
- Turing’s work laid the groundwork for the **Turing Machine**, a theoretical model of computation.

### Turing Machines and Computation
- A **Turing Machine** can compute any algorithmically solvable problem.
- Modern devices (like smartphones) are **Turing-complete**, capable of emulating any other computation, including themselves.
- Example: Running a virtual machine within a virtual machine.

### Everyday Use of Cryptography
- **HTTPS** websites use encryption to secure data during transfer.
- **End-to-end encryption** in apps like **Signal** and **WhatsApp** ensures only sender and recipient can read messages.
- **Password managers** store passwords using **hashed strings**, making them unreadable without the master key.
- **Biometrics** (Face ID, Touch ID) act as cryptographic keys for device access.

### Types of Cryptography
- **Asymmetric (Public Key)**: Two keys — one public, one private. Used in Bitcoin, secure email, GitHub authentication.
- **Symmetric**: One key used to both encrypt and decrypt. Faster but less secure.

### Ethical and Social Considerations
- **Cryptography protects privacy and human rights**, but can also be used for illicit activities (e.g., using Bitcoin for drug trafficking).
- Raises philosophical and legal questions:
    - Should encryption be absolute, or should the government have backdoor access?
    - Greater good vs. individual liberty
- Historical example: **Liberty Safe controversy**, where a company handed over user access codes to the FBI, sparking a backlash.
- Parallels to the **Patriot Act** and increasing surveillance post-9/11.

### Final Thoughts
- **Pancomputationalism**: The idea that the universe itself is a Turing machine computing its own state.
- On Friday: Deeper dive into **anonymization**, especially in research contexts.

---

**Fun Fact:** The word "computer" originally referred to a person, often a woman, who performed manual calculations. At Bletchley Park, these "computers" carried out algorithmic decryption by hand based on daily communications.

**Bonus:** Dr. Tomesh shared a personal story about visiting Bletchley Park and meeting one of the original codebreaking women (Wrens) who helped win WWII.

> "We had no idea what we were working on. We were just told this was for King and Country."
> – Former Wren at Bletchley Park
