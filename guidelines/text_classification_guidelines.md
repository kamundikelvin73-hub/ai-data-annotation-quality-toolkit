# Text Classification Guidelines

## Objective

Assign one category label to each text sample based on the user's primary intent.

## Label Taxonomy

| Label | Definition |
|---|---|
| Account Access | Login, password, authentication, locked account, MFA |
| Billing | Payments, invoices, subscriptions, refunds |
| Technical Support | Bugs, crashes, device issues, software errors |
| Product Feedback | Feature requests, opinions, satisfaction comments |
| General Inquiry | Broad questions that do not fit other categories |

## General Rules

1. Read the entire text before assigning a label.
2. Choose the label that represents the main user intent.
3. Do not infer information that is not present.
4. If two labels apply, choose the most urgent or primary request.
5. Escalate unclear or multi-intent examples for reviewer discussion.

## Examples

| Text | Correct Label | Reason |
|---|---|---|
| I cannot log into my account after resetting my password. | Account Access | Main issue is login access |
| My invoice has the wrong amount. | Billing | The issue relates to billing |
| The app crashes whenever I open Zoom. | Technical Support | The user reports a software failure |
| I wish the dashboard had a dark mode. | Product Feedback | Feature request |
| What services do you offer? | General Inquiry | Broad informational question |

## Edge Cases

### Multi-intent text

Text: "I cannot log in and I was also charged twice."

Preferred label: Account Access if the main request is access recovery. Billing if the user primarily asks about the charge.

### Vague complaints

Text: "This is not working."

Preferred label: Technical Support if no other context is provided.

## Reviewer Notes

When correcting labels, provide a short explanation that references the guideline. Avoid vague comments such as "wrong label."
