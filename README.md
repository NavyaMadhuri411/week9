
# Experiment 9: JSON Generation and Validation Using an LLM

## Aim
To generate structured JSON using an LLM and validate the
output for syntax and schema correctness.

## Problem Statement
Generate a JSON array describing exactly three books.
Each object must contain title, author, and year.

## Tools Used
- Python
- Google Gemini API
- Google Gen AI SDK
- Google Colab

## Algorithm
1. Define the initial JSON prompt.
2. Send the prompt to the LLM.
3. Parse the response using json.loads().
4. Validate the JSON array and required fields.
5. If validation fails, retry with a stricter prompt.
6. Validate and print the final result.

## Constraints
- Output valid JSON only.
- Use double quotes for keys and strings.
- Do not use trailing commas.
- Include exactly three book objects.
- Every object must contain title, author, and year.
- Use temperature 0.

## Expected Output
A valid JSON array containing three book objects with
the required fields and correct data types.

## Conclusion
The experiment demonstrates how an LLM can generate
structured data and how Python validation can identify
invalid JSON and schema violations.

## How to Run
1. Install dependencies:
   pip install -r requirements.txt
2. Configure your Gemini API key securely.
3. Run:
   python experiment.py

## Outputs
See the outputs folder for execution screenshots
and saved experiment results.
