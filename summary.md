# 20 Review Web UI Testing with serenity 
# Resume

## Intro Serenity BDD
- Serenity is open source BDD Framework that helps making write well-structured and maintainable automated acceptance test.
- Serenity architecture consist of Requirements, Tests, Steps, Pages and Reports.

### Define Requirements 
- When using Serenity, you start with the requirements you need to impiement.
- These are often expressed as user "stories" with acceptance criteria that help clarify requirements.
- It is these "stories" that Serenity automate.

### Automate Acceptance Criteria
- Next, describe the acceptance criteria in high-level business terms.
- Record these acceptance criteria using either a BDD tool such as Cucumber with the form "feature" so taht serenity can run them.

### Implement the Test
- Implement the acceptance criteria into a code, so that they can run against the actual application.
- Under the hood, tests are broken down into nested steps for better readability and easier maintenance.

### Report on Test Result
Serenity provides detailed reports on the test result and execution, including :
- A narrative for each test.
- Screenshots for each step in the test.
- Test result including execution times and error messages if a test failed.
