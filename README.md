# Test_022
This project is part of a benchmark / test suite used to check the different git histories created through different development processes. The test suite is meant to be processed by SPHA-Code-Integrity.

## Textual Description
Expected Commits against integrity rules :
* Squashed Commit

## Changes Made In This Repo

* Create a feature branch from main and make a commit on that branch.
* Create a second commit on the main branch.
* Merge the feature branch with the main branch without PR.
* Squash the last 2 commits on the main branch so that there are only 2 commits on the main branch and activity shows a force push
* Squash all the commits from root to the previously squashed commits so activity shows 2 force pushes.
