# Unit Testing Best Practices

# What is unit testing ?

Unit testing occurs during the coding phase of the software development lifecycle, and it helps identify coding errors, code quality issues, and security issues.

Unit tests are typically created by developers during the coding phase of a project and are written as code that exists in the codebase alongside the application code it is testing.

A unit may be a function, procedure, method, object or module.

A unit test validates and verifies individual software units to ensure each unit works as intended.

# Best Practices:

## 1. Write Readable, Simple Tests:

### AAA Structure for Unit Tests:

- Arrange:

Configure the test by setting up the tested system and other mechanisms.

- Act:

Call an action to perform to test the unit

- Assert:

Check the result of the performed operation to verify it worked as intended.

## 2. Naming your tests:

Naming standards are important because they explicitly express the intent of the test.

The name of your test should consist of three parts:
- The name of the method being tested
- The scenario under which it's being tested
- The expected behaviour when the scenario is invoked



