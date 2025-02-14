# Python-Activity-1
# Employee Data Processing Script

This project is a Python script that processes employee data from a CSV file, performs salary and department analysis, and outputs the results to both the console and a text file (`results.txt`).

## Features

- **Salary Analysis:**
  - Calculates the total number of employees with valid salary data.
  - Computes the average salary of all employees.
  - Identifies the employee with the highest salary.

- **Department Analysis:**
  - Counts the number of employees in each department.

- **Data Validation:**
  - Tracks and reports missing or invalid salary values.

- **Output:**
  - Results are printed to the console and written to a file (`results.txt`).

## How to Run the Code

### Prerequisites

- Python 3.x installed on your system. You can download it from [here](https://www.python.org/downloads/).

### Steps to Run

1. **Clone the repository** to your local machine using the following command:

   ```bash
   git clone https://github.com/aleenavarghese29/employee-data-processor.git



This Python script processes employee data from a CSV file, analyzes salary and department data, and outputs results to the console and a text file.

## Features

- Calculates total employees, average salary, and highest salary.
- Counts employees per department.
- Handles missing and invalid salary values.


2. ***Navigate to the project folder:***
   ```bash
   cd employee-data-processor
   ```
3. Ensure `emp_data_v2.csv` (with `name`, `salary`, `department` columns) is in the directory.
4. ***Run the script:***
   ```bash
   python process_employee_data.py
   ```
5. Check the console and `results.txt` for output.

## Assumptions & Design

- The CSV file must have `name`, `salary`, and `department` columns.
- Missing or invalid salary values are skipped.

## Challenges

- **Handling Missing/Invalid Data**: Solved by using try-except and skipping invalid values.
- **Dynamic CSV Column Positions**: Handled by detecting column indices from the header.

## License

This project is licensed under the MIT License.





   


