# Requirements

Configure a continuous integration workflow for an existing set of test suites using GitHub Actions.

Configure workflows that automate test runners for three different test suites.  For this assignment, it's okay to modify test cases as needed to accommodate the automated CI environment.

- [x] Create a github Action in EACH assignment repository (Unit, System and Behave) that runs the tests you created in those assignments whenever something is pushed to the main branch of those repos.
- [ ] Create a single workflow in THIS assignment repo (testing continuously) that executes tests on the code in the three repositories. Use the template run_tests.yml included in the starter code. You'll need to figure out how to checkout the correct repository and run the appropriate tests on that repository. 
 