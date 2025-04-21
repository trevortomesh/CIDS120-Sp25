Lecture Summary: CS 120 - Privacy, Anonymization, and K-Anonymity (April 21, 2025)

📅 Announcements
•	This Friday (April 25): No in-person class. Instead, students will be assigned a short reading and comment activity.
•	From next Monday (April 28) onward: All remaining sessions will be online only.
•	Office hours will still be available virtually.
•	Final exam will be online.
•	Position Paper 3 is now available: it is an anti-position paper, where students will rebut their own earlier argument.
•	Reminder: If you do not consent to AI-assisted grading, write “I do not consent to AI-assisted grading” at the top of your submission.

⸻

🔐 Privacy, Anonymity, and Re-identification

Personally Identifiable Information (PII):
•	Any piece of information that can be linked to a specific individual (e.g., name, date of birth, zip code, gender, address).
•	Even if names are removed, individuals can still be re-identified by combining other attributes.

Latanya Sweeney’s Research:
•	Demonstrated that even “anonymized” datasets can be de-anonymized.
•	In 1997, showed that 87% of the U.S. population could be uniquely identified using just zip code, date of birth, and sex.
•	Re-identified the Massachusetts governor’s hospital records by cross-referencing “anonymized” health data with voter rolls.

⸻

🔢 K-Anonymity

Definition:

A dataset is said to have k-anonymity if every record is indistinguishable from at least (k-1) others based on a set of quasi-identifiers (like age, gender, zip code).

Example:

If three people in a dataset are all 29 years old, live in the same zip code, and have different favorite cakes, an attacker cannot tell which person corresponds to which cake. This is called 3-anonymity.

Techniques:
1.	Suppression – Replace specific values with placeholders (e.g., ‘*’) to prevent re-identification.
2.	Generalization – Convert specific values into broader categories (e.g., age 27 becomes “21–30”).

Privacy through Groups:
•	The greater the value of k, the more protected each individual’s identity is.
•	Protects against uniqueness-based re-identification.

⸻

🧪 In-Class Activity: Anonymizing Dummy Patient Data

Students were given a CSV file containing fictional patient data including:
•	Name, Age, Sex, Height, Weight, Diagnosis, Religion, etc.

Objective:

Apply anonymization techniques to prepare the data for safe publication.

Student Observations:
•	Delete names and replace with patient IDs.
•	Bucket ages into ranges (e.g., 18–25, 26–35).
•	Convert weight/height into bins.
•	Collapse religious categories into broader groups (e.g., Christian, Muslim, Other).
•	Suppress rare diagnoses to prevent uniqueness.

Instructor Demonstration:
•	Created master copy of data before editing.
•	Used Excel formulas to bin age data.
•	Discussed using VLOOKUP or REPLACE for bulk generalization.

⸻

🧠 Key Takeaways
•	Re-identification is a real threat, even for anonymized data.
•	K-anonymity provides a structured method for data privacy.
•	Techniques like suppression and generalization help ensure data cannot be traced back to individuals.
•	Always work from a master copy before anonymizing data.

⸻

📌 Homework / Reminder
•	Begin work on Position Paper 3 (anti-position paper).
•	Explore anonymization techniques further by applying them to the dummy patient dataset (available on Canvas).
•	Be prepared to discuss anonymization strategies on Wednesday.