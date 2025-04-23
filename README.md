
Python API Automation Framework
Hybrid Custom API Automation Framework include the proper folder structure
![image](https://github.com/user-attachments/assets/99059265-5190-458f-9635-fcab6459ceeb)


Tech Stack
- Python 3.12
- Requests - HTTP Requests
- PyTest - Testing Framework
- Reporting - Allure Report, PyTest HTML
- Test Data - CSV, Excel, JSON, Faker
- Advance API Testcase - jsonschema
- Parallel Execution - x distribute (xdist)

How to Install Packages
- pip install requests pytest pytest-html faker allure-pytest jsonschema

How to run your Testcase in Parallel
- pip install pytest-xdist 

How to run the Basic Test with Allure report
- pytest tests/tests/crud/test_create_booking.py --alluredir=allure_result -s
