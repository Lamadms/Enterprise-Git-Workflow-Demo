# Enterprise-Git-Workflow-Demo
This repository serves as a professional blueprint for managing complex software projects. It demonstrates how to transform Git from a basic saving tool into a powerful **Quality Assurance** and **Automation** system.

```mermaid
graph LR
    Main((Main Branch)) -- "Create" --> Feat(Feature Branch)
    Feat -- "cz commit" --> Commit[Standardized Commit]
    Commit -- "Pull Request" --> Review{Code Review}
    Review -- "Approved" --> Merge((Main Branch))
    Review -- "Rejected" --> Feat
