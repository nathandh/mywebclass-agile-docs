# Initiative: Develop a web-based application that provides curated content for technology education.
## Epics
* [Project Infrastructure and Initial Setup](./epics/epic_project_infra_and_initial_setup.md)
* [MyWebClass Site Creation](./epics/epic_mywebclass_site_creation.md)
* [MyWebClass Should Be Search Engine Friendly and Provide Usage Analytics]()
* [Ensure Legal Compliance with GDRP, CCPA, and any other compliance entities where our users are.]()
* [Setup Automatic Deployment and Testing (CI/CD)]()
## Test plan
Iterative and continuous testing as development is done. This includes at minimal some forms of Unit testing to ensure 
components functionally render as intended. 

The preliminary planned testing stack is as follows:

* Jest for Unit Tests in JS frontend code: https://jestjs.io/

* Playwright for End-To-End Testing. Written in SPEC format, with support of Python at the Docker Container 
  Level: https://playwright.dev/

### Load Testing
There is initial consideration and potential of using Artillery with Playwright to achieve Load Testing: 
* https://www.artillery.io/docs/guides/guides/playwright
* https://github.com/artilleryio/artillery-engine-playwright#readme
In this scenario, we can simulate thousands of users visiting our site to stress test our application. It would provide 
us the ability to see how our application will scale as our user base grows. 