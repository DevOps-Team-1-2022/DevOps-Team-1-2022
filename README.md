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
- Requirements Analysis???
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
- Starting work on issues
     1. During Sprint Planning
        1. Assign the issue to a repository
        2. Estimate the issue size
        3. Add a priority
     2. During Development
        1. Create a branch from the issue and use it for development
        2. In the event a new branch is needed, use the same issue number
- TDD
- Branching Issues
- Merge Strategy
## Pull Requests
- Creating Pull Requests
- Reviewing Pull Requests
## Completing Issues
- Updating Issues
- Reviewing Issues

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
![image](https://user-images.githubusercontent.com/73124349/200510538-ce785acb-1849-4285-9f3e-aa576b8d341d.png)
