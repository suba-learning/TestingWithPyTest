**[TestingWithPyTest](https://github.com/suba-learning/TestingWithPyTest)**:

---

# 🧪 TestingWithPyTest

This repository demonstrates how to write and run unit tests using [Pytest](https://docs.pytest.org/en/stable/) — a powerful Python testing framework. It’s ideal for beginners learning how to structure and execute tests in Python.

---

## 📂 Project Structure

The repo includes simple test files to help you learn the Pytest workflow:

```
TestingWithPyTest/
├── test_one.py
├── test_two.py
├── three_test.py
├── test_four.py
├── test_five.py
└── requirements.txt
```

Each file demonstrates different Pytest features like:
- Basic test functions
- Assertions
- Grouping tests
- Pytest naming conventions

---

## 🔧 Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/suba-learning/TestingWithPyTest.git
   cd TestingWithPyTest
   ```

2. (Optional) Create a virtual environment:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

---

## 🚀 Running the Tests

You can run all tests using:

```bash
pytest
```

To run a specific file:

```bash
pytest test_one.py
```

To run a specific test function:

```bash
pytest test_one.py::test_function_name
```

Use `-v` for verbose output:

```bash
pytest -v
```

---

## 📘 Learn More

- [Pytest Documentation](https://docs.pytest.org/en/stable/)
- [Real Python’s Pytest Tutorial](https://realpython.com/pytest-python-testing/)
- [Awesome Pytest GitHub](https://github.com/augustogoulart/awesome-pytest)

---

## 🤝 Contributing

Have a suggestion or want to add a new example? Feel free to fork this repo and create a pull request!

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

```
