"Setup Automatic Deployment and Testing (CI/CD)"

User Stories:
## List stories related to this Epic
1. [CI/CD Pipelines](./stories/story_ci_cd_pipelines.md)
2. [Code Standard Validation](./stories/story_code_standard_validation.md)

Dependencies: Completion or in Parallel with Epic [MyWebClass Site Creation](epic_mywebclass_site_creation.md)

Risks: Pipeline failures here can result in our site being down completely or broken in some way for our users. We 
can mitigate this risk by using industry standards for code validation, and up to date and stable packages and 
techniques for testing before release in each stage of pipeline; and, especially for release to Prod. 

Estimated Effort: 1 Full Sprint, where Sprints are 2 Week periods. (2 Weeks)

Priority: Medium