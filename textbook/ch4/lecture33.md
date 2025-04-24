# Privacy, Anonymization, and the Risks of Reidentification

## Final In-Person Session: April 23, 2025

This marks our final in-person class for CIS 120. From next week onward, all sessions will take place online via Zoom. Lectures will be recorded and uploaded to Canvas, and you are welcome to attend live or watch later. While attendance isn’t required, it’s always appreciated—it’s more fun when there’s someone to talk to who isn’t a cat.

Office hours will continue but shift to virtual meetings. If standard office hours don't work for you, just email to schedule a time. Final exams will be online as well.

---

## Wrapping Up Privacy

We concluded our multi-week discussion on privacy by exploring techniques for anonymizing data and the risks of reidentification. These privacy protections are vital in domains like healthcare, finance, and social media analytics.

### Key Techniques

#### 1. **K-Anonymity**
A dataset satisfies k-anonymity if each individual cannot be distinguished from at least \( k - 1 \) others. This prevents unique identification based on quasi-identifiers like age, ZIP code, or gender.

**Limitation**: Vulnerable to external dataset linkage attacks (e.g., Latanya Sweeney’s famous work).

#### 2. **Generalization**
Replaces specific values with broader categories. For example:
- Age 18 → Age range 18–25
- Religious denominations → Broader categories like "Christian"

**Limitation**: Reduces data precision and utility.

#### 3. **Suppression**
Hides or replaces high-risk values with placeholders (e.g., \* or -). For example, rare diseases or unique traits like "Hindu + female + age 61–75 + COPD" might warrant suppression.

#### 4. **Obfuscation (Noise Addition)**
Slightly alters numerical values to protect identity:
- Height (cm) ± 5cm
- Weight (kg) ± 1kg

**Limitation**: Still vulnerable to sophisticated attacks and statistical reversibility if too predictable.

---

## Combining Techniques for Stronger Privacy

The most effective strategy is to use a **combination** of techniques:
- Replace names with unique IDs
- Bin ages into ranges
- Generalize or suppress rare attributes
- Add noise to quantitative data

Also, consider the **context of the study**. If diagnosis is the focus, suppress religious data. If religion is relevant, consider omitting specific diagnoses.

---

## Emerging Threats: AI and Reidentification

Modern AI tools (e.g., large language models) can detect patterns far more efficiently than traditional analysis methods. This makes it easier to:
- Reidentify individuals from "anonymized" data
- Discover correlations that may compromise privacy

### Why This Matters:
- External datasets are increasingly public (e.g., on Kaggle)
- Data storage is cheap, leading to longer retention and more risk
- LLMs are powerful tools for pattern recognition, even for non-experts

**Implication**: Anonymization methods must evolve to address these threats. Techniques like **differential privacy** and tighter access controls are becoming more relevant.

---

## Ethical Foundations: Informed Consent

The most important takeaway is the principle of **informed consent**:
- Participants must know what data is collected
- How it will be stored and used
- Whether it will be shared or sold
- When and how it will be deleted
- What guarantees and limitations exist

If you collect data, you are responsible for protecting it—and the trust of those who provide it.

---

## Summary of Key Points

- K-anonymity helps hide individuals in a crowd but is not foolproof
- Generalization and suppression reduce identifiability at the cost of precision
- Noise can obfuscate data but doesn't guarantee protection
- AI and public datasets increase reidentification risks
- Informed consent is the ethical foundation of data collection

---

## Looking Ahead: AI and LLMs

Our next topic will explore **Artificial Intelligence** and **Large Language Models** (LLMs). We’ll discuss:
- What AI *actually* means in computer science
- How machine learning and neural networks function
- What a language model is, and how it’s trained
- Misconceptions around intelligence and consciousness in AI

An exercise using ChatGPT will be posted for Friday, and we’ll begin our technical deep dive on Monday.

Thank you all for showing up this semester, especially in person. And yes—you’ll get a clicker point for today’s poll: “What’s your favorite letter?”

> Spoiler: Most of you said A or B.

Until next time!

