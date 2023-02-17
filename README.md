# Testing Best Practices

# Unit Testing

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

## 3. Avoid Magic Strings / Values:

Well named constants explicitly show what you're trying to prove, and avoid confusion for test contributors / maintainers.

## 4. Avoid logic in tests:

You have a lesser chance of introducing bugs in your tests, with a focus on your end results, rather than the implementation details.

## 5. Test one scenario per test:

To ensure when the test fails it's clear which test is failing, and where it's failing.

## 6. Write deterministic tests:

Deterministic tests have a consistent behaviour every time the test is run.

## 7. Avoid test interdependence

## 8. Avoid tightly coupled code (Coding best practice to enable seamless testing) 

# Integration Testing

# What is Integration Testing ?

Integration testing covers integration between various modules and third-party tools, and APIs consumed by your application, to ensure that each unit works as expected when in collaboration with other units.

`NB!`

Make sure to reset test data to it's initial state between test execution.
- This ensures that your tests are not dependent on any other part of the system and can be run independently.
