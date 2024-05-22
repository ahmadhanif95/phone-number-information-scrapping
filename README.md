# Phone Number Separator

This project aims to separate landline and cell phone numbers from a given list of phone numbers. It provides a straightforward solution for categorizing phone number data based on their service type.

## Table of Contents

- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)


## Features

- **Differentiation of Landline and Cell Phone Numbers**: It efficiently distinguishes between landline and cell phone numbers.
- **Customizable Rules**: Users can customize separation rules based on area codes or number patterns.
- **Simple Interface**: The interface is user-friendly, allowing easy input and processing of phone numbers.

## Installation

To utilize this project, ensure you have Python installed on your system. Follow these steps to set up the project:

1. Clone the repository:
   ```sh
   git clone https://github.com/ahmadhanif95/phone-number-information-scrapping.git
   ```
2. Navigate to the project directory:
   ```sh
   cd phone-number-separator
   ``
   ```

## Usage

1. Prepare a text file (e.g., `phone_numbers.txt`) containing the list of phone numbers, with each number on a new line.
2. Run the script to separate the numbers:
   ```sh
   python separate_numbers.py phone_numbers.txt
   ```
3. The script will generate two output files: `landlines.txt` and `cellphones.txt`, containing the separated numbers.

## Contributing

Contributions to enhance this project are welcomed. To contribute, follow these steps:

1. Fork the repository.
2. Create a new branch:
   ```sh
   git checkout -b feature/your-feature
   ```
3. Make your changes and commit them:
   ```sh
   git commit -m 'Add your feature'
   ```
4. Push to the branch:
   ```sh
   git push origin feature/your-feature
   ```
5. Open a pull request.

---

Feel free to reach out with any questions or concerns. Happy coding!
