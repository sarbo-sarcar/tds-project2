# TDS Project 2

This repository presents the implementation of a solution for the "Tools in Data Science" course assignment at IIT Madras. The project leverages an LLM-based API that provides answers to almost all of the graded assignments 1 through 5 in the TDS course. The output generated by the API is ready to be submitted to the assignment portal since it directly generates the answer without any explanation or intermediate steps.

## Acknowledgements

The core functionality of this project is built upon the TDS Solver created by [Pradeep Mondal](https://github.com/pradeepmondal/tds-solver). His repository served as a foundational reference, and portions of the codebase have been adapted with minimal modifications to align with the objectives of this assignment.

## Project Overview

This project is an API designed to automatically answer graded assignment questions from the "Tools in Data Science" course at IIT Madras. It processes user-provided questions and optional file attachments to extract and return accurate answers.

## Features

- Accepts questions as input via API.
- Supports CSV and ZIP file uploads.
- Extracts answers dynamically from provided files.

## Installation

To set up the project environment:

1. Clone the repository:

   ```bash
   git clone https://github.com/sarbo-sarcar/tds-project2.git
   cd tds-project2
   ```

2. Install the required dependencies:

   ```bash
   pip install -r requirements.txt
   ```

## License

This project is licensed under the MIT License.
