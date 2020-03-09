# Structure of a Sprint

The purpose of this document is to:

- Organize the content in the playbook for quick reference and discoverability.
- Provide content in a logical structure which reflects the engineering process.
- Extensible hierarchy to allow teams to share deep subject matter expertise.

## A Wek in the Life of a CSE Project

### Before starting the project

<!-- TODO:
WORKING AGREEMENTS
  - [Working Agreements](team-agreements/working-agreements/readme.md)
  - [Definition of Ready](team-agreements/definition-of-ready/readme.md)
  - [Definition of Done](team-agreements/definition-of-done/readme.md)
  - [Estimation](sprint-planning/estimation/readme.md)

REPOSITORIES
  - [Decide on how many repositories and repository structures](source-control/readme.md)
  - Add the basics ([README.md](resources/templates/README.md), [LICENSE](resources/templates/LICENSE), [CONTRIBUTING.md](resources/templates/CONTRIBUTING.md), .gitignore, etc)

VERSIONING
  - Recipes for implementing Semantic Versioning
    - ADO Pipelines
    - Jenkins

PRODUCT BACKLOG
  - Guide to creating stories
    - INVEST
    - User story and acceptance criteria examples
    - Defining stories for Machine Learning
  - Recipes
    - Managing product backlog in ADO
-->

- [ ] [Discuss and write Team Agreements](team-agreements/readme.md)
- [ ] [Set up the repository/repositories](source-control/readme.md)
- [ ] [Determine a versioning strategy](source-control/versioning/readme.md)
- [ ] [Build a Product Backlog](backlog-management/readme.md)

### Day 1

<!-- TODO:
SPRINT PLANNING
  - Purpose, Goals, Participants, Facilitation Guidance, Impact, and Measures
  - Capacity Planning
  - Tasking
  - Dividing work WIP Limits
TEST FIRST DEVELOPMENT
  - Conceptual (Purpose, Goals, Impact, and Measures)
  - Developing Test Cases
  - [Unit Testing](test-first-development/unit-testing/readme.md)
    - Conceptual (Purpose, Goals, Impact, and Measures)
  - Load Testing
FEATURE BRANCHING
-->

- [ ] [Plan the first sprint](sprint-planning/readme.md)
- [ ] [Decide on test frameworks and discuss test strategies](test-first-development/readme.md)
- [ ] [Decide on branch naming for feature branches](source-control/feature-branching/readme.md)
- [ ] [Discuss security needs and verify secrets are kept out of source control](continuous-deployment/secrets-management/recipes/azure-devops/secrets-per-branch.md)

### Day 2

<!-- TODO:
SOURCE CONTROL
  - Commit best practices
  - [Git guide](source-control/git.md)
CONTINUOUS INTEGRATION
  - Conceptual (Purpose, Goals, Impact, and Measures)
    - Recipes for ADO
DAILY STANDUPS
  - Purpose, Goals, Participants, Facilitation Guidance, Impact, and Measures
    - What should be in my standup update
  - Recipes
    - How to run efficient standups for remote teams
SCRUM OF SCRUMS
  - Purpose, Goals, Participants, Facilitation Guidance, Impact, and Measures
-->

- [ ] [Set up Source Control](source-control/readme.md)
- [ ] [Set up basic Continuous Integration with linters and automated tests](continuous-integration/readme.md)
- [ ] [Set up meetings for Daily Standups and decide on a scrum master](stand-ups/readme.md)
- [ ] [If the project has multiple sub-teams, set up a Scrum of Scrums](scrum-of-scrums/readme.md)

### Day 3

<!-- TODO:
PULL REQUESTS
  - Conceptual requirements for pull request (it should build, have 1 reviewer, linked work item, build changes)
    - Add emphasis on importance of protecting master, effect this has on crew efficiency
  - Recipe for Setup in
    - Azure DevOps
    - GitHub
  - [Code Reviews](code-reviews/readme.md)
    - Conceptual
      - Add to checklist (breaking changes & backward compatibility, security, fault tolerance, etc)

CODE MERGING
  - prescribe strategy (i.e. squash /w or w/o rebase)
-->

- [ ] [Set up Build Validation for Pull Requests (2 reviewers, linters, automated tests)](pull-requests/readme.md) and agree on [Definition of Done](team-agreements/definition-of-done/readme.md)
- [ ] [Agree on a Code Merging strategy](source-control/git.md) and update the [CONTRIBUTING.md](resources/templates/CONTRIBUTING.md)
- [ ] [Agree on logging and observability frameworks and strategies](observability/readme.md)

### Day 4

<!-- TODO:
CONTINUOUS DEPLOYMENT
  - Conceptual, Purpose, Goals, Impact and Measures
    - Which environments (ci, test, stage)? For each environment...
      - Conceptually whats is the purpose for each env
      - When should deployment trigger
      - Pre-deployment approvers
      - Sign off for promotion
  - Recipes for Setting up CD Pipelines
    - Azure DevOps

-->

- [ ] [Set up Continuous Deployment](continuous-deployment/readme.md)
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
- [ ] [Groom the Backlog](backlog-management/grooming/readme.md)
- [ ] [Submit Engineering Feedback for issues encountered](engineering-feedback/readme.md)