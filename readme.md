# Gongguan OCR

Gongguan OCR is a project focused on Optical Character Recognition (OCR) and text layout tasks for the Gongguan (Kong Koan of Batavia) documents. 

## Repository Structure

The repository is organized as follows:

- **data/**: Contains datasets related to the Gongguan documents.
- **src/**: Includes source code for OCR and text layout processing tasks.

## Hugging Face API Keys

Hugging Face API keys must be stored in the `tokens/` directory.  

- Ensure that the `tokens/` directory is included in `.gitignore` to prevent keys from being pushed to the repository:

  ```bash
  # .gitignore
  tokens/
  ```

- API keys should not be hardcoded in scripts. They must be read from files in `tokens/` or set as environment variables.

API keys should not be hardcoded in scripts. They must be read from files in tokens/ or set as environment variables.