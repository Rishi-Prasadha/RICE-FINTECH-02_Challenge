# Loan Qualification App

This application was created to help users determine their eligibility to obtain a loan from a predetermined list of lenders. This app takes a user's credit score, monthly debt, monthly income, desired loan amount and desired home value and matches those criteria against a list of requirements from various lenders

---

## Technologies 

This application runs on Python 3.7 with the following packages:

* **[fire](https://github.com/google/python-fire)** - For the command line interface, help page, and entry-point.

* **[questionary](https://github.com/tmbo/questionary)** - For interactive user prompts and dialogs


---

## Installation Guide

Prior to running the program, please install the following packages in either Terminal or Git Bash:

```python
pip install fire
pip install questionary
```

---

## Usage

To run this program, from the top of the repository, change directories into *loan_qualifier_app*:

```python 
cd loan_qualifier_app
```

 Proceed to type the following in the command line: 

```python
python app.py
```

Using questionary, this program will request user's credit score, monthly debt, monthly income, desired loan amount and desired home value and match it with a list of predetermined lenders. If there are any qualifying lenders, users will have the option to either save the list or forgo saving it. 

---

## Contributors

Thank you for Eric Cardena for teaching Rice's FinTech Boot Camp. He was instrumental in teaching and helping us understand this material. Thank you for Rice for preparing this curriculum and the corresponding data sets that are required to be used. 

**Rishi Prasadha**

**LinkedIn**: https://www.linkedin.com/in/rishi-prasadha-912212133/

**Instagram**: @therishiprasadha

**Twitter**: @RishiPrasadha

---

## Licenses 

MIT