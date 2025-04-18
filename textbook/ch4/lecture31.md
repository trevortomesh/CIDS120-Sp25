# CIDS 120 Lecture Summary – April 18, 2025

## Semester Planning Updates
- April 18th: Final in-person lecture week.
- April 25th: No in-person class — either an activity or a video will be provided.
- April 28, 30, May 2, 5, 7, 9: Online classes via Zoom (recordings available).
- Final Exam: Online.
- Assignment schedule noted to be chaotic (e.g., multiple quizzes and assignments back-to-back).

## Cryptography and Randomness

### Recap:
- Cryptography: securing information through encoding.
- The shift (Caesar) cipher is a basic example.
- Good encryption relies on randomness and complexity.

### Determinism vs. Randomness:
- Computers are deterministic and not good at generating true random numbers.
- True randomness is essential for strong cryptographic security.
- Best practice: create a path from plaintext to ciphertext that is impossible to reverse without a key.

### Generating Strong Keys:
- Good keys have no discernible pattern.
- Example random key: `[7, 9, 0, 2, 13]`
- This randomness prevents reverse engineering of encrypted data.

### Pseudo-randomness:
- Simulates randomness using deterministic algorithms.
- Uses "seeds" to generate unique outputs.
- Example: Minecraft world generation based on seed input.

### Sources of Randomness:
- Natural entropy sources:
    - **Radioactive decay**
- Mathematical unpredictability:
    - **Distribution of prime numbers**
- **UNIX Time** (milliseconds since Jan 1, 1970) used as a changing seed for randomness.

## Applications of Cryptography
- Used in: banking, login credentials, communication apps, password managers.
- HTTPS encrypts web traffic.
- Passwords are stored as hashed strings.
- Face ID / Touch ID as cryptographic verifications.
- Asymmetric vs. symmetric encryption:
    - Asymmetric: public + private key (used in GitHub, email encryption)
    - Symmetric: one key for both encryption and decryption

## Privacy vs. Security
- Encryption protects human rights and individual privacy.
- Also enables criminal activity (e.g., illegal markets, ransomware).
- Core debate: *greater good vs. individual liberty*

## Cryptography and Democracy
- Voting systems (e.g., Diebold machines) rely on cryptography.
- Weak cryptographic systems risk election integrity.
- Democracy depends on secure, verifiable vote counting.

## Data Anonymization
- Personally Identifiable Information (PII): name, address, SSN, birthday, etc.
- Removing PII can protect privacy.
- Small datasets can still lead to re-identification (e.g., eye color + preference data).

### Real-World Examples:
- 1990s: Massachusetts GIC released anonymized health data.
    - Re-identified by combining zip code, birth date, and sex.
    - Latanya Sweeney demonstrated how 87% of the US could be uniquely identified with these three fields.

## Coming Up
- Monday: Discussion on **k-anonymization** – a method to combat re-identification.
- Reminder: Graded papers have been returned.

---

Thanks for attending! See you next class.

