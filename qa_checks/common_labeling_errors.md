# Common Labeling Errors

## 1. Primary Intent Confusion

Incorrect:
Text: "I cannot log in and I need my invoice."
Label: Billing

Better:
Label: Account Access if the access issue is the main request.

## 2. Over-Inference

Incorrect:
Text: "My account is locked."
Label: Negative

Better:
Label sentiment as Neutral unless the user expresses frustration.

## 3. Inconsistent Entity Span

Incorrect:
"University" instead of "University of St. Thomas"

Better:
Label the full organization name.

## 4. Ignoring Mixed Sentiment

Incorrect:
Text: "Support was helpful, but the app still crashes."
Label: Positive

Better:
Label: Mixed

## 5. Vague Reviewer Feedback

Poor feedback:
"Wrong."

Better feedback:
"The main intent is account access, not billing, because the user is asking to recover login access."

## Error Severity

| Severity | Description |
|---|---|
| Critical | Incorrect label creates misleading training data |
| Major | Important guideline missed |
| Minor | Formatting or note issue |
