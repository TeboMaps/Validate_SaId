# Validate South African ID

This Java project focuses on **unit testing** and **Test-Driven Development (TDD)** by implementing a validator for South African ID numbers.

## 🚀 Objective

Your mission is to create a function called `isIdNumberValid(String id)` that verifies whether a South African ID number is valid. The function should return `true` for a valid ID number and `false` otherwise.

## 🧪 Key Concepts Practiced

- Unit Testing using **JUnit**
- Test-Driven Development (**TDD**) - RED, GREEN, REFACTOR cycle
- Java development with **Gradle**
- Logical validation through condition checking
- Implementation of the **Luhn algorithm** for checksum validation

## 📋 South African ID Format

A South African ID number has **13 digits** and follows the format: `YYMMDDSSSSCAZ`.

- **YYMMDD**: Date of birth (e.g., `920220` for 20 Feb 1992)
- **SSSS**: Gender (0000–4999 for females, 5000–9999 for males)
- **C**: Citizenship (0 = SA citizen, 1 = permanent resident)
- **A**: Usually 8 or 9, reserved for future use
- **Z**: Checksum digit (validated using the **Luhn algorithm**)

## 🔧 Setup Instructions

1. **Install Gradle** (if not already installed)
2. Initialize your project using:
   ```bash
   gradle init
