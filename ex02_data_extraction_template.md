## 1. Choose an unstructured text (e.g., "John Doe, age 29, lives in Paris and works as a software engineer.").

a. Ehi Agaba, age 33, works as an AI engineer and lives in Port Harcourt

b. Ofugocho Ochoyo, age 14, lives in Otukpo, and is a student

## Create a template prompt:
**"Extract the following fields from the text: Name, Age, Location, Occupation. Return the output in JSON format."**

**prompt**
Extract the following fields from the text: [Ehi Agaba, age 33, works as an AI engineer and lives in Port Harcourt] Name, Age, Location, Occupation. Return the output in JSON format."

**AI's Response:**
```json
{
  "Name": "Ehi Agaba",
  "Age": 33,
  "Location": "Port Harcourt",
  "Occupation": "AI Engineer"
}
```
**Prompt**
Extract the following fields from the text: [Ofugocho Ochoyo, age 14, lives in Otukpo, and is a student] Name, Age, Location, Occupation. Return the output in JSON format."**

**AI's Output"**

```json
{
  "Name": "Ofugocho Ochoyo",
  "Age": 14,
  "Location": "Otukpo",
  "Occupation": "Student"
}
```

## Validate the output and ensure consistency across multiple inputs.
The output is correct across the two inputs used.
