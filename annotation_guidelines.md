# Text Annotation Guidelines

## 1. Purpose

These guidelines define how to assign sentiment labels to text records consistently. They are intended for a small demonstration dataset used in an AI training portfolio.

## 2. Available Labels

### Positive
Use when the text clearly expresses satisfaction, praise, approval, or a favorable opinion.

Example: "The delivery was fast and the service was excellent."

### Negative
Use when the text clearly expresses dissatisfaction, criticism, a complaint, or an unfavorable opinion.

Example: "The application crashes whenever I open it."

### Neutral
Use when the text provides factual information without a clear positive or negative opinion.

Example: "The appointment is scheduled for Thursday."

### Mixed
Use when the same text contains meaningful positive and negative sentiment.

Example: "The food was cold, but the staff were friendly."

## 3. Annotation Procedure

1. Read the entire text before assigning a label.
2. Identify the main sentiment expressed.
3. Apply the label definitions consistently.
4. Write a short reason supporting the decision.
5. Flag ambiguous cases for review.

## 4. Decision Rules

- Do not infer sentiment that is not supported by the text.
- A factual statement is Neutral unless it clearly expresses an opinion.
- A complaint should be Negative even if it is written politely.
- Use Mixed when both positive and negative sentiment are clearly present.
- If the meaning is unclear, flag the record for review rather than guessing.
- Do not use punctuation or capitalization alone to determine sentiment.

## 5. Quality Assurance Checks

Before finalizing annotations, verify that:

- Every record has a unique identifier.
- Every record has a valid label.
- Each reason matches the text and its assigned label.
- Mixed sentiment is handled according to the rules.
- No required fields are missing.
- Inconsistent or ambiguous cases are flagged.

## 6. Scope

These rules apply to this portfolio's sample sentiment-classification task. Different AI annotation projects may use different label definitions and instructions. Always follow the client or project-specific guidelines when working on a real task.
