# Good vs Bad Annotations

## Example 1: Text Classification

Text: "I cannot access my account after changing my password."

Good Annotation:
Label: Account Access

Bad Annotation:
Label: Technical Support

Reason:
The main issue is account access, not a general technical bug.

## Example 2: Sentiment

Text: "The new update is useful, but the app freezes too often."

Good Annotation:
Label: Mixed

Bad Annotation:
Label: Positive

Reason:
The text includes both praise and complaint.

## Example 3: Entity Labeling

Text: "I use Microsoft 365 for work at the University of St. Thomas."

Good Annotation:
- Microsoft 365: PRODUCT
- University of St. Thomas: ORGANIZATION

Bad Annotation:
- Microsoft: ORGANIZATION
- Thomas: PERSON

Reason:
The full product and organization spans should be captured.

## Example 4: Reviewer Feedback

Good Feedback:
"The label should be Billing because the user's primary concern is an incorrect invoice amount."

Bad Feedback:
"Wrong label."

Reason:
Good feedback is specific, explainable, and tied to the guideline.
