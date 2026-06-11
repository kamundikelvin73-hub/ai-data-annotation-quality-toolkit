# Sentiment Annotation Guidelines

## Objective

Classify the sentiment expressed in a text sample.

## Labels

| Label | Definition |
|---|---|
| Positive | The user expresses satisfaction, praise, or approval |
| Negative | The user expresses dissatisfaction, frustration, anger, or disappointment |
| Neutral | The user expresses facts without clear emotion |
| Mixed | The user expresses both positive and negative sentiment |

## Decision Rules

1. Label expressed sentiment, not assumed emotion.
2. Do not infer sentiment from topic alone.
3. If both praise and complaint are present, use Mixed.
4. If the text is factual and emotion is unclear, use Neutral.
5. Strong negative language should be labeled Negative even if polite.

## Examples

| Text | Label | Reason |
|---|---|---|
| The support team was very helpful. | Positive | Clear praise |
| The app keeps crashing and I am frustrated. | Negative | Clear dissatisfaction |
| My subscription renews tomorrow. | Neutral | Factual statement |
| The new design is nice, but the app is slower. | Mixed | Positive and negative elements |

## Common Errors

- Labeling a complaint as Neutral because it is politely written
- Labeling a factual technical issue as Negative without emotional language
- Ignoring mixed sentiment in longer comments
