# Chapter 4: White Box Testing & Experience based Testing

Actual Notes: [Chapter 1](file:///C:/Users/User/Desktop/DegStud/Sem%207%202021/CSEB424%20Software%20Testing/chapter_4.pdf)

Terminology: [Glossary](https://glossary.istqb.org/en/search/)

-----

## White Box Testing

-----
### Statement Testing and Coverage
-----

- Exercises the potential executable statements in the code.
- Coverage
  - the number of statements executed by the tests divided by the total number of executable statements in the test object
  - normally expressed as a percentage.

-----
### Decision Testing and Coverage
-----
![decision_testing_and_coverage](decision_testing_and_coverage.png)

-----
## Experience-based Test Techniques
-----
### Error Guessing
-----

- technique used to anticipate the occurence of errors, defects, and failures, based on the tester's knowledge
- Requires knowledge on:
  - How the application has worked in the past
  - What kind of errors tend to be made
  - Failures that have occured in other application
- Methodical approach
  - to create a list of possible errors, defects and failures
  - design tests that will exposed those failures and the defects that caused them

-----
### Exploratory Testing
-----

- Informal (not pre-defined) tests are designed, executed, logged, and evaluated dynamically during test execution.
- Test results:
  - to learn more about the component or system
  - to create tests for the areas that may need more testing
- Session-based testing
  - to structure the exploratory activity
  - conducted within a defined time-box
  - the tester use a test charter containing test objectives to guide the testing
  - The tester may use test session sheeets to document the steps followed and thhe discoveries made.
- Most useful when:
  - there are few or inadequate specifications or significannt time pessure on testing
  - to complement other more formal testing techniquues
- Strongly associated with reactrive test strategies
- May incorporate the use of other black-box, white-box, and experience-based testing

-----
### Checklist-based Testing
-----

- testers design, implement, and execute tests to cover test conditions
- Testers may create:
  - a new checklist
  - expand an existing checklist
  - use an existing checklist without modification

#### Basis for creating checklists

- Experience
- Knowledge about what is important for the user
- An understanding of why and how software fails

#### Purpose of Checklists

- to support various test types: functional and non-functional testing
- checklist-based testing can provide guidelines and a defree of consistency in the case of absence of detailed test cases.