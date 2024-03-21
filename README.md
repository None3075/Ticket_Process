# Ticket_Process

This repository contains the code and resources for processing support tickets, from reading raw ticket data to creating a database and generating feedback reports. The process involves using the `pyesseract` library to extract text from ticket images or PDFs, storing the data in a database, and generating reports based on the feedback provided.

## Table of Contents

- [Getting Started](#getting-started)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [License](#license)

## Getting Started

To get started with this project, follow these steps:

1. Clone the repository to your local machine.
2. The instrucctions to follow the process are inside `process_and_references.pdf`.

## Usage

1. The raw ticket files (images or PDFs) are in the `tickets_raw` directory.
2. The `OCRScript.py` was used to extract text from the ticket files.
3. The processed data is already stored in the `database` directory which contains a dump of the mysql database.
5. The generated reports are stored in the `first_iteration_reports` and `second_iteration_reports` directories.
6. For further information about the process, check the `process_and_references.docx`

## Project Structure

- `database/`: Directory containing a dump of the mysql database with the processed ticket data.
- `first_iteration_reports/`: Directory for storing the initial feedback reports.
- `second_iteration_reports/`: Directory for storing the second iteration of feedback reports.
- `tickets_raw/`: Directory for storing the raw ticket files (images or PDFs).
- `LICENSE`: The license file for this project.
- `README.md`: This README file.

## License

This project is licensed under the [Apache License 2.0](LICENSE).
