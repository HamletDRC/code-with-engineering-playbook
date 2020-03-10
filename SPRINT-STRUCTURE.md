# Structure of a Sprint

The purpose of this document is to:

- Organize the content in the playbook for quick reference and discoverability.
- Provide content in a logical structure which reflects the engineering process.
- Extensible hierarchy to allow teams to share deep subject matter expertise.

## A Wek in the Life of a CSE Project

### Before starting the project

- [ ] [Discuss and start writing the Team Agreements](team-agreements/readme.md). Any decisions made throughout the project should be reflected in these documents.
  - Get started on [Work Agreement](team-agreements/working-agreements/readme.md), [Definition of Ready](team-agreements/definition-of-ready/readme.md), [Definition of Done](team-agreements/definition-of-done/readme.md), [Estimation](sprint-planning/estimation/readme.md)
- [ ] [Set up the repository/repositories](source-control/readme.md)
  - Decide on repository structure/s
  - Add [README.md](resources/templates/README.md), [LICENSE](resources/templates/LICENSE), [CONTRIBUTING.md](resources/templates/CONTRIBUTING.md), .gitignore, etc
- [ ] [Determine a versioning strategy](source-control/versioning/readme.md)
- [ ] [Build a Product Backlog](backlog-management/readme.md)
  - Set up a project in your chosen project management tool (ex. Azure DevOps)
  - INVEST in good User Stories and Acceptance Criteria

### Day 1

- [ ] [Plan the first sprint](sprint-planning/readme.md)
  - Agree on a sprint goal, and how to measure the sprint progress
  - Determine team capacity
  - Assign user stories to the sprint and split user stories into tasks
  - Set up Work in Progress (WIP) limits
- [ ] [Decide on test frameworks and discuss test strategies](test-first-development/readme.md)
  - Discuss the purpose and goals of tests and how to measure test coverage.
  - Agree on how to separate unit tests from integration, load and smoke tests
- [ ] [Decide on branch naming for feature branches](source-control/feature-branching/readme.md)
- [ ] [Discuss security needs and verify secrets are kept out of source control](continuous-deployment/secrets-management/recipes/azure-devops/secrets-per-branch.md)

### Day 2

- [ ] [Set up Source Control](source-control/readme.md)
  - Agree on best practices for commits
- [ ] [Set up basic Continuous Integration with linters and automated tests](continuous-integration/readme.md)
- [ ] [Set up meetings for Daily Standups and decide on a scrum master](stand-ups/readme.md)
  - Discuss purpose, goals, participants and facilitation guidance
  - Discuss timing, and how to run an efficient standup
- [ ] [If the project has multiple sub-teams, set up a Scrum of Scrums](scrum-of-scrums/readme.md)

### Day 3

- [ ] [Agree on code style](code-reviews/README.md) and on [how Pull Requests are assgined](code-reviews/pull-requests.md)
- [ ] [Set up Build Validation for Pull Requests (2 reviewers, linters, automated tests)](code-reviews/readme.md) and agree on [Definition of Done](team-agreements/definition-of-done/readme.md)
- [ ] [Agree on a Code Merging strategy](source-control/git.md) and update the [CONTRIBUTING.md](resources/templates/CONTRIBUTING.md)
- [ ] [Agree on logging and observability frameworks and strategies](observability/readme.md)

### Day 4

- [ ] [Set up Continuous Deployment](continuous-deployment/readme.md)
  - Determine what environments are appropriate for this solution
  - For each environment discuss purpose, when deployment should trigger, pre-deployment approvers, sing-off for promotion.
- [ ] [Desing a feature and conduct a Design Review](design-reviews/readme.md)

### Day 5

<!-- TODO:
SPRINT DEMO
RETROSPECTIVES
  - Conceptual
    - Inputs (Requirements to have ready before meeting)
    - Participants required
    - Outputs (Decisions, actions to conclude meeting)
  - Guide for retrospective facilitator
    - Timeline for 1 hour retro
    - Tips for sticking to time
    - Voting for action items
  - Recipes
    - Remote retros using ADO Retrospectives
    - Remote retros using Retrium
GROOMING
  - Conceptual
    - Inputs (Requirements to have ready before meeting)
    - Participants required
    - Outputs (Decisions, actions to conclude meeting)
  - Definition of ready for stories
    - Examples of well defined acceptance criteria
    - Can the story be tested as written
    - Can it be completed within a sprint
    - Is it dependent on other stories
  - [Estimation](sprint-planning/estimation/readme.md)
    - Resolving estimation conflicts (two people are sizing differently))-->

- [ ] Conduct a Sprint Demo
- [ ] [Conduct a Retrospective](retrospectives/readme.md)
  - Determine required participants, how to capture input (tools) and results
  - Set a timeline, and discuss facilitation, meeting structure etc.
- [ ] [Groom the Backlog](backlog-management/grooming/readme.md)
- [ ] [Submit Engineering Feedback for issues encountered](engineering-feedback/readme.md)