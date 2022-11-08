# Introduction
This is the profile readme of DevOps Oct2022 Team 1. It details the roles of the team members as well as the scrum and development processes that we adhere to.

## Team Members & Roles
| Name | Role | Description |
|---|---|---|
Dong En | Scrum Master | Facilitate scrum processes and enforces scrum practises
Wen Kang | Lead Developer | Facilitate scrum processes and enforces scrum practises
Vernon | Quality Assurance | Test Cases for component and above level tests
Lincoln | Quality Assurance | Test Cases for component and above level tests
Balqis | Developer | Development and more development

## Software & Tools
- **Visual Studio Code**: IDE of choice
- **Github**: Keeps a backup copy of the source files, also serves for remote collaboration for distributed teams.
  - **Github Projects**: Scrum board
  - **Github Actions**: CICD

## Tech Stack & Dependencies
| Name | Description | Link |
|---|---|---|
|Python|Backend Language|https://docs.python.org/3/|
|Pytest|Python Testing Framework|https://docs.pytest.org/en/7.1.x/contents.html|

# Development & Scrum Workflow
Below details the workflow that developers should adhere to during development. It is ordered sequentially.
## Requirements Gathering & Analysis
- Our requriements illication method of choice will be document review
- **Requirements Analysis**
## Backlog Issues & Test Cases
- Creating Issues
  1. Create an issue with a meaningful name in product backlog
  2. Under the issue description
     1. Add in the Requirements section
     2. Add in the Pull Requests section
- Creating Test Cases
    1. Test cases will be created for each user story
        - These tests should be integration or system tests (strictly not unit tests)
    2. Test cases should follow the below format
        | ID | Name | Description | Value/Steps | Result |
        |---|---|---|---|---|
        |1|Navigate to contact us|When an existing user .... |1. 2. 3.|url="..."|
## Development & Git
- During Sprint Planning
    1. Assign the issue to a repository
    2. Estimate the issue size
    3. Add a priority
- Starting Development & Branching Issues
    1. Create a branch from the issue and use it for development (25-develop locking mechanism)
    2. Assign the issue to yourself and move it to "In Progress"
    3. In the event a new branch is needed, use the same issue number (25-new locking mechanism)
    4. Under the description section of each issue, add comments to update the progress of your issue. Developers should only comment important information that is relevant to share to the team. (Subjective but just don't put too much insignificant stuff)
- TDD
    1. Development will be done using a TDD approach (Unit Tests)
    2. Integration and System tests will be introduced after the completion of the relevant features
- Merge Strategy
    1. Development of enhancements or bugs will be done in their respective branches and merged back into main when completed. 
    2. **Merging of working code is to be done at least once a day, this is done to encourage everyone to be working on the same set of code and resolve all issues during development**
## Pull Requests
- Creating Pull Requests
    1. When code is ready to be merged back into main, developers are to make a pull request
    2. Pull Requests should contain a meaningful description to summarise the changes
    3. Developers are to ping the relevant reviewers in telegram 
    4. and add the pull reuquest to the relevant issue
- Reviewing Pull Requests
    1. When reviewing pull requests, developers should test the code that has been changed locally
    2. To approve the pull request, approve the code or add a LGTM and merge it
## Completing Issues
- Updating Issues
    1. Ensure that all code is merged into main and working
    2. Ensure that the issue has been updated 
        - Requirements, Pull Requests, Comments/Updates
    3. Move the issue to "In Review" (Max 2 days before Sprint Review)
- Reviewing Issues
    1. Review the requriements of the issue and verify that it is working in main
    2. Review the code if necessary 
    3. If the issue is done
        1. Add a LGTM
        2. Close the issue
        3. Move it to Ready
    4. If the issue requires changes
        1. Add a comment detailing the change and move it back to "In Progress"

# Misc
## Git Strategy
- Merging VS Rebasing
## Deployment Strategy
- NIL for now
## CI/CD
- Pipeline stuff
- Unit tests in pipeline
- Integration and system tests in pipeline
## Adjusting to Changing Requirements
- Adding new tickets mid sprint
## Scrum & Processes
- Working as a team to accomplish sprint goals
- Scrum processes
- Scrum board
![image](https://user-images.githubusercontent.com/73124349/200510538-ce785acb-1849-4285-9f3e-aa576b8d341d.png)
