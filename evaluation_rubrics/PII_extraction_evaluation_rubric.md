# PII Extraction Evaluation Rubric

This rubric is used to evaluate the accuracy of AI extraction of personally identifiable information (PII) from text documents.

## Evaluation Categories

| Evaluation | Description |
|------------|-------------|
| Correct | The PII field was correctly identified and extracted |
| Partially Correct | The field was identified but incomplete or slightly incorrect |
| Missed | The PII field existed but was not extracted |
| Incorrect | The extracted information was incorrect |
| Extra Data | The model extracted data that was not requested or not PII |

## Evaluation Criteria

When evaluating extraction results, consider:
- Accuracy of extracted values
- Completeness of extracted fields
- Correct identification of PII types
- Whether any PII fields were missed
- Whether any incorrect data was extracted
- Consistency of structured output

## Purpose

This evaluation assesses the ability of AI systems to identify and extract personally identifiable information for privacy, data governance, and document review use cases.
