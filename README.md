# LLM Translation Sets

This repository provides tooling for translating enterprise SaaS applications using large language models (LLMs). Applications are composed of a base app and multiple modules. For each module, translation strings are exported to Excel, translated by an LLM, and written back to a format that can be re-imported into the application.

## Workflow

1. Open and read the exported translation set (.xlsx).
2. Invoke an LLM with the strings and contextual information about the app.
3. Parse the model's responses and generate a translated Excel file.

This project aims to automate the entire pipeline from export to re-upload so that apps can quickly support multiple languages.
