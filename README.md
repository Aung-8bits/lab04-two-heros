# lab04-two-heros
# Lab 4: Collaborating on a Shared GitHub Repository

## 1. Group Name
two-heros

## 2. Who Did What

| Group Member | Contribution |
|---|---|
| Member 1 –  Aung Myo Htet| Set up the GitHub repository, created the `.gitignore` file, and added `conftest.py`. |
| Member 2 – Aung Chan Nyein | Created the remaining Python files, including `bank.py` and the test files. |

## 3. Our Merge Conflict

We created a merge conflict when both members edited the same section of `README.md`. We resolved the conflict by keeping the information from both members and removing the conflict markers.

## 4. Git Contribution Summary

Paste the actual output of `git shortlog -sn` here.

## 5. Reflection Questions

### Q1. Why was the push rejected, and how did you fix it?

The push was rejected because the GitHub repository had changes that were not in our local repository. We needed to pull the latest changes, resolve any conflicts, and push again.

### Q2. Why could Git not resolve the conflict automatically?

Git could not decide how to combine the changes because both members edited the same part of the file. We resolved the conflict manually.

### Q3. What is the difference between committing and pushing?

Committing saves changes in our local repository. Pushing uploads those changes to GitHub so other members can see them.

### Q4. Why do we use fixtures in pytest?

Fixtures provide reusable objects and setup for tests. They reduce repeated code and make testing easier to manage.
