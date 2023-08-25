### Main Branches:

:angel: Master/Main: Represents the stable, production-ready code. All code in this branch should be deployable.

:angel: Develop: Integration branch for ongoing development. Features and bug fixes are merged here for testing and integration.

## Supporting Branches:
Feature Branches: Used to develop new features or enhancements. Created from develop and merged back into it when the feature is complete.
Release Branches: Created to prepare for a new release. Bug fixes and minor improvements are made here. Once ready, merged into both master/main and develop, and tagged with a version number.
Hotfix Branches: Address critical bugs in the production code. Created from master/main, fixed, and then merged into both master/main and develop.

## WORKFLOW STEPS

-Feature Workflow:
Create a new feature branch from develop.
Work on the feature, committing changes to the feature branch.
Once the feature is complete, merge the feature branch back into develop.

-Release Workflow:
Create a new release branch from develop.
Perform final testing and bug fixing in the release branch.
Merge the release branch into both master/main and develop.
Tag the release on the master/main branch.

-Hotfix Workflow:
Create a new hotfix branch from master/main.
Fix the critical bug in the hotfix branch.
Merge the hotfix branch into both master/main and develop.
Tag the hotfix on both branches.

Versioning:
Versions are typically represented by tags on the master/main branch and the release branches. Semantic versioning (e.g., X.Y.Z) is commonly used.

[Go](considerations.md)

## Quick Links

- [Readme](../readme.md)
- [1. GitFlow Introduction](Git-Flow-Introduction.md)
- [2. Main strategies](Main-strategies.md)
- [3. Considerations](considerations.md)
- [4. Git Commands](Git-Commands.md)
- [5. Feature branch merge conflict](featureBranchMergeConflict.md)
- [6. Long runnin feature branches](long-runninFeatureBranches.md)
- [7. Hotfix](mergingHotFixintoDevelo.md)
- [8. Release branch bugs](releaseBranchBugs.md)
- [9. Release Stagnation](releaseStagnation.md)
- [10.Unclear version](unclearVersioning.md)