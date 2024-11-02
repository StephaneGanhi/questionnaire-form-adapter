# Adapted Questionnaire Form Script

## Overview
This repository contains a Python script (`formulaire.py`) designed to adapt a questionnaire into a format suitable for teleform data collection. The script processes an input questionnaire, applies standardized coding rules, skip logic, and highlights terms that require clarification. It then exports the adapted questionnaire as a Word document with input fields for easy electronic administration.

## Features
- **Standardized Coding Rules**: Ensures uniform coding for questions.
- **Skip Logic Identification**: Marks questions that include skip instructions.
- **Clarification Check**: Flags questions that may need further explanation.
- **ASCII Formatting**: Ensures questions are formatted for compatibility.
- **Word Document Export**: Outputs the formatted questionnaire as a `.docx` file with input fields.

## Requirements
- Python 3.x
- `pandas` library
- `python-docx` library

## Installation
1. Clone this repository:
   ```bash
   git clone https://github.com/StephaneGanhi/questionnaire-form-adapter.git
   ```
2. Navigate to the project directory:
   ```bash
   cd questionnaire-form-adapter
   ```
3. Install required Python libraries:
   ```bash
   pip install pandas python-docx
   ```

## Usage
1. Place your questionnaire data in a suitable format (e.g., CSV or DataFrame).
2. Run the `formulaire.py` script to process and generate the Word document:
   ```bash
   python formulaire.py
   ```
3. The output file `adapted_teleform_questionnaire.docx` will be created in the same directory.

## Example Output
The generated Word document includes:
- The question text.
- Input fields for numeric, text, and Yes/No answers.

## Contribution
Contributions are welcome! Feel free to open issues or submit pull requests.

## License
This project is licensed under the MIT License.

## Contact
For questions or further information, please contact Stephane Ganhi at stephaneganhi@hotmail.com.
