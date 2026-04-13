# Module 11 Assignment
# FastAPI Calculation Model Project

## Overview
This project builds on Module 10 by adding a Calculation model to a FastAPI app. It uses SQLAlchemy to store calculation data and Pydantic to validate the input. The project supports four types of calculations: Add, Subtract, Multiply, and Divide. It also includes unit tests, integration tests, Docker, and GitHub Actions CI/CD.


## Features
- Secure user model with password hashing
- SQLAlchemy Calculation model
- Pydantic validation for calculation input and output
- Support for Add, Subtract, Multiply, and Divide
- Unit tests for calculation logic and schema validation
- Integration tests with PostgreSQL

## How to run locally
Create and activate a virtual environment:

```bash
python3 -m venv venv
source venv/bin/activate