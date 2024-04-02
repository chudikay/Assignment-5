# Data Transformation using Pandas and PyMySQL

A Python report showing the application of Data Transformation in Python on VG Sales data. The file provides a step-by-step tutorial on how to find average global sales and sorting into columns using Python MYSQL and Python Pandas. This repository contains Python scripts that show you how to carry out some data pre-processing in python using pandas package and MySQL codes in Python environment by creating a connection to the MySQL databases using sqlalchemy and pymysql. It explains importing data from a CSV file, creating dataframe,  executing basic and advanced SQL queries, and filtering and manipulating data using pandas.

## Getting Started
To get started with these scripts, Python will be installed along with the required libraries (pandas & pymysql). You will also need access to a MySQL database.

### Prerequisites
Python Notebook, pandas, pymysql, sqlalchemy and MySQL database

### Installing
Clone this repository to your local machine & install the required Python libraries using pip.

## Running the tests

To run the automated tests, you will need to follow these steps:

Install Testing Dependencies: If you haven't already, make sure you have installed the necessary testing dependencies. This typically includes the testing framework you've chosen, such as unittest or pytest. You can install them using pip:

graphql
Copy code
pip install unittest   # If you're using unittest
pip install pytest     # If you're using pytest
Write Test Cases: Write your test cases according to the structure and logic I provided earlier. Ensure that your test cases cover the relevant functionality of your data manipulation scripts.

Organize Test Files: Place your test files in a directory structure that makes sense for your project. For example, you might create a directory named tests and organize your test files within it.

Run Tests: To execute the automated tests, you will typically run a command in your terminal or command prompt. The exact command may vary depending on the testing framework you've chosen:

For unittest, you can run the tests using the following command:

Copy code
python -m unittest
For pytest, you can run the tests using the following command:

Copy code
pytest
These commands will automatically discover and execute your test cases.

Review Test Results: After running the tests, review the output in your terminal or command prompt. The testing framework will display information about which tests passed or failed and any relevant error messages.

Troubleshoot Failures: If any tests fail, review the error messages to understand why they failed. Make any necessary adjustments to your code or test cases to address the failures.

Repeat as Needed: Make changes to your code or test cases as necessary, and rerun the tests to ensure that your changes haven't introduced any regressions.

Integration with CI/CD: Optionally, you can integrate your automated tests with a continuous integration (CI) system in GitHub Actions or Travis CI. This will automate the process of running your tests whenever changes are made to your codebase, helping to catch regressions early.


### Break down into end to end tests

The purpose of the tests above and why they are important:

Test for SQL-based Data Manipulation Script:
Test for get_data_from_database Function:
What it tests: This test ensures that the get_data_from_database function retrieves data from the database correctly according to the specified SQL query.
Why it's important: This function is critical for fetching data from the database, which is the foundation of the data manipulation process. Ensuring that it retrieves the expected data ensures the correctness of subsequent data processing steps.
Test for pandas-based Data Manipulation Script:
Test for manipulate_data Function:
What it tests: This test verifies the correctness of the manipulate_data function, which likely performs data manipulation operations on a pandas DataFrame.
Why it's important: Data manipulation operations are central to the data transformation process. Verifying that these operations produce the expected results ensures the accuracy of the transformed data. It helps catch any logic errors or unexpected behavior that might lead to incorrect analysis or conclusions.
Why These Tests Are Important:
Ensuring Correctness: Both sets of tests ensure that the data manipulation scripts perform their intended functions correctly. By verifying the correctness of the functions, you can have confidence that the data transformation process produces accurate results.

Preventing Regressions: Automated tests serve as a safety net to catch regressions. If changes are made to the codebase in the future, running these tests can quickly identify if any modifications have inadvertently introduced bugs or caused existing functionality to break.

Facilitating Collaboration: Clear, well-structured tests make it easier for team members to understand the expected behavior of the code. They provide a form of documentation that helps new developers onboard onto the project and collaborate effectively with existing team members.

Maintaining Code Quality: By enforcing a testing discipline, you ensure that your codebase maintains a certain level of quality. It encourages writing modular, testable code and discourages practices that lead to tightly coupled, hard-to-maintain systems.

In summary, these tests play a crucial role in ensuring the correctness, reliability, and maintainability of your data manipulation scripts. They provide a safety net against regressions, facilitate collaboration among team members, and contribute to overall code quality.

### And coding style tests



## Deployment

Add additional notes about how to deploy this on a live system

## Built With

* Jupyter notebook in Anaconda
* MySQL database

## Contributing


## Versioning


## Authors

* **Chukwudi Kelvin Okpala** 

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

* Adepeju Onawoga, Gaabrielle Walters, Sheila Odor
