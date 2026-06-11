# Entity Labeling Guidelines

## Objective

Identify and label named entities in text consistently.

## Entity Types

| Entity | Definition | Example |
|---|---|---|
| PERSON | Individual names | Kelvin Mureithi |
| ORGANIZATION | Companies, schools, agencies | Microsoft, Scale AI |
| LOCATION | Cities, countries, regions | Nairobi, Kenya |
| DATE | Calendar dates or time references | June 2026, tomorrow |
| PRODUCT | Software, platforms, or tools | Microsoft 365, Zoom |

## Annotation Rules

1. Label only explicit entities.
2. Do not label generic nouns.
3. Include the full entity span.
4. Avoid overlapping labels unless the project instructions allow it.
5. Preserve exact spelling from the source text.

## Examples

Text: "Kelvin works with Microsoft 365 at the University of St. Thomas."

| Entity | Label |
|---|---|
| Kelvin | PERSON |
| Microsoft 365 | PRODUCT |
| University of St. Thomas | ORGANIZATION |

## Ambiguous Cases

- "Apple" may be ORGANIZATION or generic noun depending on context.
- "Zoom" should be PRODUCT when referring to the meeting platform.
- "Washington" may be LOCATION unless referring to a person or organization.

## Quality Standard

A high-quality annotation must be complete, consistent, and explainable using the guideline.
