TestingWithPyTest
This repository contains a collection of examples demonstrating how to use Pytest for testing Python code. It's designed to help you understand the basics of writing and running tests using Pytest.​

📁 Repository Structure
The repository includes several test files, each illustrating different aspects of Pytest:​
GitHub
+1
GitHub
+1

test_one.py​
GitHub
+1
GitHub
+1

test_two.py​
GitHub
+4
GitHub
+4
GitHub
+4

three_test.py​

test_four.py​

test_five.py​

These files cover various testing scenarios and can serve as a reference for writing your own tests.​
GitHub

🛠 Installation
To get started, clone the repository and install the required dependencies:​

bash
Copy
Edit
git clone https://github.com/suba-learning/TestingWithPyTest.git
cd TestingWithPyTest
pip install -r requirements.txt
The requirements.txt file includes all necessary packages to run the tests.​

🚀 Running Tests
You can run all tests in the repository using the following command:​

bash
Copy
Edit
pytest
Pytest will automatically discover and execute all test functions in files matching the pattern test_*.py or *_test.py.​
GitHub

To run a specific test file:​

bash
Copy
Edit
pytest test_one.py
To run a specific test function within a file:​

bash
Copy
Edit
pytest test_one.py::test_function_name
📚 Learning Resources
For more information on Pytest and writing effective tests, consider exploring the following resources:​

Pytest Documentation

Pytest Tutorial

Effective Python Testing With Pytest

🤝 Contributing
Contributions are welcome! If you have examples or improvements to share, feel free to fork the repository and submit a pull request.​

📄 License
This project is licensed under the MIT License. See the LICENSE file for details.​

