🧩 Assignment–I: Command Line TOPSIS Program
🔹 Objective

To implement the TOPSIS algorithm as a command-line Python program that accepts input parameters and generates a ranked output file.

🔹 Description

In this part, a Python script was developed that:

Takes a CSV file as input

Accepts weights and impacts from the command line

Applies the TOPSIS algorithm

Produces a new CSV file containing TOPSIS scores and ranks

🔹 Inputs

Input CSV file containing alternatives and criteria values

Weights (comma-separated)

Impacts (+ for benefit, - for cost)

Output CSV file name

🔹 Output

A CSV file containing:

TOPSIS Score

Rank of each alternative

🔹 Learning Outcome

Understanding of TOPSIS algorithm
🧩 Assignment–II: Python Package and PyPI Deployment
🔹 Objective

To convert the TOPSIS command-line program into a reusable Python package and publish it on PyPI.

🔹 Description

In this part:

The TOPSIS logic was modularized into a Python package

Proper package structure was created

setup.py and README.md files were written

The package was built using setuptools

The package was uploaded to PyPI using twine and API token authentication

🔹 Package Details

Package Name: topsis_atul_102103383

Version: 1.0.0

Dependencies: pandas, numpy

Command-line Tool: topsis

🔹 Verification

The package was tested by:

Installing it using pip

Running the topsis command from the terminal

Successfully generating output CSV files

🔹 Learning Outcome

Python packaging concepts

Building and distributing Python packages

Working with PyPI and API tokens

Real-world debugging and version control issues
🧩 Assignment–III: Web Service using Flask
🔹 Objective

To develop a web service that performs TOPSIS analysis through HTTP requests.

🔹 Description

In this part:

A REST-style web service was developed using Flask

The service accepts:

CSV file

Weights

Impacts

The server processes the input using the TOPSIS algorithm

The ranked result file is returned to the user

🔹 Technology Used

Flask (Web Framework)

Pandas & NumPy (Data Processing)

Python

🔹 Execution

The Flask application was run on a local development server

The service listens on port 5000

The application is suitable for academic and demonstration purposes

🔹 Learning Outcome

Basics of web services and REST APIs

Handling file uploads and downloads

Server-side data processing

Understanding deployment limitations in development environments
File handling in Python

Command-line argument processing
